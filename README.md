# INFO2201_-notes
All the class notes from summer 


# W1d3
character = chr    ex: chr = "J"
string = strng     ex: strng = "Jenisha"
number= num        ex: num = 5

#assign a float variable
fltVar = 3.4 

#find out the type of the variable
type(fltVar)

#### input( ) always prints string so in other to print your input in float number type :   float(input("dcvbhdgbu"))

### Boolean expressions
== compariosn
x!= means not equals to. ex: x!= y meaning x is not equals to y
x>y means checking if x greater than y
x>=y means checking if x is greater or equal to y
x<= y means checking if x is smaller than or equals to y
x is y means checking if x is the same as y
x is not y means checking if x is not the same as y

OR = In "or" condtion  either of the condtion has to be true
b > c or a> c

And = In "and" condition both have to be true 
c>= b and a = b

### If condtion
z = 5
#check if its greater than 0 and print a statemetn
if (z>0):
    print('x is postive')
 ### modulo
 = a math operator that gives you the remainder after division.
 
 ### elif
 will run after if statment even 'if ' statment is true or not
 
  # W1D3
  
  ## Tuple
  =A tuple is a built-in data type in Python used to store multiple items in a single variable.

Key properties:

Ordered: The items have a fixed order and do not change position automatically.

Immutable: You cannot change (add, remove, or modify) items after you create the tuple.

Allow duplicates: Tuples can contain the same value multiple times.  ##example ; tuple= ("Banana", "Apple", "Banana", "Apple")
                                                                     ## oytput : (Banana , Apple , Banana , Apple)

Can hold mixed data types: Numbers, strings, booleans, lists, other tuples — anything.
 ## to print the first item of the variable: variable_name[0]
 ## to print the first second and third items in the tuple : variable_name[0:3]
 ## re-assign the second item to a letter:  not possible in tuples
 
 ## List
 A list is a built-in data type used to store multiple items in a single variable.
Think of it like a container or box that can hold a sequence of items.
Feature	Description
Ordered	Items keep their order (first, second, third, etc.)
Mutable	You can change, add, remove items anytime
Allow duplicates	Same value can appear more than once
Mixed data types	A list can hold strings, numbers, booleans, even other lists
### #get the items at positions 2 and 4: fruits[1:5:2]
### #get the items after postion 3 :mylist[4:]

 ## Appending : .append()
 Appending means adding a new item to the end of a list.

It does not replace any item — it just adds something after the last item.

It changes the length of the list by one each time you append.

### variablename. append(namethatyouwanttoadd)

## extending : .extend()
Extending a list means:
Adding multiple items (from another list, tuple, or any iterable) to the end of your list — one by one.

So instead of adding a whole list as one element, extend() takes each element and adds it individually.

## sorting : .sort()
=Sorting means arranging items in a specific order — usually:

Ascending (smallest to largest, A–Z)

or Descending (largest to smallest, Z–A)

Python has two ways to sort lists:
 sorted() function → returns a new sorted list, original stays unchanged
 .sort() method → sorts the list in place, changing the original
 
 ## Pop : .pop()
 =pop() is a list method used to:

Remove an item from a list
Return the removed item (so you can use it if you want)


## Disctonary : variable name = {
                                        "Key" : "Value"
                                        }

### to get the key = variablename.key()


 # W2D1
 ### While loop
 = A while loop repeats a block of code over and over again as long as a condition is True.
It checks the condition before each repetition.
 ### counter
 =A counter is just a variable that keeps track of how many times something happens.
You usually start it at 0 or 1, and then add 1 each time you repeat something
 ### For loop
 =A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string). With the for loop we can execute a set of statements, once for each item in a list, tuple, set etc.

#### Iterable
 An iterable is something you can go through one item at a time, usually in a loop.
 
 #### range()
 =The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and ends at a specified number. The range() function defaults to 0 as a starting value, however it is possible to specify the starting value by adding a parameter: range(2, 6), which means values from 2 to 6 (but not including 6).
 
 #### enumerate() : enumerate(fruits)
 =t lets you loop through a list (or any iterable) and get both:

The index (position in the list)

The item (the value)

It’s like adding a counter automatically when looping!


 
 # W2D2
 
 ## Functions:
 A function is a block of code which only runs when it is called. You can pass data, known as parameters, into a function. A function can return data as a result.
 Function ois called using def() keywod. 
 A parameter is the variable listed inside the parentheses in the function definition.
 An argument is the value that is sent to the function when it is called.
 
 #### example:
 def fullname(fname, lname, occupation = 'student')
    return fname +" "+lname+"is a " + occupation
    
    #And whne you call this function 
 def fullname('Jenisha', 'Shrestha' )
 /// It will print: Jenisha Shrestha is a Student.
 /// if you want to change the occupation then we can simply write: def fullname('Jenisha', 'Shrestha', 'Engineer' )
 /// which will print Jenisha Shrestha is a Engineer. 
 
 ## Scope
 When you create a function, it has its own little world called a scope.

Any variables you create inside the function stay inside that function.

If you have a variable outside the function with the same name, it will not be affected by the one inside.

### Example:
 // assign a variable
var1 = 'Word'

//make a function that has the variable as an argument
//have it return the mutated variable
def updated_variable(var1):
    var1 = var1 + " is cool"
    return var1



#print the output of the funciton and the original variable
print(updated_variable(var1))
print(var1)

//output:
Word is cool
Word

## Arbitrary Arguments, *args
This way the function will receive a tuple of arguments, and can access the items accordingly:

## W2D3

### class: Inculdes lots of methos, arrtibutes and function.
needs to define the variable in the class
### Ex:
class personinf0():
    def name():
      print(jnjxni):
    def age():
    print(xjdxjd)
    
 ## Class initialization __ init __ and methods¶
 
