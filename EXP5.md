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
def binary_search(arr, x): 
    low = 0 
    high = len(arr) - 1
    while low <= high: 
        mid = (high + low) // 2 
        if arr[mid] < x: 
            low = mid + 1
        elif arr[mid] > x: 
            high = mid - 1
        else: 
            return mid
    return -1  
arr = [2, 3, 4, 10, 40]
x = input("Enter the element to be searched: ")
try: 
    x = int(x)  
    result = binary_search(arr, x)
    if result != -1: 
        print("Element is present at index", result)
    else: 
        print("Element is not present in array")
except ValueError: 
    print("Enter a valid integer input!")

```

### Output:

![Armstrong Number (1)](https://github.com/user-attachments/assets/7b992fd3-7fe0-4c63-9b81-21a1a97ab010)


### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.

