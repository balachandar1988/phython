## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Ans: Python is an object-oriented, high-level programming language. Object-oriented means this language is based around objects rather than functions, and high-level means it's easy for humans to understand.We dont need to 

Q2. Why is Python called a dynamically typed language?

Ans: Python is called a dynamically typed language since the type of the variable defined in program is determined only during runtime. Python interpreter does type checking only as code runs, and the type of a variable is allowed to change over its lifetime.

Q3. List some pros and cons of Python programming language?

Ans :
Pros
Beginner-friendly
Large Community	
Flexible and Extensible	
Extensive Libraries
Embeddable	
Highly Scalable	
Machine Learning algorithm integerated
Portable, it can be run on any other platform			
Cons
Issues with design
Slower than compiled languages
Security
Work Environment
High memory consumption
Dynamically-typed language
Complex multithreading
Garbage collection leads to potential memory losses

Q4. In what all domains can we use Python?

Ans: Web development, Gaming, artificial intelligence, machine learning and deep learning,Data science.

Q5. What are variable and how can we declare them?

Ans Variables are containers to store data. Python has no command for declaring a variable.

Q6. How can we take an input from the user in Python?

Ans: input() method.
name=input("enter username:")
print(name)

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans: Python input() function is used to take user input. By default, it returns the user input in form of a string.

Q8. What is type casting?

Ans: Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans: Yes, Using split() method
Using List Comprehension

Q10. What are keywords?

Ans: Keywords are  special reserved words that have specific meanings and purposes and can’t be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans: No we cant use keywords as varaiable. SyntaxError will occur if we use.

Q12. What is indentation? What's the use of indentaion in Python?

Ans:Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
 Ans: Can raise exception for handling

Q14. What are operators in Python?

Ans: Operators are used to perform operations on variables and values. Various operators:
Arithmetic operators
Assignment operators
Comparison operators
Logical operators
Identity operators
Membership operators
Bitwise operators

Q15. What is difference between / and // operators?

Ans:  The first one is Float Division("/") and the second is Integer Division("//") or Floor Division.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

n=0
x="iNeuron"
y=""

while(n<4):
    y=x+y
    n=n+1
print(y)
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans
num=int(input("Enter Number:"))


if((num % 2)==0):
    print("Number",num, "is Even")

else:
    print("Number", num, " is odd")

Q18. What are boolean operator?

Ans: True or False is boolean operator

Q19. What will the output of the following?
```
Ans
1 or 0  --> 1

0 and 0 -->

True and False and True -->False

1 or 0 or 0 --> 1
```

Q20. What are conditional statements in Python?

Ans: 
Equals: a == b.
Not Equals: a != b.
Less than: a < b.
Less than or equal to: a <= b.
Greater than: a > b.
Greater than or equal to: a >= b.

Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans: It allows us to check for multiple expressions.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans:
age=int(input("Enter your age:"))


if(age> 18):
    print("I can vote")

else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans:
int_list =[12, 75, 150, 180, 145, 525, 50]
list_sum = 0

for num in int_list:
    list_sum = list_sum + num
print(list_sum)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

num1,num2,num3 = input("Enter three numbers:").split()


if (num1 >= num2) and (num1 >= num3):
   print("number",num1,"is largest")
elif (num2 >= num1) and (num2 >= num3):
   print("number",num2, "is largest")
else:
   print("number",num3,"is largest")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]


Ans:

int_list =[12, 75, 150, 180, 145, 525, 50]
list_sum = 0

for num in int_list:
    if (num%5 ==0):
        list_sum = num
    elif (num>150):
        continue
    elif (num>500):
        break

    

print(list_sum)
```