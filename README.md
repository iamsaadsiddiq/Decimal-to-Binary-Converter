# Decimal-to-Binary-Converter

1) The main function prompts the user to enter a decimal number and reads it from the standard input.
2) The BinaryCalculation function takes the decimal number as an argument and performs the conversion.
3) Inside the BinaryCalculation function, an integer array arr of size 10 is declared to store the binary digits. 
4) The variable count is initialized to 0 to keep track of the number of binary digits generated. 
5) The variable binary is used to store the remainder when dividing num by 2.
6) The for loop starts with an initial value of i = 0 and continues until num becomes 0. 
7) In each iteration, it calculates the binary digit by taking the remainder of num divided by 2.
8)  It stores the binary digit in the arr array and updates num by dividing it by 2. Finally, it increments the count variable.
9) After the for loop finishes, the binary representation is printed using another for loop. 
10) It starts from the highest significant bit (stored at arr[count - 1]) and prints each binary digit in reverse order.
11) The program ends by returning 0 from the main function.

You can compile and run this code to convert decimal numbers to binary and see the results.
