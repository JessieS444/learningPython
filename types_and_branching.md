# Types and Branching

## Numeric
- All the information we have covered so far is referred to as data. Different things are different data types.
- <ins>Integers</ins>: whole numbers like 1. "int." for short.
  - (look I know what integers are but I am Afraid I will forget)
- You can multiply using an asterisk.
- The solution to any math problem that you enter into the python shell will be stored in the variable underscore.
  - So if you type `_`, then it will print the answer to the last equation.
- <ins>Floating-Point Number</ins>: aka "float." A non-integer number with a decimal point. This is a different data type than integers.
  - Even whole numbers that display a decimal point are considered float. 4.0 is a float.
  - Needed for precision.
  - Need to be careful with this. Sometimes will get odd results. Example: 0.1 + 0.1 + 0.1 - 0.3 will give you the answer 5.551115123125783e-17 with is a negative exponent and is zero with seventeen zeros following it and then a five. Why? I have no idea.
- To round floats back to an integer, use the function `round`. Use the underscore to round the last solution you got: `round(_)`. 
- Python uses PEMDAS: Please Excuse My Dear Aunt Sally - Parentheses, Exponents, Multiplication and Division, Addition and Subtraction.
- "TypeError" will occur if you mix and match types of strings that don't work together in equations (for example, "apple" + 2 or "11" +2).
- You can use the command `int( )` to transform a number into an integer. Conversely, you can use `float( )` to transform into a float. These functions will not round, they will just drop everything after the decimal point.
- <ins>Division Shortcut</ins>: normal division uses a forward slash. If you use two forward slashes, it is the division shortcut and will get you just the whole number portion without the decimal (integer instead of float).
- <ins>Modulus</ins>: lets you get the remainder for math that does not have a whole number answer. To use the modulus put a % sign as the operator.
  - Example: `23 % 3` gets you the answer of 2 because 3 goes into 23 seven times with a remainder of 2.

## Strings and Operators
- After you create a string, it is <ins>immutable</ins>, or impossible to modify.
- When making a string literal using either quotes or double quotes, you can use a backslash to start an <ins>escape sequence<\ins>.
- <ins>Escape Sequence<\ins>: use backslash to tell the interpreter to treat a quote or double quote like a character instead of syntax.

## String Methods


## Booleans


## If, Else, and Elif


## Comparisons
