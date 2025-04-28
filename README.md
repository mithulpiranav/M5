EX-21-POINTERS
# AIM:
Write a C program to convert a 23.65 into 25 using pointer

## ALGORITHM:
1.	Declare a double variable to hold the floating-point number (23.65).
2.	Declare a pointer to double to point to the address of the variable.
3.	Use the pointer to modify the value to 25.0.
4.	Print the modified value.

## PROGRAM:
![image](https://github.com/user-attachments/assets/23c986be-5910-4d90-8834-e683f9de112a)

## OUTPUT:

 ![image](https://github.com/user-attachments/assets/34324488-eeb1-4444-8b90-0b26f744b27a)







## RESULT:
Thus the program to convert a 23.65 into 25 using pointer has been executed successfully.
 
 


# EX-22-FUNCTIONS AND STORAGE CLASS

## AIM:

Write a C program to calculate the Product of first 12 natural numbers using Recursion

## ALGORITHM:

1.	Define a recursive function calculateProduct that takes an integer parameter n.
2.	Return n multiplied by the result of the calculateProduct function called with n - 1.
3.	Declare an integer variable n and an unsigned long long variable product.
4.	Initialize n with the value 12 (for the first 12 natural numbers).
5.	Call the calculateProduct function with n and store the result in the product variable.
6.	Print the result, indicating it is the product of the first 12 natural numbers.

## PROGRAM:
![image](https://github.com/user-attachments/assets/3c2b4248-cd58-4d09-8982-d8e39547a90c)

## OUTPUT:
![image](https://github.com/user-attachments/assets/10c99da4-8dee-4314-9e33-a6742945cc34)

         		
## RESULT:

Thus the program has been executed successfully.
 
 


# EX-23-ARRAYS AND ITS OPERATIONS

## AIM:

Write C Program to find Sum of each row of a Matrix

## ALGORITHM:

1.	Declare and initialize the matrix with the desired values.
2.	Create a loop to iterate through each row of the matrix.
3.	Inside the loop, calculate the sum of the elements in each row.
4.	Print the sum for each row.

## PROGRAM:
![image](https://github.com/user-attachments/assets/7431fa69-dd59-413f-9782-8ac469318c5e)



## OUTPUT

![image](https://github.com/user-attachments/assets/460f2b5e-8876-4bd1-b5e3-a6090b8c744e)

 
 

 ## RESULT
 


# EX-24-STRINGS

## AIM:

Write C program for the below pyramid string pattern. Enter a string: PROGRAM Enter number of rows: 5 P R O G R A M P R O G R A M P R O G R A M

## ALGORITHM:

1.	Input the number of rows for the pyramid (e.g., num_rows).
2.	Initialize variables:i for the row count (starting from 1),j for the character count (starting from 1)
3.	Start a loop for i from 1 to num_rows (for each row of the pyramid).
4.	Calculate the midpoint position as midpoint = (2 * num_rows - 1) / 2.
5.	End the program.

## PROGRAM:
![image](https://github.com/user-attachments/assets/639bc9e7-de46-406f-9f6b-1591732abc80)


 ## OUTPUT

 ![image](https://github.com/user-attachments/assets/c14cd6a1-9871-49f5-81b2-88b2bf55ab74)


## RESULT

Thus the C program to String process executed successfully
 

 
.



# EX -25 –DISPLAYING ARRAYS USING POINTERS
## AIM

Write a c program to read and display an array of any 6 integer elements using pointer

## ALGORITHM
Step 1: Start the program.
Step 2: Declare the following:
•	Integer variable i for iteration.
•	Integer variable n to store the number of elements.
•	Integer array arr[10] to hold up to 10 elements.
•	Integer pointer parr and initialize it to point to the array arr.
Step 3: Read the value of n (number of elements) from the user.
Step 4: Loop from i = 0 to i < n:
•	Read an integer value and store it in the address parr + i using pointer arithmetic.
Step 5: Loop from i = 0 to i < n:
•	Print the element at *(parr + i) using pointer dereferencing.
Step 6: End the program.

## PROGRAM
![image](https://github.com/user-attachments/assets/15afc4de-b315-4ecb-9ffe-95021fa94a93)

## OUTPUT
![image](https://github.com/user-attachments/assets/614b5d24-fbf4-4d83-82f4-8fdcdfdad20d)

 

## RESULT

Thus the C program to read and display an array of any 6 integer elements using pointer has been executed
