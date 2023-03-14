# Programming basics

## The very low level stuff
The computer only understand 1s and 0s (machine code). Above that, there are some very basic
commands, like move memory, copy memory, add numbers, etc. This language is called
assembler. It is possible to program at this level, but the programs are very 
difficult to understand for a human. To solve this, many programming languages have been
invented to make programming easier. To name a few:

- C
- C++
- Java
- Ruby
- Python              <-- We'll be programming with this one
- JavaScript          <-- And probably with this one
- Haskell
- and many (maaany) more


## Different, but not by much
There are some differences between languages that make them useful in this or
that situation, but most of them have the same problems

- How do we tell it that one step ended and now we have another?
- How do we make groups of instructions (instead of a single step)
- How do we do math operations, and how do we tell it which one goes first
- How do we store results
- How do we show results
- How can we add text that is not code
- How can we add descriptions (comments) to the code
- And above all, how to translate the language into machine code because that's the only thing the computer 
understands. You don't need to worry now about this (but what's your guess)

## What Almost all programming languages have
### Telling steps apart
How does the program knows that one instruction started and one ended? There are mainly three ways to do it
depending on the language
```
Each line is a step  (like Python and Haskell)
Using a special character. In C, Java and JavaScript an instuction ends with a semicolon (;)
Using grouping symbols, like parenthesis (but we won't be learning Lisp, don't worry)
```

### Comments
Comments are pieces of code that are not executed. They are used to explain a difficult 
code piece or give information about how to use it to other programmers. E.g.
```
In Python:
# In python, a # symbol marks the start of a comments

In JavaScript, C, Java 
// Two slashes indicate that this is not code, but a comment
```

### Numbers
In must languages, there are two types of numbers: integers and real. You must be aware that if you
are working with integers the operations are done with integers. E.g.
```
10.0 + 10.0   <--- returns 20.0
10 + 10       <--- returns 20
5.0 / 2       <--- returns 2.5
5 / 2         <--- returns 2!!!
```

### Strings
Strings are text that is not part of the program, but that we want to use in our code. It is usually 
enclosed in double quotes. E.g.
```
"This is a great string"  //Note that the string starts with " and ends with "
"And the winer is..."     //Note also that I'm using comments in the code :)
```

### Variables
If you're familiar with algebra, you already know what a variable is: a box, a placeholder that 
can contain any number. The difference in programming is that a variable can contain many things, and can
have more than one letter. In most languages, a variable must start with a letter or underscore, and then
can have 32 or even 64 letters, numbers or underscores. E.g.:
```
In Python:
x0 = 10
_result = "We didn't start the fire"

In Java and C++
int x0 = 10; //Note that we added "int". In many languages, you need to specify
             //the variable type
string _result = "This is a string";

In JavaScript
let x0 = 10; //Note that we don't specify the type, but we use "let" 
const _result = "This is a string"; //if you know your value won't change, use const
var anyVariable;  //using var is a bad idea. We'll look into why
```

### Order of operations
If you have a large number of operations, like `5 + 4 * 8 / 2 + 9 ` how do you know which operation goes first?
Well, all languages have an operator precedence. It looks a lot like arithmetics. Stuff inside parenthesis is 
calculated first, multiplications go before additions, etc. Do a search if you're in doubt.


### Conditionals
In any program, you will need to execute some steps only if a condition is met:
if you have less money than the required, if a name is in a list, etc.
Usually, the syntax is super simple
```
Python:
if "Bon Jovi" in artists:
    playSong("It's my life")
    # Note that I'm using exactly 4 spaces
	# This is how Python knows which steps to execute
	# But don't worry, we'll do exercises
	
JavaScript:
if (moneyAvailable > costOfItem) {
    buyItem();
    //In JavaScript we use the { and } to tell it which steps we want
	//to execute when the condition is true and which not
}
```

### Functions
We'll be writing functions soon. For now, think of functions as a way to group some steps together
so you can use them many times in different places.
