#What are lists

```A list is in basic a variable with multiple values, thus creating a list. A lists values can be changed and are ordered. An example of a list is: 

thislist = ["Windows", "Apple", "Linux"] 

Here, the list called 'thislist' has three different values, Windows, Apple and Linux, in that exact order.

Lists in python can have different data types, it does not have to be in all the same type``` 

#Creating Lists 

```Creating a list: 

<listname> = [<value 1>, <value 2>, <value 3>]

Example: 

examplelist = ["Hi", "I", "am", "William"] 

print(examplelist)

OUTPUT: ['Hi', 'I', 'am', 'William']```

#Accessing items

```You can access an item (an item is any of the different values inside the list). Be careful that this starts with 0 not 1, like shown:

Item:  A   B  C  D  E  F  G

Value  0   1  2  3  4  5  6

To access a specific item in a list, use the index number like shown: 

print(<listname>[<index number of item>])

EXAMPLE: 

examplelist = ["Hi", "I", "am", "William"] 

Print 'I'

print(examplelist[1]} (remember the value is not 2, it is one because the first value starts at 0) 

OUTPUT: I```

#Negative Indexing 

```Negative indexing indexes the last item as -1, second last as -2 etc. 

Example: 


examplelist = ["Hi", "I", "am", "William"] 

use negative indexing to output William

print(examplelist[-1])```

#Range of Indexing 

```To return multiple values, use a : in the middle of the two numbers like this: 


examplelist = ["Hi", "I", "am", "William"] 

Output: I, am, William

print(examplelist[1:3])

To print from the start to a specific value do: 

print(examplelist[:2])

To print from specific value to the end do: 

print(examplelist[2:])

This all can also be done with negative indexing``` 

#Change Item Value 

```If you want to change the value of an item, do this: 

<listname>[<value index>] = <new value> 

Exmple:

examplelist = ["Hi", "I", "am", "William"] 

Change the item 'I' to '!'

examplelist[1] = "!"

print(examplelist)

OUTPUT: ["Hi", "!", "am", "William"]``` 

#Check if item is in the list 

```To check if an item is on the list, you use an if statemnt like this: 

examplelist = ["Hi", "I", "am", "William"] 

Check to see if 'am' is in example list: 

examplelist = ["Hi", "I", "am", "William"] 
	if "am" in examplelist: 
		print("Yes, am is in this list")```

#How to get the list length 

```To find out how many items are in your list, use: 

examplelist = ["Hi", "I", "am", "William"] 

print(len(examplelist)) 

OUTPUT: 4``` 

#Add Items to list

```To add items to the end of the list, use the .append() method like this:

<list>.append(<item>) 

EXAMPLE: 

examplelist = ["Hi", "I", "am", "William"] 

examplelist.append("Boi") 

print(examplelist) 

OUTPUT: 

examplelist = ["Hi", "I", "am", "William", "Boi"]

To add to a certain position: 

<listname>.append(Index, value)

EXAMPLE: 

examplelist.append(1, "!")

OUTPUT: 

examplelist = ["Hi", "I", "1", "am", "William"] ```

#Remove Item

```There are many ways to remove a list: 

WAY 1: 

using the remove() to remove a specified item like this:

examplelist = ["Hi", "I", "am", "William"] 

examplelist.remove("Hi")

print(examplelist) 

OUTPUT:

examplelist = ["I", "am", "William"]

WAY 2: 

using the pop() to remove a specified index or the last index if not specified: 

examplelist = ["Hi", "I", "am", "William"] 

examplelist.pop() 

print(examplelist) 

OUTPUT

examplelist = ["Hi", "I", "am"]

WAY 3: 

The del keyword, which deletes a specified index

examplelist = ["Hi", "I", "am", "William"] 

del examplelist[0]

print(examplelist)

OUTPUT

examplelist = ["I", "am", "William"]   

WAY 4: 

The clear() function empties the list: 

examplelist = ["Hi", "I", "am", "William"] 

examplelist.clear()

print(examplelist)

OUTPUT

[]``` 

#Copying a list

```You cannot use list1 = examplelist because then list 1 will have any changes made to examplelist, instead you have to use the copy() method: 

examplelist = ["Hi", "I", "am", "William"] 

listone = examplelist.copy()

print(listone)

OUTPUT: 

listone = ["Hi", "I", "am", "William"]

OR you can use the list() method: 

examplelist = ["Hi", "I", "am", "William"] 

listone = list(examplelist) 

print(listone) 

OUTPUT: 

listone = ["Hi", "I", "am", "William"]``` 

#Combining Two lists

```By using the + operator, you can join two lists: 

examplelist = ["Hi", "I", "am", "William"] 

listtwo = ["It", "is"] 

listthree = examplelist + listtwo

print(listthree)

OUTPUT:

listthree = ["Hi", "I", "am", "William", "It", "is"]```

#All list methods 

```These are all the list methods

append()	Adds an element at the end of the list
clear()	        Removes all the elements from the list
copy()	        Returns a copy of the list
count()	        Returns the number of elements with the specified value
extend()	Add the elements of a list (or any iterable), to the end of the current list
index()	        Returns the index of the first element with the specified value
insert()	Adds an element at the specified position
pop()	        Removes the element at the specified position
remove()	Removes the item with the specified value
reverse()	Reverses the order of the list
sort()	        Sorts the list```
 

