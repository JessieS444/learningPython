# The Beginning Pt. 2

Before we get any further, the command to clear the console is "CTRL + L". It is super annoying to have a full console with stuff not relevant.

## Syntax and Errors
- First syntax rule to know: case matters. Capitalizing or leaving a command lowercase will change the command and won't get the result you want.
- Make sure you save the file you are writing your code in. The command is usually "CTRL + S" or "CMD + S".
- If you mess something up, it will give you a traceback, which will tell you the file and line of the error so you can go and fix it.
- Make sure to have both an opening and closing parenthesis. If you forget one it won't know where to begin or where to end.
- Can use either quotation marks or apostraphes to enclose a string, e.g. print("Hello, World") and print('Hello, World') would both work.
  - However, must match beginning and end punctuation otherwise it won't read it.

## Variables
- In python, everything you create is an object and you can label an object so that you can refer to it later in your program.
  - These labels you create are called <ins>variables</ins>. Variables allow you to refer to objects that have been created; they are object references.
- <ins>String Literal</ins>: a sequence of zero or more characters enclosed within single quotation marks. The following are examples of string literals: 'Hello, world!' 'He said, "Take it or leave it."'
- Variable Naming Rules:
  1. Can contain both letters and digits, but must begin with either a letter or an underscore.
  2. Remember that case matters, you can use upper case, but by convention we do not.
  3. They cannot be a Python keyword.
- To name a string literal, you put "variable_name = 'string literal'"
  - This form of naming is the conventional way for Python. It is often referred to as "snake case" (adorable).
 - The `print` function can hold multiple arguments so that it prints the strings with a space in between each one. This is done by separating the arguments with a comma.
  - Example: print("These", "will be", "joined together by spaces")
  - You don't put a variable name in quotation marks when putting multiple arguments together with the print function.
    - For example, `print("Hello,", "first_name")` will cause the python shell to print "Hello, first_name". But if you put `print("Hello," first_name)` it will print "Hello, Ada" (Ada being the string literal with the variable name "first_name").
   
## Input and Coding Style
- <ins>Input</ins>: information gathered from the users of an application.
  - `input` is the command for this (easy).
  - Example: `input("How are you today?")` will prompt the user to answer the question and then write out the answer.
- Variables can include other commands. For example, `current_mood = input("How are you today?   ")` will make the input given to the question equal the current_mood. So if you answer "wonderful" to the question, current_mood = wonderful.
- The following code was made based off of what I've learned so far:

![image](https://github.com/JessieS444/learningPython/assets/157999229/2a7e82d2-4e7b-4fc1-95f9-333da92723d9)

- A variable can be thought of as a storage container. You "store" things under a variable name.
- Keep with the conventions of the coding language that you are using, even if it is not technically necessary. This is called <ins>coding style</ins>. This will help your code be readable to others as well as yourself over time.
