# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### NAME: GOKULA PRIYA P                                                                         
### REGISTER NUMBER : 212222040044

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

## Do while
```
def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
```

## while do

```
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
```

## Switch

```
def switch():
    switcher={0:"even",1:"odd"}
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch()

```

## If else

```
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()
```

## for

```
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate()
```

### Output:

## Do while
![stl1a](https://github.com/user-attachments/assets/1828d8ae-c347-4c89-a54e-b4776bd2d18a)


## While do
![stl1b](https://github.com/user-attachments/assets/9fe4feca-5d2a-4feb-9fea-25c0fde87112)


## Switch

![stl1c](https://github.com/user-attachments/assets/b7449049-75b4-4ad7-96eb-9754e3ab44b5)

## If else
  ![stl1d](https://github.com/user-attachments/assets/23e82684-68e4-4a34-b7d7-28fd14bde424)


## for
![stl1e](https://github.com/user-attachments/assets/059fee5a-54e8-4533-b4aa-12bd4a4ae912)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


