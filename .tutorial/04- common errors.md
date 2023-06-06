# Common Errors

*First, delete any other code in your `main.py` file. Copy each code snippet below into `main.py` by clicking the copy icon in the top right of each code box. Then, hit `run` and see what errors occur. Fix the errors and press `run` again until you are error free. Click on the `👀 Answer` to compare your code to the correct code.*

## Syntax Error
👉 What is wrong with the code below? Copy the code only (not the error message) and hit `run`.
```python
my variable = input("WHO GOES THERE? ")
print(my variable)
```
Did you get this error message? What can you fix?

```
  File "main.py", line 1
    my variable = input("WHO GOES THERE? ")
       ^
SyntaxError: invalid syntax
```


<details>

<summary> 👀 Answer</summary>
Did you notice the space in the variable name? We never put spaces in variable names - it just confuses the poor computer!
</details>


## Name Error
👉 What is wrong with this code? Copy only the code and press `run`.
```python
myGrandma = input("How's your Grandma doing? 😘 ")
print(mygrandma)
```
Did you get this error message? How can you fix it?
```
How's your Grandma doing? 😘 fine
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    print(mygrandma)
NameError: name 'mygrandma' is not defined
```
<details>
  <summary> 👀 Answer</summary>

- What we're trying to print out is *NOT* the same as what we set the varaible up as in the first place. The **capitalization** is different.  `myGrandma` versus `mygrandma`

- This is also important when you try to print out a variable that you haven't created yet. You must ALWAYS create the variable BEFORE you print it out.
</details>


## This is just plain weird...
You won't get an error from this one, but the output won't make a lot of sense...

👉 Copy this code and `run` it to see what happens.
```python
myLunch = input("What are you having for lunch? ")
print("Hmm, it sounds like you really should just order")
print("myLunch")
print("as soon as possible!")
```


```
What are you having for lunch? Burrito
Hmm, it sounds like you really should just order
myLunch
as soon as possible!
```
<details> <summary> 👀 Answer</summary>

- You've tried to print a variable, but added in quotes! 
- Remember: quotes will ***literally*** print out whatever you stick in them.
- In this case it's printing the variable name instead of the contents of the variable.
- If you want the contents, then you DO NOT USE QUOTES.
</details>

