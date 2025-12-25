# Looping(Patterns)-pyramid of numbers

## 🎯 Aim

Write a Python Program to print pyramid pattern of numbers .Get the input for the number of rows 

For example:

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5


## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop i from 1 to the number of rows+1.
4. loop j another one from 1 to i+1
5. print j
6. print()
7. End the program.


## 🧪 Program

n=int(input())

for i in range(1,n+1):
    
    for j in range (1,i+1):
        
        print(j, end=" ")
    
    print()

## Sample Output

<img width="533" height="483" alt="image" src="https://github.com/user-attachments/assets/1be6e50d-2a28-4ad0-abdb-f54d2b28d069" />


## Result
Thus, the program is been simulated sucessfully

