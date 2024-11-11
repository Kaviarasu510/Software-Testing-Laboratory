# Ex.No: 7 Sorting.

### DATE:                                                                  
### REGISTER NUMBER :  212222040075
### AIM: 
Write a python program for sorting and inspect for failures.

### Algorithm:
1. Start
2. Get an input from the user by prompting
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2.
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome.
7. Stop the program

### Program:
```
n = int(input("Enter the number of elements: "))
arr = []
try:
    for i in range(n):
        a = float(input("Enter the element: "))
        arr.append(a)
    for i in range(n):
        for j in range(i + 1, n):  
            if arr[i] > arr[j]:    
                temp = arr[i]
                arr[i] = arr[j]
                arr[j] = temp
    print("The array after sorting: ")
    for i in range(n):
        print(arr[i], end=' ')
except ValueError:
    print("Enter a valid number")

```

### Output:
![Screenshot 2024-11-11 194937](https://github.com/user-attachments/assets/78e2ab11-85ee-4f9f-bba9-a9e9ff961fe8)


### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully
