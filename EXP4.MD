# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE:                                                                            
### REGISTER NUMBER : 
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:
```
x = input("Enter the input: ") 
if x.isnumeric(): 
    x = int(x) 
    temp = x 
    cube = 0; 
    while(temp>0): 
        digit = temp%10 
        cube = cube + (digit**3) 
        temp//=10 
    if(cube == x): 
        print("Armstrong Number") 
    else: 
        print("Not Armstrong Number") 
else: 
    print("Enter a Positive Integer.")
```

### Output:

```
Enter the Input: 143 
Armstrong Number 
Test Case: Pass 

Enter the Input: 25 
Not Armstrong Number 
Test Case: Pass 

Enter the Input: 
Enter a Positive Integer. 
Test Case: Fail 

Enter the Input: String 
Enter a Positive Integer. 
Test Case: Fail 

Enter the Input: A 
Enter a Positive Integer. 
Test Case: Fail 

Enter the Input: !@# 
Enter a Positive Integer. 
Test Case: Fail 

Enter the Input: -10 
Enter a Positive Integer. 
Test Case: Fail 

Enter the Input: 0 
Not Armstrong Number 
Test Case: Pass 

Enter the Input: 22/7 
Enter a Positive Integer. 
Test Case: Fail 

Enter the Input: 1 
Armstrong Number 
Test Case: Pass 

```

### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


