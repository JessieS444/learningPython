# Beginning Python Lessons through Treehouse

## Welcome, Running Scripts, the Python Shell, and REPL

### Welcome:
- Python is a general purpose language, so it can be used to build just about anything.
- Who uses python and for what?
    - US Government uses it for statistical analysis and data visualization
    - Spotify, Evernote, OkCupid use it for personalized recommendations and artificial intelligence-based tasks.
    - Disney, Pixar, Lucasfilm, and others use python to provide more realistic effects in their movies.
    - YouTube, Instagram, Reddit, Pinterest, and the Onion use python.
    - Python can be used for face and speech recognition.
- Teacher's notes are attached to each video in Treehouse.


### Running Scripts:
- Text editors allow us space to write and edit code. GNU nano is a text editor. You write the code in a file.
- Different colors in code is called "syntax highlighting." Syntax is the rules of the language (just like in non-coding languages).
- <ins>Script:</ins> a program or sequence of instructions that is interpreted or carried out by another program rather than by the computer processor. (according to techtarget.com)
    - <ins>Script:</ins> The file we are writing that the Python interpreter will use. (according to Treehouse)
    - Python programs are commonly called scripts. (according to realpython.com)
- <ins>String:</ins> a string is a sequence of characters encolsed between the quotation marks. Example: "Hello, World." (according to emory.edu)
- After writing code in a file, it is passed to a Python Interpreter, which reads it line by line and interpret the meaning from the written script. Then, it will perform the actions in the code or evaluate it.
- <ins>Interpreter:</ins> The program that will read and execute our script.
- <ins>Console:</ins> also known as a command prompt (Windows OS), powershell (Windows OS), terminal (Mac OS). A tool that sends low level commands to your Operating System (macOS / Windows / Linux).

![image](https://github.com/JessieS444/learningPython/assets/157999229/3b1dc688-7843-4c6b-9b81-711958021abf)

- The above is the command prompt (aka cmd or cmd.exe) for the Treehouse workspace. The tilde (~) means that you're in your home directory and the slash (/) means that you're in that subfolder/subdirectory of the named workspace (in this case, that is treehouse). The command prompt (command line?) is where you can send commands to your operating system.
    - Directories are like folders in most operating systems.
- `ls` command: short for "list," this command lists directories and files in the OS.'

- We told the Python Interpreter to run our script by typing `python hello.py`. This ran the script in the hello.py file, which was `print("Hello, World")`. So, what appeared was "Hello, World":

![image](https://github.com/JessieS444/learningPython/assets/157999229/8e26d5a5-806c-4010-89e1-15183862d4cc)


- `python` is the command that brings up the python interpreter.

### The Python Shell:
- Can use the interpreter to open up a prompt that will let you type code line by line. This is useful for creating code to figure out what it does without writing a whole script (playing around).
    - This exploratory prompt is called a REPL (Read, Evaluate, Print, Loop).
    - <ins>REPL:</ins> REPL is an acronym for Read, Evaluate, Print, and Loop. Developers use REPL Python to communicate with the Python Interpreter. In contrast to running a Python file, you can input commands in the REPL and see the results displayed immediately. (according to codeinstitute.net)
    - The Python interpreter allows for what's known as an interactive REPL (Read-Eval-Print Loop), or shell, which reads a piece of code, evaluates it, and then prints the result to the console in a loop. You can try out code ideas quickly. (according to realpython.com)
    - Python's REPL is often known as the python shell.
    - The "python" command pulls up the python shell.

![image](https://github.com/JessieS444/learningPython/assets/157999229/6e50d97c-e4b8-40fb-92a2-100d1895526a)

- In the above, "print" is the function. This is an example of testing a line of code in the python shell. You call a function by providing an open parenthesis and closing parenthesis. An <ins>argument</ins> is the value passed to a function when its called, aka what is inside the parenthesis.
- Press the up arrow to get a copy of the last thing you typed into the python shell.
- Python shell can be used as a calculator. Just type in the equation, no function needed.
- The python shell can help you if you need it using the `help` function.
    - For example, if you want to know more about the `print` function, you would type `help(print)`. This will open up the pager with details about the print function.
    - The bottom of the page will read "(END)". To get out of a pager, you can press Q.
- To exit the python shell, use the `exit` function. I typed `exit()` to get out of the python shell. You can also use CTRL + D to "drop" out of it (exit).
