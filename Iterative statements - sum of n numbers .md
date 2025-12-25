# Iterative statements - sum of n numbers 

## 🎯 Aim
Python Program to print the sum of N  numbers which is divisible by 3.

## 🧠 Algorithm
1. get an integer input and assign it as 'a'
2. assign s=0
3. create a for loop ranging from 1 to a+1
4. write a if statement inside the for loop loop to find the sum of odd numbers
5. print the sum
6. end of program 

## 🧾 Program

a=int(input())

s=0

for i in range (1,a+1):
    
    if i%3==0:
        
        s += i

print(f"Sum is: {s}")
        

## Output

<img width="417" height="148" alt="image" src="https://github.com/user-attachments/assets/86eadd88-350e-454d-8add-657329230634" />


## Result
Thus, the program has simulated sucessfully
