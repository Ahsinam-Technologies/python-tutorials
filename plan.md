**1. Intro to Programming Languages**

* We want to talk to computers and ask them to do something. For that we need programming languages. In the post-AI era, we don't learn about the syntax of the programming languages, but the concepts that appear when you use the language. 

* Question: What is a programming language? How was it made? This should give you the understanding of: scripted languages (they need interpreters) and compiled languages (they need compilers). Pros: compiled ones are faster, interpreted ones are easier to debug. 

* There are many programming languages. All can be classified into 4 types. Touch a bit about programming paradigms: procedural, object-oriented, functional and declarative. All are equally powerful. You can ask computer to do the same thing, but think in 4 different ways. Python is a multi-paradigm language. Give more language examples of each one of them. No need to know everything about paradigms now, you will learn it easy. 

* Any code is composed of literals, identifiers, operators, and keywords. Introduce REPL. And basic code statements. 

**2. Literals**

* Numbers: Integers (counting techniques - bin, oct, hex, dec), Boolean, Floating Point Numbers (also contains inf & nan), and Complex Numbers. 
    * Tell them about Coins in bags distribution problem.
    * Tell them how the size of number representation changes even though the number remains same when the counting base changes. 
    * Introduce the idea of hash value, as the classic hex number. Motivate how Git works & blockchains are formed.
    * For floating-point, tell them about the floating point representation and show how 0.1 + 0.1 + 0.1 - 0.3 is not exact zero. 
    * Final fun fact: Base 60 is the reason for how our clocks work, and why circle has 360 degrees.
* Strings
    * Some operators work with strings (concat & repetition).
    * Sequence operations
    * The idea of immutability vs mutability
    * The idea of type-specific methods
* Lists
    * Basics
    * Sequence operations
    * They are mutable
    * The idea of nesting!
    * Then the type-specific methods
    * Sequence unpacking
* Dictionaries
    * key-value pairs
    * Nesting
    * Type specific methods
* Tuples
    * They are just immutable lists
    * Trick to make single element tuple
    * Parenthesis are optional. That makes the python swapping the easiest.
* Sets
    * Intro
    * Type specific functions
* None
    * This is special value indicating nothing, not even zero. 


Write the following list of keywords on the board. 

| Keywords in Python | | | | | | |
| --- | --- | --- | --- | --- | --- | --- | 
| True | and | if | import | class | try | async |
| False | or | elif | from | self | except | await |
| None | not | for | as | | finally |
| del | is | else | global | | raise |
| | in | break | nonlocal | | assert | 
| | | continue | | | with | 
| | | def | 
| | | return |
| | | pass |
| | | lambda | 
| | | yield | 

**3. Operators**

* ARITHMETIC: + - * / % // **
* RELATIONAL: > < == != >= <=
* LOGICAL: and, or, not. Here, the idea of short-circuiting needs to be covered. 
* BITWISE: | & ^ ~ << >>. Tell them about Josephus Problem.  Computers store date time as integers. Show this demo in Google sheets by converting date to int.  
* ASSIGNMENT: = += -= *= /= %= //= **= &= |= ^= >>= <<=
* IDENTITY: is & is not. They also explain the dynamic typing of python. This also explains about shared references. Copies & repetitions are shallow. 
* MEMBERSHIP: in & not in. 

**4. Control Statements**

* There are 3 control flows that are available in all programming languages: branch, loop, and jump. 
* Branching = if.
    * Q1. While purchasing certain items, a discount of 10% is offered if the quantity purchased is more than 10. If quantity and price per item is entered through keyboard, program should calc the total expenses.
    * Q2. The basic salary of company is 12,000 per month. If the employee is having  experience less than or equal to 4 years, they get the basic salary, 50% of  salary as bonus and 5,000 as yearly expenses. If the experience is more than 4  years, they would get basic salary, 100% of salary as bonus and 6,000 as yearly  expenses. If the number of years of experience is entered through keyboard, write a prog to calc their annual income. 
    * Q3. Write a program to check whether the entered year is leap or not.
    * Q4. Write a prog to determine whether given 3 points by user are  collinear or not. 
   * Q5. Write a prog that determines whether the point is inside, on or outside the circle; where point, centre and radius of circle are entered by user. 
   * Q6. Write a prog to calc the area of triangle, when 3 sides are entered by the user, with the condition that the triangle is valid.
   * Q7. If ages of A, B, C are entered, write a prog to determine the  youngest of 3.
* Looping = for, while, break, continue. 
    * Cover list comprehensions & dict comprehensions. 
    * Q8. Write a prog to check whether the num is prime or not.
    * Q9. Write program to accept an integer & find the sum of its digits.
    * Q10. Write a prog to print Fibonacci series where number of terms is entered by the user.
    * Q11. Write a prog that prints Fibonacci series upto a certain limit, limit being entered by user.
    * Q12. Write a prog to reverse a number and check it is a palindrome or not.
    * Q13. Write a prog to print all primes form 1 to N, where N is entered by the user. Also print the total number of primes in that range.
    * Q14. Write a program to accept a decimal number and convert it to binary and count the number of 1's in the binary number.
    * Q15. Write a prog that converts binary number to its equivalent decimal number.
    * Q16. Write a prog to calculate the sinx series upto the nth term, where x and n would be entered by user. Note: x is in radians.
    * Q17. Write a program to find GCD/HCF and LCM of two integers. 
    * Q18. Write a prog to generate list of pythagorean triplets upto a certain limit, limit being entered by the user.
* Jumping = def, return, pass, lambda
    * Functions don't check the type of the arguments. 
    * Argument passing (pass by value, pass by reference). Return always works as return by reference, never as return by value. 
    * Types of arguments: default, positional, keyword arguments.
    * Varargs
    * One-liner anonymous functions. Helpful when you want to pass a function to the argument. 
    * Generator functions.
        * Iterables & Iterators
        * Generator functions using yield. Useful when you demand values if the sensor is constantly sending you the data.

**5. Scope**

* The idea of scope & the LEGB Rule.
* Built-in Scope
* Global Scope
* Enclosing Scope: traps the value, factory functions
* Taste of functional programming: map, reduce, filter

**6. Modules**

* Difference between modules & scripts. \_\_name__ and \_\_main__. 

THIS IS END OF PART 1 OF PYTHON. 

---

PART 2 covers classes & objects, exception handling, files, packages, static & class methods, inheritance, and decorators.

---