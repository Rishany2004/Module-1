## Experiment No: 1d – Conditional Statements- Checking Vowel or not

## AIM  

To Write a Python program to check whether the given character is a vowel or not using if..else statement

## ALGORITHM  

1. Begin the program.  
2. Prompt the user to enter a year and read it as input.
3. Check the following condition using an if statement
4. If the year is divisible by 4 and not divisible by 100, or divisible by 400, then it is a leap year.
5. If the condition is true, print that it is a leap year.
6. Else, print that it is not a leap year.
7. Terminate the program.

## PROGRAM
```
a=int(input())
if(a%4==0 and a%100!=0 or a%400==0):
   print("Given year {} is a leap year".format(a))
else:
    print("Given year {} is not a leap year".format(a))
```

## OUTPUT

![image](https://github.com/user-attachments/assets/f9b17dad-659a-4551-8d77-a1e98d66f951)

## RESULT

Thus the Python program to check whether a given year is a leap year or not was successfully written and executed.
