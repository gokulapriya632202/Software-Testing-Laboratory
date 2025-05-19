# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### NAME : GOKULA PRIYA P                                                                            
### REGISTER NUMBER : 212222040044
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:

```
num = input("Enter a number: ")
flag = 0

if num.isnumeric():
    z = int(num)
    if z == 2:
        flag = 1
    elif z > 2:
        for i in range(2, z // 2 + 1):
            if z % i == 0:
                flag = 0
                break
        else:
            flag = 1
    if flag == 1:
        print("Prime Number")
    else:
        print("Not a Prime Number")
else:
    print("Enter a Positive Number")
```

### Output:

![STL3](https://github.com/user-attachments/assets/bb93df8e-0d4f-49ad-9595-31082df65cba)




### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
