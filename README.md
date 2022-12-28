# Python_Assignment-1
Basics python Assignment 

1.	Why do we call Python as a general purpose and high-level programming language?
ANS: Python is a computer language it is used to build a website, software, automate some tasks even we can create some interesting analysis using python, in general it can be used to create a variety of different programs and it is specialized for any specific problems. Python can also called as High Level Language because it is an interpreted language.
     

2.	Why Python is called a dynamically typed language?
ANS: In general a python is a dynamically typed language, in python we no need to declare the type of variable while assigning a value to a variable but in other languages like C, C++, Java there is a strict declaration of variable before assigning the value to them. 

3.	List some pros and cons of Python programming language?
ANS:
PROS:
1.	It is a beginner friendly 
2.	Python is a large community
3.	It is more flexible and extensible 
4.	Python is a designed for highly scalable
 
CONS:
1.	Python having issues with design
2.	Python is slower than complied language 
3.	Python needs high memory consumption 
4.	Python language is a dynamically typed language 

4. In what all domains can we use Python?
ANS: Python language can used for programming language for domains such as artificial intelligence, machine learning and deep learning, Model building, Deployment, Web Application.

5. What are variable and how can we declare them?
ANS: In python variables are just a name of variable which we are assigning some values in that variables. In python programming language variables are starts with ABC, _ABC123, AB_CD .

6. How can we take an input from the user in Python?
ANS: We can take the input 
abcd= input("Enter username:")
print("Username is: " + abcd)

output: 
Enter username: gomathi
Username is gomathi 

7. What is the default datatype of the value that has been taken as an input using input () function?
ANS:  in python we use input() function to take the input from the user whatever you enter as input , the input function it converts into the string as a default suppose if we enter the integer values in the input function it takes as a string datatype only.

8. What is type casting?
ANS: Type Casting: typecasting it converting one data type into another is known as type casting or, type-conversion. For example, if you want to store a 'long' value into a simple integer then you can type cast 'long' to 'int'. You can convert the values from one type to another.


9. Can we take more than one input from the user using single input () function? If yes, how? If no, why?
ANS: NO (In input function we can get only one input from the user)

10. What are keywords?
ANS: Every programming language has special reserved words, or keywords, that have specific meanings and restrictions around how they should be used. Python is no different. Python keywords are the fundamental building blocks of any Python program.
	Type of Keywords:  True, False, as, def, from, if, elif, and etc  

11. Can we use keywords as a variable? Support your answer with reason.
ANS: We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language. All the keywords except True, False and none are in lowercase and they must be written as they are. 

12. What is indentation? What's the use of indentaion in Python?
ANS: Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.

13. How can we throw some output in Python?
ANS: In Python we can choose to throw an exception if a condition occurs. To throw an exception, use the raise keyword.

14. What are operators in Python?
In Python, there are seven different types of operators: 
•	Arithmetic operators, 
•	Assignment operators, 
•	Comparison operators, 
•	Logical operators, 
•	Boolean operators

15. What is difference between / and // operators?
ANS:  
/ = FLOAT DIVISION 
// = INTEGER DIVISION
They are arithmetic operators, logical operators, assignment operators, etc.
'/' and '//' belong to the arithmetic operators.
'/' is used for the normal division of two numbers.
'//' is used to obtain the smallest integer nearest to the quotient obtained by dividing two numbers.
EXAMPLE: 
a = 19
b = 4
Print (a // b) #This prints output as 4
Print (a / b) #This prints output as 4.75
So, if the quotient obtained by dividing two numbers is not an integer, then operators '/' and '//' will return different answers.

16. Write a code that gives following as an output.
INeuroniNeuroniNeuroniNeuron
Ans:
a = "ineueron" *4
print(a)

17. Write a code to take a number as an input from the user and check if the number is odd or even.
ANS:
num = int(input("enter the number:"))

if (num % 2) ==0:
    print("The number is even")
else:
    print("The number is old")

18. What are boolean operator?
ANS: Boolean operator it return the expression as True OR False keywords in console page A Boolean variable is a variable that can be either True or False

19. What will the output of the following?
1 or 0 = 1

0 and 0 = 0

True and False and True = False

1 or 0 or 0 = 1

20. What are conditional statements in Python?
  ANS: There are 4 conditional statement in python
1.	If statement
2.	If-else statement
3.	Nested if statement
4.	If-elif-else statement.
21. What is use of 'if', 'elif' and 'else' keywords?
•	If statement: 
1.	The if statement is a conditional statement in python, that is used to determine whether a block of code will be executed or not.
2.	Meaning if the program finds the condition defined in the if statement to be true, it will go ahead and execute the code block inside the if statement.

•	Elif statement:
1.	The elif statement is used to check for multiple conditions and execute the code block within if any of the conditions evaluate to be true.
2.	The elif statement is similar to the else statement in the context that it is optional but unlike the else statement, there can be multiple elif statements in a code block following an if statement.
•	Else statement:
1.	It is used to execute both the true part and the false part of a given condition. If the condition is true, the if block code is executed and if the condition is false, the else block code is executed.

22. .Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans: 
age = int(input("Enter the age of the person:"))

if age>=18:
    print("I can vote")
elif age<18:
    print("I can't vote")

23. Write a code that displays the sum of all the even numbers from the given list.
numbers = [12, 75, 150, 180, 145, 525, 50]
def solve(nums):
   return sum([i for i in nums if i % 2 == 0])
nums =  [12, 75, 150, 180, 145, 525, 50]
print(solve(nums))

24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ANS:
num1 = int(input("Enter the num1 :"))
num2 = int(input("Enter the num2 :"))
num3 = int(input("Enter the num3 :"))

if num1 > num2 and num1 > num3:
    greater = num1
if num2 >num1 and num2 > num3:
    greater = num2
if num3> num1 and num3>num2:
    greater = num3
print(greater,"is the largest number")

25. Write a program to display only those numbers from a list that satisfy the following conditions

• The number must be divisible by five

• If the number is greater than 150, then skip it and move to the next number

• If the number is greater than 500, then stop the loop
numbers = [12, 75, 150, 180, 145, 525, 50]
ANS:
a= [12, 75, 150, 180, 145, 525, 50]

b = []

for i in a:
    if i > 150:
        if i < 500:
            break       
    if i % 5 ==0:
        b.append(i)
print(b)


