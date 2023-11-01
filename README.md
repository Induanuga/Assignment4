Question-1:
AccountType is an enum which contains savings and current
AccountInfo is a struct which contains details of the customers of the bank such as Account Number, Account Type, Name and Balance
Node is a struct which contains variable "data" of type AccountInfo(as typedef- struct AccountInfo to AccountInfo). Node also contains a pointer variable(next) to next Node. 
LinkedList is a Node pointer(pointer to a Node).
The variable accstart(integer) is assigned 100 as 100 should be the first account number.
The array "deleted_accno" stores account numbers which are deleted(to reuse them).
Integer n is the size of the deleted_accno array.
The function named fun1 takes AccountNumber(integer) as argument and return type is void. This function is used to add the deleted account numbers to the array deleted_accno.
The function named fun2 will not take any arguments but returns an integer and this function is used to get the available account numbers. If n(size of the array deleted_accno)>0 i.e, some accounts are deleted previously, then I sorted the array and took the smallest of all deleted account numbers , stored it in a variable AN(integer). Then I have removed the smallest element from the array and updated the size of array(decreased by one), return AN. If n is not greater than zero then I returned accstart++ which means return accstart and then update accstart i.e.,accstart=accstart+1.
The function named sizeofl takes argument as LinkedList and returns an integer which is the size of the LinkedList.
s is an array of characters (which is used to take commands like CREATE, DELETE, DISPLAY, EXIT etc..)
Name is an array of characters (string), Name array is used to take Name of the customer.


Question-2:
CN is a struct which contains a variable n (of integer type) and an array named coeff. coeff is an array of size 1000 which stores the coefficients of the complex number(which are of type float). Here n is the dimension of the complex number.
add function takes arguments c1 and c2 (two complex numbers) of type CN (struct CN) and returns a complex number i.e., add function takes two complex numbers as arguments and returns a complex number(whose coefficients are sum of coefficients of c1 and c2).
Similarly sub is a function that takes arguments c1 and c2 (two complex numbers) of type CN (struct CN) and returns a complex number i.e., sub function takes two complex numbers as arguments and returns a complex number(whose coefficients are difference of coefficients of c1 and c2).
dot is a function which takes arguments c1 and c2 (two complex numbers of type CN) and returns a float which is the dot product of the two complex numbers.
mod is a function that takes argument c (complex number of type CN) and returns a float which is the square root of sum of squares of all the coefficients of the complex number.
cosineSimilarity is a function which takes arguments c1 and c2 (two complex numbers of type CN) and returns a float which is division of dot product of c1 and c2 by mod(c1)*mod(c2).
print_cn is a function (takes argument c, complex number of type CN and returns nothing) that prints all the coefficients of the complex number(coefficients are floats correct upto 2 decimal places).
s is an array of characters(string) which is used to take commands like ADD, SUB, DOT, -1 etc.


Question-3:
Node is a struct which contains the variable,"data" (of type integer) and a pointer variable(next) which points to the next Node.
LinkedList is a Node pointer(pointer to a Node).
append is a function that takes a(integer)(data) and l(LinkedList) as arguments and returns a LinkedList. This function is used to append a node(whose data variable is a)to the end of the LinkedList. It first checks whether l==NULL if(l==NULL), then it creates a Node pointer 'N' and assigns data (of N) as 'a' and next(of N) as NULL. if(l!=NULL) then the function is called again with LinkedList as l->next and the returned LinkedList is assigned to l->next and then finally return l(updated LinkedList).
print_list is a function(whose argument is a LinkedList and return type is void) prints the Linked List.
delete function(whose arguments are i(integer)(data) and l(LinkedList) and returns a LinkedList). This function is used to delete a node(whose data variable is i)from the LinkedList. 
a is an array of integers which is used to take colors.



















# Assignment4
