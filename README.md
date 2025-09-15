# Experiment-3
## PRIME NUMBER OR NOT

# Aim: Write a python program to check the number is prime or not and inspect for failures. 

# Algorithm
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
 - If the number is divisible by the current iteration value, return "Not Prime".
6. If the number is not divisible by any value from 2 to the square root, return "Prime".
7. Stop the program. 

## Program
```python
num=int(input("Enter a numer :"))
if num<=1:
    print(num,"is not a prime number")
else:
    for i in range(2,int(num**0.5)+1):
        if num%i==0:
            print(num,"is not a prime number")
            break
    else:
        print(num,"is a prime number")
```

## Output
<img width="1500" height="193" alt="image" src="https://github.com/user-attachments/assets/3c942ea5-f14c-4864-81f4-3a4ac20b9ace" />


## Result
Thus, the python program to find if a number is prime or not has been successfully executed.
