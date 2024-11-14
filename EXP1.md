# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 16/8/24                                                                         
### REGISTER NUMBER : 212222040046

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
a) do..while
```
def display(): 
    start = input("Enter a positive value for START: ") 
    end = input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start = int(start) 
            end = int(end) 
            print(start, end=' ') 
            if start < end: 
                start += 1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.")

display()
```
b) while..do
```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric(): 
    start = int(start) 
    end = int(end) 
    while start < end: 
        print(start) 
        start += 1 
else: 
    print("Enter a valid positive number.")
```
c) if..else
```
def compare(): 
    a = input("Enter a value for A: ") 
    b = input("Enter a value for B: ") 
    try: 
        a = int(a) 
        b = int(b) 
        if a > b: 
            print("A is greater than B") 
        elif a < b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")

compare()
```
d)switch
```
def switch(): 
    switcher = { 
        0: "even", 
        1: "odd" 
    } 
    n = input('Enter a value for N: ') 
    try: 
        n = int(n) 
        print(switcher[n % 2]) 
    except ValueError: 
        print("Enter a valid number.")

switch()
```
e) for
```
def iterate(): 
    string = input("Enter a string: ") 
    for i in string: 
        print(ord(i), end=" ") 

iterate()
```
### Output:
i)DO...WHILE
![image](https://github.com/user-attachments/assets/34231620-cd07-41b7-a4e8-d16aaacc2da4)
![image](https://github.com/user-attachments/assets/e240d6e6-727b-4746-8fde-3599c0f29222)
ii)WHILE...DO
![image](https://github.com/user-attachments/assets/41d03de3-7b7f-4507-aced-e80d3e8b8512)
![image](https://github.com/user-attachments/assets/0cfea109-c051-48ef-9e66-d1dba335563d)
iii) SWITCH
![image](https://github.com/user-attachments/assets/70f0baa4-9272-43d1-86a3-02dd02d94895)
iv)IF ELSE
![image](https://github.com/user-attachments/assets/73450c00-1bee-4b2a-a672-9b23499bc616)
v) FOR
![image](https://github.com/user-attachments/assets/939ad955-780c-44b5-b986-a55eb968dcd6)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


