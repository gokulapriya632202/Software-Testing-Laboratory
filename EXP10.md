# Ex.No: 10  Pytest program for Sum of digits

### NAME : GOKULA PRIYA P                                                                            
### REGISTER NUMBER : 212222040044

### AIM: 
To write a python program for Fibonacci Series and generate test cases using Pytest. 

### Algorithm:

1. Write the python program for Fibonacci Series. 
2. Make sure that function name should be “def test_*():” and the line to be tested 
should have assert keyword at the beginning. 
3. Write some test cases for to be tested and save it as “test_fib.py”. 
4. Open command prompt and change the directory to where pytest and program is 
saved and type “pytest test_fib.py” and run it. 
5. Stop the program.

### Program:

```
def fibR(n): 
if n==1 or n==2: 
return 1 
return fibR(n-1)+fibR(n-2) 
def test_fib_1_equals_1(): 
assert fibR(1) == 1 
def test_fib_2_equals_1(): 
assert fibR(2) == 1 
def test_fib_6_equals_8(): 
assert fibR(6) == 7
```

### Output:
![STL2](https://github.com/user-attachments/assets/dbdabc32-4a24-49c3-abb0-75431712a62d)



### Result:
Thus, the python program for Fibonacci Series is tested using pytest and executed and output is verified successfully.


