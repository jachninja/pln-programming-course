# Working with functions
Sooner or later, you will want to reuse your code. 
After all, you don't want a program that only calculates
the area of one triangle. You want it to calculate it for
all triangles. Or a program that works with many users,
not only one user

The format of a function is simple:

```
# we have "def", then a name. Then we have the parameters that this function will use. And then a colon
def name_of_function(parameter1, parameter2):   
    # things that this function does
    # Note that I have 4 indentation spaces to "group" the function code
    return some_value  # At the end, you return the result of your function.
```

## Function examples

```
def circle_area(radius):
    area = PI * radius**2
    return area 
```
Note that I used a name that describes what my function does, and I also named
my parameter radius. Using good names will make your life a lot easier
in the future.

```
def say_hello(person):
    print(f"Hello {person}")
    return
```
Note that I'm using a special format for string that allows me to add a variable.
Experiment with it to see what it does.
Note also that this function doesn't have any value to return, so it only says
"return"

## Excercises
Make a couple of functions that calculate the area of a square.
Save your code, commit, and push it.

Next, we're going to look at other data types and loop
