# Crash-Course-on-Python-

## Week 1
-  In a human language, **syntax** is the rules for how a sentence is constructed while
**semantics** refers to the actual meaning of the statements. 
- In a programming language like Python, the syntax is the rules for how each instruction is written and the semantics is the effects the
instructions have. 
- So what's the difference between a **script** and a **program?** The line between the two can be a bit blurry. In general, you can think of **scripts** as programs with a short development cycle that can be created and deployed rapidly. In other words, a **script** is a program that is short, simple, and can be written very quickly.. 

- *Automation* is the process of replacing
a manual step with one that happens automatically. 
- Some benefit of automation is consistency. 
- Automation isn't a solution for every situation, some tasks just
aren't suited for automation. For example, they may require a degree of
creativity or flexibility that automatic systems can't provide or for more
complicated or less frequently executed tasks creating the automation may actually
be more effort or cost than it's worth. 

- Automation is a powerful tool when used
in the right place at the right moment. It can save time, reduce errors,
increase consistency, and provide a way to centralized solutions and
mistakes making them easier to fix. 

- Python interpreter. In programming, an interpreter is the program that reads
and executes code. 

- Print is a Python function that writes what we tell it to on the screen. Like the statement hello
world for example, the print function is part of
the basic Python language, whenever we use keywords or functions that are
part of the language, we're using the programming
language's syntax to tell the computer what to do. 
- So what are functions
and keywords? *Functions* are pieces of code
that perform a unit of work.  *Keywords* are reserved words that are used to construct
instructions. These words are the core part of the language and can only
be used in specific ways. Some examples include
if, while, and for. The keywords
and functions used in Python are what makes up
the syntax of the language. 

## Week 2

- Text written between quotes in Python is called a string. In programming terminology, a string is known as a data type,  Most programs need to
manipulate some kind of data, and that data can come in a lot of different forums, or like we call them data types. A string is only one kind of
data type found in Python. There's a bunch of others, like an integer which represents whole numbers without
a fraction, like one, and float, which represents real numbers or in other words, a number with a
fractional part like 2.5. Generally, your computer doesn't know how to mix
different data types.

- For example, adding two integers together makes perfect sense to
computers, Adding together two
strings also makes sense. We just end up with the longer strings that contains the two, like so, but your computer doesn't know how to add
an integer and a string. If you tell it to mix these
two different data types, your computer isn't
going to know what to do and will raise an
error.

- Errors are a common
part of programming. The trick is to think of
errors as little clues from your computer to help you improve your programming skills. Read the errors carefully, understand what
they're telling you, and then use that new knowledge to help you fix the mistake.  It might be helpful to
think about data types in terms of information
they can represent. 

- For example, the name of a file would be represented as
a string data types, while the size of that file might be an integer data type. If you're ever not 100 percent sure what data types
a certain value is, Python gives you a
handy way to find out. You can use the type function, to have the computer
tell you the type. This might come in handy when dealing with
code that someone else wrote and you're not sure what data types it's using. 

 **Variables**
- *Variables* are names
that we give to certain values in our programs. Those values can be
of any data type; numbers, strings or even
the results of operations.

- When you create a
**variable** in your code, your computer reserves a chunk of its own memory to
store that value. This lets the computer access the variable later to read
or modify the value. 


- Generally, you can name variables whatever you like but there are some restrictions.
   -  First, you shouldn't use as variable names any of the key words or functions that Python reserves for its own, like print. Using these reserved
terms will make your program confusing to read
and will result in errors. 
  - Python also has some
restrictions on the characters you can
use to define a variable. Variable names can't have
any spaces and they must start with either a
letter or an underscore. 
   - Also, they can only be made up of letters, numbers and underscores. Some examples of valid and invalid variable names to understand this better. I_am_a_variable is the
valid variable name. I_am_a_variable2 is also
a valid variable name. 1_is_a_number is invalid because variable names must start
with a letter or underscore. Apples_&_oranges
is invalid because it uses the special
character uppers hand. 
  - Last thing, remember that precision is important
when programming. Python variables are case sensitive, so
capitalization matters. Lowercase name,
uppercase name and all caps name are all valid
and different variable names, and that rule on
variables is invariable.


 **Expression Numbers and Type Conversions**
 - Implicit Conversion :- The interpreter
automatically converts one data type into another [Implicit conversion is where the interpreter helps us out and automatically converts one data type into another, without having to explicitly tell it to do so.]
- Python operations aren't
just restricted to numbers. You can also use
the plus operator to add together strings. This lets you do
things like create sentences from individual words. Just don't forget to add
spaces to each words.
- explicit conversion:  to convert between
one data type and another [explicit conversion is where we manually convert from one data type to another by calling the relevant function for the data type we want to convert to.]

**Functions**
- We start a function definition with the def keyword, followed by the name we want to give our function. After the name, we have the parameters, also called arguments, for the function enclosed in parentheses. A function can have no parameters, or it can have multiple parameters. Parameters allow us to call a function and pass it data, with the data being available inside the function as variables with the same name as the parameters. Lastly, we put a colon at the end of the line.

- After the colon, the function body starts. It’s important to note that in Python the function body is delimited by indentation. This means that all code indented to the right following a function definition is part of the function body. The first line that’s no longer indented is the boundary of the function body. It’s up to you how many spaces you use when indenting -- just make sure to be consistent. So if you choose to indent with four spaces, you need to use four spaces everywhere in your code.
**

**Returning Values Using Functions**
- Sometimes we don't want a function to simply run and finish. We may want a function to manipulate data we passed it and then return the result to us. This is where the concept of return values comes in handy. We use the return keyword in a function, which tells the function to pass data back. When we call the function, we can store the returned value in a variable. Return values allow our functions to be more flexible and powerful, so they can be reused and called multiple times.

- Functions can even return multiple values. Just don't forget to store all returned values in variables! You could also have a function return nothing, in which case the function simply exits.

**Code Style**
- First off, you want the code to be self-documenting as possible. Self-documenting code is
written in a way that's readable and doesn't
conceal its intent. 

-  In programming lingo, when we re-write code to be
more self-documenting, we call this process refactoring.

- When good naming and clean organization can't
make the code clear, you can add a bit of
explanatory texts to the code. You do this by adding
what we call a comment. In Python, comments are
indicated by the hash character. When your computer
sees a hash character and understands that
it should ignore everything that comes after that character on that line.

**Comparison Operators**
- In Python, we can use comparison operators to compare values. When a comparison is made, Python returns a boolean result, or simply a True or False. 

- To check if two values are the same, we can use the equality operator: == 
- To check if two values are not the same, we can use the not equals operator: != 
- We can also check if values are greater than or lesser than each other using > and <. If you try to compare data types that aren’t compatible, like checking if a string is greater than an integer, Python will throw a TypeError. 

- We can make very complex comparisons by joining statements together using logical operators with our comparison operators. These logical operators are and, or, and not. When using the and operator, both sides of the statement being evaluated must be true for the whole statement to be true. When using the or operator, if either side of the comparison is true, then the whole statement is true. Lastly, the not operator simply inverts the value of the statement immediately following it. So if a statement evaluates to True, and we put the not operator in front of it, it would become False.
 
 **if Statements Recap**
- We can use the concept of branching to have our code alter its execution sequence depending on the values of variables. We can use an if statement to evaluate a comparison. We start with the if keyword, followed by our comparison. We end the line with a colon. The body of the if statement is then indented to the right. If the comparison is True, the code inside the if body is executed. If the comparison evaluates to False, then the code block is skipped and will not be run.
