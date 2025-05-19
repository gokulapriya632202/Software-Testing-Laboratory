# Ex.No: 2   Matrix Multiplication 

### NAME: GOKULA PRIYA P                                                                           
### REGISTER NUMBER : 212222040044

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

Algorithm:
1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
### Program:

```
# Input the row and column count for both matrices
r1, c1 = input("Enter row and column count in matrix 1: ").split()
r2, c2 = input("Enter row and column count in matrix 2: ").split()


matrix1 = []
matrix2 = []
result = []


if r1.isnumeric() and c1.isnumeric() and r2.isnumeric() and c2.isnumeric():
    r1 = int(r1)
    r2 = int(r2)
    c1 = int(c1)
    c2 = int(c2)

    
    if c1 != r2:
        print("Matrix multiplication not possible (columns of matrix 1 must equal rows of matrix 2)")
    elif max(r1, c1, r2, c2) > 20 or min(r1, c1, r2, c2) == 0:
        print("Matrix multiplication not possible (size constraint or zero dimension)")
    else:
        
        print("Enter elements for matrix 1:")
        for i in range(r1):
            a = []
            for j in range(c1):
                a.append(int(input(f"Element [{i}][{j}]: ")))
            matrix1.append(a)

       
        print("Enter elements for matrix 2:")
        for i in range(r2):
            a = []
            for j in range(c2):
                a.append(int(input(f"Element [{i}][{j}]: ")))
            matrix2.append(a)

        for i in range(r1):
            result.append([0] * c2)

       
        for i in range(r1):
            for j in range(c2):
                sum = 0
                for k in range(c1):
                    sum += matrix1[i][k] * matrix2[k][j]
                result[i][j] = sum

   
        print("Resultant Matrix after multiplication:")
        for i in range(r1):
            for j in range(c2):
                print(result[i][j], end=" ")
            print()

else:
    print("Enter valid numbers for rows and columns.")

```

### Output:

![STL2](https://github.com/user-attachments/assets/32383f76-7c5a-4988-a4e1-556a0f73b8fa)





### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

