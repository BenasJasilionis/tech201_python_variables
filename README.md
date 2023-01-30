# tech201_python_variables

# What are variables
Variables are names which are used to store information to be referenced and used by programs further down the line.
* Variables can be assigned by the syntax `= " "`.
* For example, `hi = "Hello"` will mean that the variable `hi` is referencing `Hello`
* Variables can be changed and reassigned:
* For instance, running `hi = "Hello there"` would overwrite the original hello from that point onward.
* Data which comes in the form of characters/words is known as a `string`

Variables don't have to store text, they can also store numbers:
* `a = 2` will mean that a will now store the `integer` 2 
* Decimals also work, e.g. `b = 2.2`, and these are known as `floats`

## Adding variables
* Variables which have the same data type can be added together with `+`.
* For instance, variables with text can be added together to print out a longer sentence
* Variables with numbers can be added or subtracted to do basic arithmetic




# Getting user input
Code can be written which takes information from users and assigns it to a variable using the `input()` command. Take the following example:

````
print("Hi, what is your name?")
name = input()
print("Hi " + name + " how old are you?")
age = input()
print("I am also " + age + ", what is your date of birth")
dob = input()
print(dob + ":Wow we are born in the same year!")
````
* The following code will print `Hi, what is your name?`
* The next line will take whatever the user writes and assign it to the variable name
* For instance, if the user writes "Jack", the third line will read: `Hi Jack how old are you?`
* The same can be seen on line 4, what ever the user inputs will be assigned to the variable `age`
* For example, if the user types 22, the 4th line will read : `I am also 22, what is your date of birth`
* The 5th and 6th lines work in the exact same way.