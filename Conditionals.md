# Python

# Conditional statements

- In a Python program, the if statement is how you perform this sort of decision-making. It allows for conditional execution of a statement or group of statements based on the value of an expression. In its simplest form, it looks like this:
    if <expr>:
       <statement> 
- In the form shown above:
         - <expr> is an expression evaluated in a Boolean context, as discussed in the section on Logical Operators in the Operators and Expressions in Python tutorial
         - <statement> is a valid Python statement, which must be indented. (You will see why very soon.)
- If <expr> is true (evaluates to a value that is “truthy”), then <statement> is executed. If <expr> is false, then <statement> is skipped over and not executed.

- Note that the colon (:) following <expr> is required. Some programming languages require <expr> to be enclosed in parentheses, but Python does not.
         
## Grouping Statements: Indentation and Blocks

- In all the examples shown above, each if <expr>: has been followed by only a single <statement>. There needs to be some way to say “If <expr> is true, do all of the following things.”

- The usual approach taken by most programming languages is to define a syntactic device that groups multiple statements into one compound statement or block. A block is regarded syntactically as a single entity. When it is the target of an if statement, and <expr> is true, then all the statements in the block are executed. If <expr> is false, then none of them are.

- Virtually all programming languages provide the capability to define blocks, but they don’t all provide it in the same way. Let’s see how Python does it.
         
- Python follows a convention known as the off-side rule, a term coined by British computer scientist Peter J. Landin. (The term is taken from the offside law in association football.) Languages that adhere to the off-side rule define blocks by indentation. Python is one of a relatively small set of off-side rule languages.

- Recall from the previous tutorial on Python program structure that indentation has special significance in a Python program. Now you know why: indentation is used to define compound statements or blocks. In a Python program, contiguous statements that are indented to the same level are considered to be part of the same block.
         
- Thus, a compound if statement in Python looks like this:
    if <expr>:
      <statement>
      <statement>
      ...
      <statement>
    <following_statement>
      
 https://files.realpython.com/media/t.78f3bacaa261.png
