# Name: Mopuri Ankitha
# Register number:212223040117
# Experiment-4
## ARMSTRONG NUMBER 
# Aim: Write a python program to check the number is Armstrong number or not and inspect for failures. 

# Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

# Program
```

number = int(input("Enter an integer number: "))

if number < 0:
    print(f"{number} is Not an Armstrong Number because negative numbers are not considered.")
else:
    sum = 0
    num = number
    power = len(str(number))  

   
    while num > 0:
        current_digit = num % 10 
        sum += current_digit ** power  
        # num = num / 10  
        num = num // 10  

    if sum == number:
        print(f"{number} is an Armstrong Number because the sum of its digits each raised to the power {power} equals the number itself.")
    else:
        print(f"{number} is Not an Armstrong Number because the sum of its digits each raised to the power {power} ({sum}) does not equal the number itself.")

```

# Output
<img width="1234" height="53" alt="image" src="https://github.com/user-attachments/assets/5088ee0b-129d-45b8-b8ae-654729bcd797" />

<img width="1354" height="68" alt="image" src="https://github.com/user-attachments/assets/b35e5676-24cb-4788-b911-6a9af0c4d4f7" />



# Result

Thus the  program to check the number is Armstrong number or not and inspecting for failures is done successfully. 

