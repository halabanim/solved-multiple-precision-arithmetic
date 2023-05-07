Download Link: https://assignmentchef.com/product/solved-multiple-precision-arithmetic
<br>
5/5 - (1 vote)

A singly-linked list can be used to store large integers one digit at a time. For example, the integer 1234 could be stored in a list by storing 1 in the first node, 2 in the second node, 3 in the third node, and 4 in the last node. However, for this you may find it more useful to store the digits backwards; that is, store 4 in the first node, 3 in the second node, 2 in the third node, and 1 in the last node.



Make a program that reads two positive integers that are of arbitrary length and then outputs the sum of the two numbers. The program will read the digits as values of type char so that the number 1234 is read as the four characters ‘1’, ‘2’, ‘3’, and ‘4’. As the characters are read they are changed to values of type int and stored in a list. After the first number has been read your program reads the second number, storing it in a second list.

The program will perform the addition by implementing the usual paper-and-pencil addition algorithm. The result of the addition is stored in a list and the result is then written to the screen. Include a loop that allows the user to continue to do more additions until the user says the program should end.

The multiple precision addition code should be formulated as a function that accepts a pair of lists, returning a list as its result (the sum of the two inputs)