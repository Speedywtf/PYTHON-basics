#Variables

```Variables are way of storing values or datas into containers. There is no specific command for this, unlike other languages. You do this by doing:

<container> = <value/data> 

for EXAMPLE:

a = 5 

The variable a (which is in the containers place) has the value of 5

The value or a data type of a variable can be changed anytime, even after being declared with an already set value. 

For demonstration purposes, I have named the variable 'a'. However, while coding, you always want to make the name of the variable relevent to the purpose of the data, for example, if the
data stored is for a cars name, you should name the variable sometime like car_Name instead of a. 

There are certain rules to naming variables, the can and cant do's are: 

CAN 

Variable name can start with an understore character or a letter

A Variable name can only contain alpha-numeric characters and underscored (A-Z, 0-9, a-z, _)

Variables are Case Sensitive

Cannot

Name cannot start with a number

Name cannot include a non-alpha numeric characters, such as '-'

Name cannot have any spaces, such as: my variable = 0``` 

#Assign values to multiple variables in one line 

```You can assign values to multiple variables like this: 

x, y, z = "Orange", "Banana", "Cherry"

You can also assign the same values to multiple variables, like this: 

x, y, z = "Orange"```

#Outputting Values

```The print statement is used to output variables. 

EXAMPLE: print('Hello World')

OUTPUT: Hello World

To combine a variable and text, you use a + 

EXAMPLE: 

a = 10 

print("I am " + a) 

OUTPUT: 

I am 10 

You can also use the + character for multiple variables

EXAMPLE 

x = "Hi"

y = "Bye!"

z = z + y 

print(z)

OUTPUT: 

Hi Bye!

If you try to combine a string and a number, you will get an error

EXAMPLE: 

z = 10

y = "Hey I am "

print(y + z)

TypeError

A LOCAL variable is a variable created inside of a function, you cannot use the variable outside the function. 

A GLOBAL variable is a variable created outside of a function, and can be used inside or outside of any function

KEEP THIS IN MIND, YOU WILL LEARN ABOUT FUNCTIONS LATER```