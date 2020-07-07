#Multiline strings

```Just like multiline comments, multiline strings also use three double quotes:

EXAMPLE: a = """Hi
		This is a 
		Multiline string"""```

#Strings Advanced 

```Strings are like arrays, an array of bytes representing unicode characters. 

Square Brackets can be used to access elements of the string 

a = "Hello"


Data            H       E       L      L     O       
 

Data value      0       1       2       3     4


print(a[1])

OUTPUT: e```

#Slicing 

```

#Slicing 

```You can return a certain range of characters by using the slice syntax, Specify the start and end index, seperated with a colon, to return part of a string, for example: 

b = "Hello, World!"
print(b[2:5])

OUTPUT: llo```

#Negative Indexing 

```To start counting from the end of the string: 

b = "Hello, World!"
print(b[-5:-2])

OUTPUT: orl```

#String Length

```len() returnes the length of a string:

a = "Hello, World!"
print(len(a))

OUTPUT: 13``` 

#String Methods 

```String methods can do many things, the way to use these are: 

<string name>.<string method>()

some examples are: 

print(a.strip()) #removes any space in the start or the end 

print(a.lower()) #returns the string in lower case 

print(a.upper()) #returns the string in upper case 

print(a.replace(<String letter one, for example "H">, <String letter two, for example "J")) 

print(a.split(",") # splits the string into substrings if it finds a seperator``` 

#Check String

```To check if a certain phrase or a character is present in a string, we can use the keywords in or not in. 

txt = "The rain in Spain stays mainly in the plain"
x = "ain" in txt
print(x)

OUTPUT: True 

txt = "The rain in Spain stays mainly in the plain"
x = "ain" not in txt
print(x) 

OUTPUT: False```

#String Concatenation

```To combine two strings, you can ues the + operator:


a = "Hello"
b = "World"
c = a + b
print(c)

To add a space inbetween them, add a " ":

a = "Hello"
b = "World"
c = a + " " + b
print(c)

YOU CANNOT COMBINE STRINGS AND NUMBERS 

to do this, you have to use the format() method:

age = 36
txt = "My name is John, and I am {}"
print(txt.format(age))```

#Some more string methods

```Some more methods:
Method	        Description
capitalize()	Converts the first character to upper case
casefold()	Converts string into lower case
center()	Returns a centered string
count()	Returns the number of times a specified value occurs in a string
encode()	Returns an encoded version of the string
endswith()	Returns true if the string ends with the specified value
expandtabs()	Sets the tab size of the string
find()	Searches the string for a specified value and returns the position of where it was found
format()	Formats specified values in a string
format_map()	Formats specified values in a string
index()	Searches the string for a specified value and returns the position of where it was found
isalnum()	Returns True if all characters in the string are alphanumeric
isalpha()	Returns True if all characters in the string are in the alphabet
isdecimal()	Returns True if all characters in the string are decimals
isdigit()	Returns True if all characters in the string are digits
isidentifier()	Returns True if the string is an identifier
islower()	Returns True if all characters in the string are lower case
isnumeric()	Returns True if all characters in the string are numeric
isprintable()	Returns True if all characters in the string are printable
isspace()	Returns True if all characters in the string are whitespaces
istitle()	Returns True if the string follows the rules of a title
isupper()	Returns True if all characters in the string are upper case
join()	Joins the elements of an iterable to the end of the string
ljust()	Returns a left justified version of the string
lower()	Converts a string into lower case
lstrip()	Returns a left trim version of the string
maketrans()	Returns a translation table to be used in translations
partition()	Returns a tuple where the string is parted into three parts
replace()	Returns a string where a specified value is replaced with a specified value
rfind()	Searches the string for a specified value and returns the last position of where it was found
rindex()	Searches the string for a specified value and returns the last position of where it was found
rjust()	Returns a right justified version of the string
rpartition()	Returns a tuple where the string is parted into three parts
rsplit()	Splits the string at the specified separator, and returns a list
rstrip()	Returns a right trim version of the string
split()	Splits the string at the specified separator, and returns a list
splitlines()	Splits the string at line breaks and returns a list
startswith()	Returns true if the string starts with the specified value
strip()	Returns a trimmed version of the string
swapcase()	Swaps cases, lower case becomes upper case and vice versa
title()	Converts the first character of each word to upper case
translate()	Returns a translated string
upper()	Converts a string into upper case
zfill()	Fills the string with a specified number of 0 values at the beginning```



