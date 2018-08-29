# Practice Problem Sets

### Strings:

> Reference1: [Introduction to Strings](https://youtu.be/nefopNkZmB4)

> Reference2: [String Manupulations](https://youtu.be/YbipxqSKx-E)

1. Write a python program to split a given string at spaces.
```
	# Input
	"Hello! How are you?"

	#Output
	["Hello!", "How", "are", "you?"]
```
2. Write a python program to concatenate two given strings.
```
	#Input
	String1 = "My "
	String2 = "World"

	#Output
	"My World"
```

3. Write a python program to print a string in multiple lines.
```
	#Input
	'Hello! My name is Kaustubh. What is your name?'

	#Output
	'Hello!
	My name is Kaustubh.
	What is your name?'
```

4. Write a python program to print letters at even indices.
```
	#Input
	"Speckbit Exploratories"

	#Output
	"Seki xlrtre"
```

### Lists:

>Reference: [Lists and Lists Manupulation](https://youtu.be/1yUn-ydsgKk)

1. Write a python program to find the sum of all the elements of a list.
```
	# Input list
	[1,2,3,4]

	# Output
	10
```

2. Write a python program to find the product of all the elements of a list.
```
	# Input list
	[1,2,3,4]

	# Output
	24
```

3. Write a python program to add new element to the list.
```
	# Input List
	["Hello", "World"]

	#Output List
	["Hello", "World", "Hey"]
```

4. Write a python program to create a copy of a list.
```
	#Input List
	["My", "Name", "Is", "Speckbit"]

	#Output List
	["My", "Name", "Is", "Speckbit"]
```	

### Dictionaries:

>Reference: [Dictionaries and Dictionary manupulations](https://youtu.be/BSNFRKG1MfE)

1. Write a program to find a word in a dictionary.
```
	#Input Dictionary
	{1:"Speckbit", 2:"World", 3:"Quiet"}

	Word to be searched:
	Speckbit

	#Output
	If word is found, print - True
	else, print - False
```

2. Write a python program to print all the key value pairs in a given dictionary in the given format.
```
	#Input Dictionary
	{1:"Speckbit", 2:"World", 3:"Quiet"}

	#Output
	1--Speckbit
	2--World
	3--Quiet

	#Clue
	Use string formatting while printing.
```

3. Write a python program to print the key of a value given as a search element from a dictionary.
```
	#Input Dictionary
	{'a':"Speckbit", 'b':"World", 'c':"Quiet"}

	Search Element: Speckbit

	#Output
	Key is a.

	#Clue
	Use string formatting while printing.
```

4. Write a program to make a dictionary of Data of USN and Name.
```
	Inputs
	USN Name
	12	Abc
	11	cd
	10	xyz

	Output
	{12:"Abc", 11:"cd", 10:"xyz"}
```

### Loops:

>Reference1: [For loops](https://youtu.be/llguiJHU0kk)

>Reference2: [Range and While](https://youtu.be/Neir-vgPyxw)

1. Write a program to sort the elements of a list in ascending order.
```
	#Input List
	[1,12,14,13,2,4,7,9]

	#Output List
	[1,2,4,7,9,12,13,14]
```

2. Write a python program that takes two lists and returns True if they have at least one common member.
```
	#Input Lists
	list1 : [1,2,3,4,5]
	list2 : [5,6,7,8,9]

	#Output
	True
	# As 5 is the common element
	# Must return False if no common elements
```

3. Write a program to create a dictionary of numbers and their squares as a key value pair respectively for all the numbers below the specified input.
```
	#Input number:
	8

	#Output Dictionary should be
	{1:1, 2:4, 3:9, 4:16, 5:25, 6:36, 7:49}
```

4. Write a python program to generate a list of square of the numbers in the range (1,5) both included.
```
	#Input
	No input is taken from the user

	#Output
	[1, 4, 9, 15, 25]
```


### For and Conditionals:

>Reference: [Condtitional Statements](https://youtu.be/bk22K1m0890)

1. Write a python program to add a key value pair to the dictionary if the key does not exist in the given dictionary.
```
	#Input Dictionary
	{'a':"Hello",'b':"Hey", 3:"Hi"}

	Inputs in the console(command prompt) should like:
	Key Value
	3 Speckbit
	c Exploratories
	m World

	#Output 
	{'a':"Hello",'b':"Hey", 3:"Hi", 'c':"Speckbit", 'm':"Exploratories"}
```

2. Write a program to find if a given element is present in a given list.
```
	Search Term
	"Hello"

	#Input List
	["Hello", 1, 1.234, "My_World"]

	#Output
	True --> if present
	False --> if not present
```


### Functions:

>Reference1: [Function Basics](https://youtu.be/j2xhtI0WTew)

>Reference2: [Returning to function](https://youtu.be/xRIzPZlei9I)

>Reference3: [What are arguments and using arguments](https://youtu.be/mwr1AtpLMpI)

>Reference4: [Variable Scope](https://youtu.be/f3TVuuhe-fY)

>Reference5: [What are Keyword Arguments and how to use them in programs](https://youtu.be/DASOXeFFkCg)

1. Write a function for adding the words to a list.
```
	#Input words
	"Hello"
	"World"
	"Speckbit"
	"Exploratories"

	#Output List
	["Hello", "World", "Speckbit", "Exploratories"]
```

2. Write a python function to sum all the numbers in a list.
```
	#Input
	Take input of how many numbers the user wants to add.

	#Output
	Print the sum
```

3. Write a program which can filter even numbers in a list by using filter function.
```
	#Input List
	[1,2,3,4,5,6,7,8,9,10,11,12]

	#Output List
	[2,4,6,8,10,12]
```

### Complex Functions

>Note: Refer tutorial videos mentioned in functions part.

1. Write a function to add two elements which are passed as arguments to the function if they are of the same data type or if they are of different data types print an error message.
```
	#Input
	Values passed to the function arguments- 2,2

	#Ouput
	4

	If they are not of the same datatype print-
	"Error: The values passed are not of same datatpye"
```


