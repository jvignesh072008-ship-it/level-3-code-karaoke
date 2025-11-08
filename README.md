
<img width="5400" height="2383" alt="Code Karaoke-min" src="https://github.com/user-attachments/assets/cf9296ba-8410-4592-8df0-bac4afd7fdba" />

# Level-3-code-karaoke
Level 3 questions for code karaoke event, there are 2 scenario based  fork and upload in git hub 

# 1st Question :
1.You are building a billing system for a small café.
The café sells:
•	Coffee → ₹60
•	Sandwich → ₹120
•	Cake → ₹80
You need to write a Python program that:
1.	Asks the user what they want to order.
2.	Asks how many of that item they want.
3.	Calculates and displays the total bill.

# Code:
```
prices = {"coffee": 60, "sandwich": 120, "cake": 80}

item = input("What would you like to order (coffee/sandwich/cake)? ").lower()
quantity = int(input("How many? "))

if item in prices:
    total = prices[item] * quantity
    print("Your total bill is ₹", total)
else:
    print("Sorry, that item is not on the menu.")
```

# OUTPUT:
<img width="631" height="77" alt="Screenshot 2025-11-08 113435" src="https://github.com/user-attachments/assets/a1e203ae-6638-4695-be79-27c3e7c61b29" />



# Question 2:
2. You’re designing a program for a college portal that evaluates a student’s final grade based on their marks in 3 subjects.
Rules:
•	If the average is 90 or above → Grade A+
•	If the average is 75–89 → Grade A
•	If the average is 60–74 → Grade B
•	If the average is 40–59 → Grade C
•	Below 40 → Fail
The program should:
1.	Take marks for 3 subjects from the user
2.	Calculate the average
3.	Print the average and the grade
________________________________________
# Example Input / Output:
Enter mark for Subject 1: 85
Enter mark for Subject 2: 78
Enter mark for Subject 3: 90
Average = 84.33
Grade = A





# Code:
```
m1=int(input("mark1"))
m2=int(input("mark2"))
m3=int(input("mark3"))
a=(m1+m2+m3)/3
if(a>=90):
    print("A+")
if(a>75 and a<89):
            print("A")
if(a>60 and a<74):
            print("B")
if(a>42 and a<59):
            print("C")
if(a<40):
            print("fail")
```

# OUTPUT:
<img width="176" height="110" alt="image" src="https://github.com/user-attachments/assets/ac30d224-9eb9-4876-a700-be696f0d821a" />


