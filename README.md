## Aim:
To write an 8085 microprocessor program to check whether a given 8-bit number is odd or even.
## Apparatus Required:
Laptop with an internet connection
## Algorithm:
1.	Load the number from a specified memory location into register A.
2.	Perform an AND operation with 01H to check the least significant bit (LSB).
3.	If the result is 0, the number is even; otherwise, it is odd.
4.	Store the result in a specific memory location (odd or even flag).
## Program:
IN 00H
ANI 01H
JZ EVEN
MVI A,01H
OUT 01H
HLT
EVEN: MVI A,00H
OUT 01H
HLT

## Output:
<img width="1918" height="867" alt="image" src="https://github.com/user-attachments/assets/38999ea8-ca24-4007-9709-6839e09c474d" />


## Result:
The 8085 microprocessor successfully checks whether a given number is odd or even and stores the result in memory.


