# Ex5 Stack Operations
## DATE:22/11/2025
## AIM:
To write a C function to perform push and pop operation of the stack in the infix to postfix conversion.

## Algorithm
1.Initialize top as -1 and declare stack as a character array.

2.To push, increment top and assign the character to stack[top].

3.To pop, check if top is -1 and return -1 if true.

4.If not, return stack[top] and decrement top   

## Program:

Program to find and display the priority of the operator in the given Postfix expression
## Developed by: NARMADHA S
## RegisterNumber:  212223220065

```
char stack[100];
int top = -1;
void push(char x)
{
 stack[++top] = x;
}
char pop()
{
 if(top == -1)
 return -1;
 else
 return stack[top--];
}
```

## Output:

<img width="334" height="159" alt="437310806-abff59db-fc19-4c53-95ec-211eb8490eb5" src="https://github.com/user-attachments/assets/1ff545b0-e359-4579-9b0c-f018cd9af726" />


## Result:
Thus the C program to perform push and pop operation of the stack in the infix to postfix conversion is implemented successfully.
