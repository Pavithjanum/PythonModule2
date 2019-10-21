# PythonModule2
Python Module2

Case Study1

1. What is the output of the following code? nums = set([1,1,2,3,3,3,4,4]) print(len(nums))
Hint: Set consists unique element.

2. What will be the output? d = {"john":40, "peter":45} print(list(d.keys())) Hint: d.keys() is the function which will show keys.

3. A website requires a user to input username and password to register. Write a program to check the validity of password given by user. Following are the criteria for checking password:
1. At least 1 letter between [a-z]
2. At least 1 number between [0-9]
1. At least 1 letter between [A-Z]
3. At least 1 character from [$#@]
4. Minimum length of transaction password: 6
5. Maximum length of transaction password: 12
Hint: In case of input data being supplied to the question, it should be assumed to be a console input.

4. Write a for loop that prints all elements of a list and their position in the list.
a = [4,7,3,2,5,9]
Hint: Use Loop to iterate through list elements.

5. Please write a program which accepts a string from console and print the characters that have even indexes.
Example: If the following string is given as input to the program:
H1e2l3l4o5w6o7r8l9d
Then, the output of the program should be:
Helloworld

6. Please write a program which accepts a string from console and print it in reverse order.
Example: If the following string is given as input to the program:
rise to vote sir
Then, the output of the program should be:
ris etov ot esir

7. Please write a program which count and print the numbers of each character in a string input by console.
Example: If the following string is given as input to the program:
abcdefgabc
Then, the output of the program should be:
a,2
c,2
b,2
e,1
d,1
g,1
f,1

8. With two given lists [1,3,6,78,35,55] and [12,24,35,24,88,120,155], write a program to make a list whose elements are intersection of the above given lists.
Module 2 - Sequence and File Operations

9. With a given list [12,24,35,24,88,120,155,88,120,155], write a program to print this list after removing all duplicate values with original order reserved.

10. By using list comprehension, please write a program to print the list after removing the value 24 in [12,24,35,24,88,120,155].

11. By using list comprehension, please write a program to print the list after removing the 0th,4th,5th numbers in [12,24,35,70,88,120,155].

12. By using list comprehension, please write a program to print the list after removing delete numbers which are divisible by 5 and 7 in [12,24,35,70,88,120,155].

13. Please write a program to randomly generate a list with 5 numbers, which are divisible by 5 and 7 , between 1 and 1000 inclusive.

14. Write a program to compute 1/2+2/3+3/4+...+n/n+1 with a given n input by console (n>0).
Example:
If the following n is given as input to the program:
5
Then, the output of the program should be:
3.55

Case Study2
Domain – Telecom
focus – Optimization
Business challenge/requirement
LifeTel Telecom is the latest entrant in the highly competitive Telecom market of Singapore. It issues SIM to the verified users. Till now verification was manual through the photocopy of approved id card document. However government has recently introduced Social ID called Reference ID which is mapped to fingerprint of user. LifeTel should now verify user against the fingerprint and Reference ID
Key issues
Build a system where when user enters Reference ID it is encrypted, so that hackers cannot view the mapping of Reference ID and finger print
Considerations
System should be secure
Data volume
- NA
Additional information
- NA
Business benefits
Company will be able to quickly issue SIM to user and expected gain in volume is approximately 10 times as the manual process of verification is replaced with secure automated system
Approach to Solve
You have to use fundamentals of Python taught in module 2
1. Read the input from command line – Reference ID
2. Check for validity – it should be 12 digits and allows on number and alphabet
3. Encrypt the Reference ID and print it for reference

Enhancements for code
You can try these enhancements in code
1. Allow some special characters in ReferenceID
2. Give the option for decryption to user
