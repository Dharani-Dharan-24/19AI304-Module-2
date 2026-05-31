# 19AI304 - Fundamentals of C Programming - Even Junior - 2026

# IAPR-2 - Module 2

# Exp.1 : Print 1 to n Odd Numbers

## Aim: 

To write a C program to print all odd numbers from 1 to a user-provided number n.

## Algorithm:

1. Get the input n from the user.
2. Loop from 1 to n.
3. Check if the current number is odd (num % 2 != 0).
4. Print the odd numbers.
5. End the program.

## Program:

```c
#include<stdio.h>
int main()
{
    int num,i;
    scanf("%d",&num);
    for(i=1;i<=num;i +=2){
        printf("%d ",i);
    }
    return 0;
}
```

## Output:

<img width="575" height="160" alt="502981380-2cc1a847-974a-48ed-a56b-2eb453965a0d" src="https://github.com/user-attachments/assets/67f10e9b-6062-4e93-90ca-84628d975572" />

## Result:

Thus, The C program to print all odd numbers from 1 to a user-provided number n was successfully executed.

***

# Exp.2 : Hollow Square Pattern using For Loop

## Aim:

Print a hollow square pattern of size n using for loops.

## Algorithm:

1. Get input the size n of the square from the user.
2. Loop through rows (1 to n) and columns (1 to n).
3. Print * for the borders (first row, last row, first column, last column).
4. Print space for inner positions.
5. End the program.

## Program:

```c
#include<stdio.h>
int main()
{
    int num,i;
    scanf("%d",&num);
    for(i=1;i<=num;i +=2){
        printf("%d ",i);
    }
    return 0;
}
```

## Output:

<img width="575" height="160" alt="502981380-2cc1a847-974a-48ed-a56b-2eb453965a0d" src="https://github.com/user-attachments/assets/a580d66f-37f5-45f7-900f-e70cff6e7592" />

## Result:

Thus, The C program to print a hollow square pattern of size n using for loops was successfully executed.

***

# Exp.3 : Factorial of a Number using Function (Without Return Type, With Arguments)

## Aim:

Find the factorial of a given number using a function without return type but with arguments.

## Algorithm:

1. Get input the size n of the square from the user.
2. Create a function factorial(int n) that calculates the factorial.
3. Use a loop inside the function to compute factorial.
4. Print the factorial from within the function.
5. End the program.

## Program:

```c
#include<stdio.h>
void fact(int num)
{
    int fact=1,i;
    for(i=1;i<=num;i++)
    {
        fact=fact*i;
    }
    printf("Factorial value is: %d",fact);
    
}
int main()
{
    int n;
    scanf("%d",&n);
    fact(n);
    return 0;
}
```

## Output:

<img width="595" height="87" alt="502981810-cf57ce5b-a598-41ea-9480-27f02306ecf9" src="https://github.com/user-attachments/assets/72791bc6-fc20-4412-b72c-76fe8371008e" />

## Result:

Thus, The C program to find the factorial of a given number using a function without return type but with arguments was successfully executed.

***

# Exp.4 : Check Palindrome using For Loop

## Aim: 

Check if the input entered by the user is a palindrome.

## Algorithm:

1. Get input the size n of the square from the user.
2. Store the input in a variable.
3. Use a for loop to compare the characters/digits from start and end.
4. If all characters/digits match, it is a palindrome; else it is not.
5. End the program.

## Program:

```c
#include<stdio.h>
int main()
{
    int num,rem;
    int original;
    int reversed=0;
    scanf("%d",&num);
    original = num;
    for(;num!=0;num /= 10){
        rem=num%10;
        reversed = reversed*10+rem;
        
  }
    if(original==reversed){
        printf("Palindrome Number");
    }
        else
    {
        printf("Not a Palindrome Number");
    }
    return 0;
```

## Output :

<img width="495" height="133" alt="502981972-ce350c0c-3648-48d4-9a4a-6cf52409d323" src="https://github.com/user-attachments/assets/1c28b606-92ca-41a3-b466-e8ea4068f789" />

## Result:

Thus, The C program to check if the input entered by the user is a palindrome was successfully executed.

***

# Exp.5 : Multiplication Table using Do-While Loop

## Aim: 

Print the multiplication table of a user-provided number using a do-while loop.

## Algorithm:

1. Get input the size n of the square from the user.
2. Initialize a counter i = 1.
3. Use a do-while loop to multiply n by i and print the result.
4. Increment i until it reaches 10.
5. End the program.

## Program:

```c
#include <stdio.h>

int main()
{
 int num,i=1;
 scanf("%d", &num);
 do {
     printf("%d ",num*i);
     i++;
    }
    while(i<=num);
    
     
 return 0;

}
```

## Output:

<img width="639" height="139" alt="502982113-453e9fc4-031f-4fb0-ace3-f3170666d1d8" src="https://github.com/user-attachments/assets/74f8216d-be04-427c-a630-19d6d8ea65cc" />

## Result:

Thus, The C program to print the multiplication table of a user-provided number using a do-while loop was successfully executed.
