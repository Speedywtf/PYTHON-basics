#Main Data Types 

```The main used data types are: 

Str, int, float, list, turple, dict, bool

DESCRIPTION

Str: A String is a sequence of characters, these could be letters or numbers

Int: An Integer is any whole number, positive or negative of unlimited length 

float: A float is a number, positive or negative with multiple decimal places 

list: A list is a variable with multiple values that can be changed

turple: A turple is a variable with multiple values that cannot be changed

dict: A dict is a list with each value assigned to a key, or a 'name'

bool: A boolean is a true or false value```


#Data Types


```Data Types have many different categories, such as: 

Category     Data type(s)

Text Types    Str

Numeric Types  int, float, complex

Sequence Types list, tuple, range

Mapping Type   dict

Set Types   set, frozenset

Boolean Type  bool

Binary Type  bytes, bytearray, memmoryview```

#Further Data Types

```Getting the data type:

You use the type() function to find the data type of the object, the correct usage is: 

x = 5 

print(type(x))

OUTPUT: <class 'int'> (This tells you that the data type is an int)```

#Setting the data type

```Ìn python, when you assign a value to a variable, the data type is also assigned. 

EXAMPLE                            DATA TYPE 

x = "Hi"                             str

x = 20                               int 

x = 20.5                             float

x = 2j                               complex

x = ["Apple", "Banana"]              list

x = ("apple", "banana")              tuple

x = range(6)                         range

x = {"name" : "John"}                dict

x = {"apple", "banana"}              set

x = frozenset({"apple", "cherry"})   frozenset

x = True                             bool

x = b"Hello"                         bytes

x = bytearray(5)                     bytearray

x = memoryview(bytes(5))             memoryview```

#Setting the data type

```You can set a data type that you want, for example for a variable or a user input

EXAMPLE                              DATA TYPE

x = str("Hi")                             str

x = int(20)                               int 

x = float(20.5)                           float

x = complex(2j)                           complex

x = list(("Apple", "Banana"))             list

x = tuple(("apple", "banana"))            tuple

x = range(6)                              range

x = dict(("name" : "John"))               dict

x = set(("apple", "banana"))              set

x = frozenset(("apple", "cherry"))        frozenset

x = bool(5)                               bool

x = byte(5)                               bytes

x = bytearray(5)                          bytearray

x = memoryview(bytes(5))                  memoryview```

#Type Conversion 

```You can convert one type to the other by specifying another data type: 

x = 1 #int

y = 2.8 #float

z = 1j #complex

#convert from int to float

a = float(x)

#convert float to int

b = int(y)

#convert int to complex 

c = complex(x)```

#Random Number

```Python has a built in module named random that can be used to make random numbers: 

import random

print(random.radrange(1,10))

OUTPUT: Any random number in between 1 and 10```










