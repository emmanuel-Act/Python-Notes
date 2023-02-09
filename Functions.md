# Python

# Function

- Python Functions is a block of statements that return the specific task.

- The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again. 

## Creating a Python Function
- We can create a  Python function     using the def keyword.
- Example:
      def fun(): <br/>
      print("Welcome to GFG")  <br/>
      
## Calling a  Python Function
- After creating a function we can call it by using the name of the function followed by parenthesis containing parameters of that particular function.

###Defining and calling a function with parameters:
- If you have experience in C/C++ or Java then you must be thinking about the return type of the function and data type of arguments. That is possible in Python as well (specifically for Python 3.5 and above).

## Arguments of a Python Function
- Arguments are the values passed inside the parenthesis of the function. A function can have any number of arguments separated by a comma.
- In this example, we will create a simple function to check whether the number passed as an argument to the function is even or odd.

## Types of Arguments
- Python supports various types of arguments that can be passed at the time of the function call. Let’s discuss each type in detail.

### Default arguments 
- A default argument is a parameter that assumes a default value if a value is not provided in the function call for that argument. The following example illustrates Default arguments. 
- Like C++ default arguments, any number of arguments in a function can have a default value. But once we have a default argument, all the arguments to its right must also have default values.

### Keyword arguments

- The idea is to allow the caller to specify the argument name with values so that caller does not need to remember the order of parameters.

### Variable-length arguments
- In Python, we can pass a variable number of arguments to a function using special symbols. There are two special symbols:
        - *args (Non-Keyword Arguments)
        - **kwargs (Keyword Arguments)
