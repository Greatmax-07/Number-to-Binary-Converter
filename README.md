Assignment 5:  Application of Recursive Function Call

Q] Develop a C program to calculate the sum of the first 10 numbers using recursive function calls and pointers.
   The program should define a recursive function that takes a pointer to an integer as an argument and returns
   the sum of the first 10 numbers. Within the function, recursion should be used to compute the sum iteratively.
   Finally, the program should display the calculated sum.

My ideation: 
Since binary language has only 0s and 1s, I thought of making a program that converts a natural number entered by user into binary language as this is a repeatative task.
I surfed the net, found out how the conversion is actually done, and applied the logic in the recursive function call accordingly.

Challenge faced:
According to the function that I defined, everything was right but the order of binary digits was being displayed in the reverse order. 
This was happening because I first printed the output followed by function call. Doing the opposite of this makes the recursion unfold in a reverse order and thus we get the desired output.
