# Python

# Variables

- Python Variable is containers which store values. Python is not “statically typed”. We do not need to declare variables before using them or declare their type. A variable is created the moment we first assign a value to it. A Python variable is a name given to a memory location. It is the basic unit of storage in a program.

## Rules for creating variables in Python
  - A variable name must start with a letter or the underscore character.
  - A variable name cannot start with a number.
  - A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ ).
  - Variable names are case-sensitive (name, Name and NAME are three different variables).
  - The reserved words(keywords) cannot be used naming the variable.
## Variable Assignment
- Think of a variable as a name attached to a particular object. In Python, variables need not be declared or defined in advance, as is the case in many other programming languages. T
- o create a variable, you just assign it a value and then start using it. Assignment is done with a single equals sign (=).

## Variable Types in Python
- In many programming languages, variables are statically typed. That means a variable is initially declared to have a specific data type, and any value assigned to it during its lifetime must always have that type.

- Variables in Python are not subject to this restriction. In Python, a variable may be assigned a value of one type and then later re-assigned a value of a different type.

## Object References
- What is actually happening when you make a variable assignment? This is an important question in Python, because the answer differs somewhat from what you’d find in many other programming languages.

- Python is a highly object-oriented language. In fact, virtually every item of data in a Python program is an object of a specific type or class. 

## Object Identity
- In Python, every object that is created is given a number that uniquely identifies it. It is guaranteed that no two objects will have the same identifier during any period in which their lifetimes overlap. Once an object’s reference count drops to zero and it is garbage collected, then its identifying number becomes available and may be used again.

- The built-in Python function id() returns an object’s integer identifier. Using the id() function, you can verify that two variables indeed point to the same object.

## Variable Names
- The examples you have seen so far have used short, terse variable names like m and n. But variable names can be more verbose. In fact, it is usually beneficial if they are because it makes the purpose of the variable more evident at first glance.

- Officially, variable names in Python can be any length and can consist of uppercase and lowercase letters (A-Z, a-z), digits (0-9), and the underscore character (_). An additional restriction is that, although a variable name can contain digits, the first character of a variable name cannot be a digit.

- The most commonly used methods of constructing a multi-word variable name are the last three examples:

  - Camel Case: Second and subsequent words are capitalized, to make word boundaries easier to see. (Presumably, it struck someone at some point that the capital letters strewn throughout the variable name vaguely resemble camel humps.)
    - Example: numberOfCollegeGraduates
  - Pascal Case: Identical to Camel Case, except the first word is also capitalized.
    - Example: NumberOfCollegeGraduates
  - Snake Case: Words are separated by underscores.
    - Example: number_of_college_graduates
