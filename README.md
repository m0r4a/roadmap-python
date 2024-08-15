# Roadmap.sh - Python 

## Introduction

This repository contains my progress in Python according to the roadmap provided by [Roadmap.sh](https://roadmap.sh/python).

Each section of the roadmap will have two sections: `Information` and `Example`.

The `Information` section will contain the information and resources that roadmap.sh provides for that section.

The `Example` section will contain the code that I have written to demonstrate my understanding of the concepts in that section.

## Purpose

There are two main purposes for this repository:

1. To demostrate that I didn't just clicked through the roadmap, but actually learned the concepts.

2. To provide a resource for others who are learning Python and want to see examples of the concepts in action.

## Table of Contents

- [Learn the Basics](#learn-the-basics)
    - [Basic Syntax](#basic-syntax)
    - [Variables and Data Types](#variables-and-data-types)
    - [Conditionals](#conditionals)
    - [Loops](#loops)

## Learn the Basics

### Basic Syntax

[Go back to the Table of Contents](#table-of-contents)

#### Information

- [Article] [W3Schools - Python](https://www.w3schools.com/python/)
- [Article] [Python Basics](https://www.tutorialspoint.com/python/python_basic_syntax.htm)
- [Article] [Learn X in Y Minutes / Python](https://learnxinyminutes.com/docs/python/)
- [Article] [Python for Beginners - Learn Python in 1 Hour](https://www.youtube.com/watch?v=kqtD5dpn9C8)

#### Example

The best code example to show the basic syntax of Python would be to just copy the "Learn X in Y Minutes" so please, just go and check it out.

### Variables and Data Types

[Go back to the Table of Contents](#table-of-contents)

#### Information

Variables are used to store information to be referenced and manipulated in a computer program. They also provide a way of labeling data with a descriptive name, so our programs can be understood more clearly by the reader and ourselves. It is helpful to think of variables as containers that hold information. Their sole purpose is to label and store data in memory. This data can then be used throughout your program.

Visit the following resources to learn more:

- [Article] [Variables in Python](https://realpython.com/python-variables/)
- [Article] [W3Schools - Python Variables](https://www.w3schools.com/python/python_variables.asp)
- [Article] [Python Data Types](https://www.w3schools.com/python/python_datatypes.asp)
- [Article] [Basic Data Types in Python](https://realpython.com/python-data-types/)
- [Article] [Python for Beginners: Data Types](https://thenewstack.io/python-for-beginners-data-types/)
- [Video] [Python Variables - Python Tutorial for Beginners with Examples | Mosh](https://www.youtube.com/watch?v=cQT33yu9pY8)

#### Example

```python
# Declare a variable
number_of_books = 10

# Declare a variable with the type: str (string)
book_title = "Harry Potter and the Philosopher's Stone"

# Declare a variable with the type: int
book_price = 20

# Declare a variable with the type: float
book_rating = 4.5

# Declare a variable with the type: bool (boolean)
is_best_seller = True

# Declare a variable with the type: list
main_characters = ["Harry", "Hermione", "Ron"]

# Declare a variable with the type: tuple
charecters_ages = (11, 12, 11)
```

### Conditionals

[Go back to the Table of Contents](#table-of-contents)

#### Information

Conditional Statements in Python perform different actions depending on whether a specific condition evaluates to true or false. Conditional Statements are handled by IF-ELIF-ELSE statements and MATCH-CASE statements in Python.

Visit the following resources to learn more:

- [Article] [Python Conditional Statements: IF…Else, ELIF & Switch Case](https://www.guru99.com/if-loop-python-conditional-structures.html)
- [Article] [Conditional Statements in Python](https://realpython.com/python-conditional-statements/)
- [Article] [How to use a match statement in Python](https://learnpython.com/blog/python-match-case-statement/)
- [Article] [W3Schools - Python Conditions and If statements](https://www.w3schools.com/python/python_conditions.asp)

#### Example

```python
# Declare a variable
wizard = "Harry"
house = "Gryffindor"

# If, elif, else statement
if wizard == "Harry":
    print("You are Harry Potter!")
elif wizard == "Ron":
    print("You are Ron Weasley!")
else:
    print("You are not Harry Potter or in Gryffindor.")


# Match-case statement
match house:
    case "Gryffindor":
        print("You are in Gryffindor!")
    case "Hufflepuff":
        print("You are in Hufflepuff!")
    case "Ravenclaw":
        print("You are in Ravenclaw!")
    case "Slytherin":
        print("You are in Slytherin!")
    case _:
        print("You are not in any house.")
```

**Output:**

```
You are Harry Potter!
You are in Gryffindor!
```

### Loops

[Go back to the Table of Contents](#table-of-contents)

#### Information

Loops are used to execute a block of code repeatedly.

Visit the following resources to learn more:

- [Article] [Loops in Python](https://www.geeksforgeeks.org/loops-in-python/)

#### Example

```python
# For loop incrementing by 1
for i in range(5):
    print(i)


# For loop incrementing by 2
for i in range(0, 5, 2):
    print(i)


# For loop decrementing by 1
for i in range(5, 0, -1):
    print(i)


# While loop
i = 0
while i < 5:
    print(i)
    i += 1


# While loop with break statement
while True:
    var = input("Guess the number between 1 and 3: ")
    if var == "3":
        print("You guessed the correct number!")
        break
    else:
        print("Try again!")
```

**Output:**

```
# For loop incrementing by 1

0
1
2
3
4

# For loop incrementing by 2

0
2
4

# For loop decrementing by 1

5
4
3
2
1

# While loop

0
1
2
3
4

# While loop with break statement

Guess the number between 1 and 3: 1
Try again!
Guess the number between 1 and 3: 3
You guessed the correct number!
```

