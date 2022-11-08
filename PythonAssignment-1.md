## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Because they are not written in machine-readable language, Python programs need to be processed before machines can run them. Python is an interpreted language. This means that every time a program is run, its interpreter runs through the code and translates it into machine-readable byte code.
high-level means it's easy for humans to understand.
==================================================================================================================================================
Q2. Why is Python called a dynamically typed language?
Python is a dynamically typed programming language, which means you don't need to specify the type of variables or data types like other languages like C/C++. It automatically assigns the data type to the variable at the execution time
==================================================================================================================================================
Q3. List some pros and cons of Python programming language?
There are some more advantages…..
Interactive
Interpreted
Modular
Dynamic
Object-oriented
Portable
High level

Disadvantages Of Python Programming
Poor Memory Efficiency. To make it simple for the developer, Python needs a lot of memory space; this can be a tad problematic if you want to develop apps where you need to optimize memory.
Slow Speed. ...
Database Access. ...
Weak in Mobile Computing. ...
Runtime Errors.
==================================================================================================================================================
Q4. In what all domains can we use Python?
Top 5 tech domains to deploy Python
Web development. Any business must invest in web development. ...
Data science. Python is an excellent tool for creating data-driven solutions. ...
OS development. ...
Scientific programming. ...
Gaming.
==================================================================================================================================================
Q5. What are variable and how can we declare them?
A variable declaration always contains two components: the type of the variable and its name
e.g:
a=1
a_bc=5.0
==================================================================================================================================================
Q6. How can we take an input from the user in Python?
Syntax:
inp = input('STATEMENT')
    
Example:
name = input('What is your name?\n')     
# \n ---> newline  ---> It causes a line break
            
>>> What is your name?
    Ram
>>> print(name)
    Ram 
            
==================================================================================================================================================
Q7. What is the default datatype of the value that has been taken as an input using input() function?
By default, input returns a string. So the name and age will be stored as strings
==================================================================================================================================================
Q8. What is type casting?
Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users
==================================================================================================================================================
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Python provides the two methods that help us to take multiple values or input in one line.

Using split() method
Using List Comprehension
In this tutorial, we will learn how to take multiple inputs in one line using various methods.

Using split() Method
The split() method is useful for getting multiple inputs from users. 

Using List Comprehension
We can also take values and convert them into the list using the map() method along with the split() method.
https://www.javatpoint.com/how-to-take-multiple-input-from-user-in-python
==================================================================================================================================================
Q10. What are keywords?
Keywords are the reserved words in Python. We cannot use a keyword as a variable name, function name or any other identifier.
few of the keywords generally used in the program coding are break, continue, true, false, and, or, not, for, while, def, class, if, else, elif, import, from, except, exec, print, return, yield, lambda, global, etc.
==================================================================================================================================================
Q11. Can we use keywords as a variable? Support your answer with reason.
We cannot use a keyword as a variable name, function name or any other identifier.
==================================================================================================================================================
Q12. What is indentation? What's the use of indentaion in Python?
Python uses indentation to indicate a block of code.
Indentation refers to the spaces at the beginning of a code line.
indentation in code is used for better readability only
==================================================================================================================================================
Q13. How can we throw some output in Python?
The basic way to do output is the print statement. To end the printed line with a newline, add a print statement without any objects. This will print to any object that implements write(), which includes file objects.
==================================================================================================================================================
Q14. What are operators in Python?
1 Numerical or Arithmetic 2. Relational or comparision 3. Assignment 4. Logical or Boolean .
==================================================================================================================================================
Q15. What is difference between / and // operators?
'/' is the division operator. '//' is the floor division operator
==================================================================================================================================================
Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

print("iNeuroniNeuroniNeuroniNeuron")
==================================================================================================================================================
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
# Python program to check if the input number is odd or even.
# A number is even if division by 2 gives a remainder of 0.
# If the remainder is 1, it is an odd number.

num = int(input("Enter a number: "))
if (num % 2) == 0:
   print("{0} is Even".format(num))
else:
   print("{0} is Odd".format(num)
==================================================================================================================================================
Q18. What are boolean operator?
The logical operators and, or and not are also referred to as boolean operators. While and as well as or operator needs two operands, which may evaluate to true or false, not operator needs one operand evaluating to true or false
==================================================================================================================================================
Q19. What will the output of the following?
```
1 or 0 => 1

0 and 0 => 0

True and False and True => False

1 or 0 or 0 =>1
==================================================================================================================================================

Q20. What are conditional statements in Python?
A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program. Python has 3 key Conditional Statements that you should know: if statement. if-else statement..........

==================================================================================================================================================
Q21. What is use of 'if', 'elif' and 'else' keywords?
if…elif…else are conditional statements that provide you with the decision making that is required when you want to execute code based on a particular condition.

The if…elif…else statement used in Python helps automate that decision making process.
==================================================================================================================================================
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
# input age
age=int(input("enter age"))

# condition to check voting eligibility
if(age >=18):
    print("I can vote")
else:
    print("I can't vote")
==================================================================================================================================================
Q23. Write a code that displays the sum of all the even numbers from the given list.
# list of numbers``
numbers = [12, 75, 150, 180, 145, 525, 50]

# Python program to print Even Numbers in a List

# iterating each number in list
for i in numbers:
    if i%2 == 0:
        print(i, end=" ")

==================================================================================================================================================
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
# Python program to find the largest number among the three input numbers

# values of num1, num2 and num3
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
num3 = float(input("Enter third number: "))

if (num1 > num2) and (num1 > num3):
    print(num1)
elif (num2 > num1) and (num2 > num3):
    print(num2)
else:
    print(num3)
==================================================================================================================================================
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

list = [12, 75, 150, 180, 145, 525, 50]
i = 0
length = len(list)

while i < length:
    if list[i] > 500:
        pass
    
    elif list[i] > 150:
        pass
    
    elif list[i] % 5 == 0:
        print(list[i])
    
    i+=1
==================================================================================================================================================
# Python Program to Check Number is Divisible by 5 and 11

# number = int(input(" Please Enter any Positive Integer : "))

# if((number % 5 == 0) and (number % 11 == 0)):
#     print("Given Number {0} is Divisible by 5 and 11".format(number))
# else:
#     print("Given Number {0} is Not Divisible by 5 and 11".format(number))
	