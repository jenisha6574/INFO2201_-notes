# INFO2201_-notes
All the class notes from summer 

### to install package : pip install 

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
 __init__
 
 
 # W3D1
 
 ## Files
 
 ## Os packages : import OS
 = This packages helps to navigate differeny files and folder within the operating control. 
 ## #get your current working directory
path = os.getcwd()
print(path)
 ## File handling
 = Key function while to open the file in python is open().
 ### open() function takes two parameters : filename and mode.
 There are four different methods (modes) for opening a file:

##### "r" - Read - Default value. Opens a file for reading, error if the file does not exist
#####  "a" - Append - Opens a file for appending, creates the file if it does not exist
##### "w" - Write - Opens a file for writing, creates the file if it does not exist
#####  "x" - Create - Creates the specified file, returns an error if the file exists

you can specify if the file should be handled as binary or text mode
#####  "t" - Text - Default value. Text mode
##### "b" - Binary - Binary mode
= with open("data/filename",'r') as f:
#### .strip() this removes any leading, and trailing whitespaces

### encoding = "utf8"    [tells Python to use UTF-8 encoding, which handles most text correctly (like special characters).]

## differnce betwwen . readlines() and .read()
### .readlines() 
= Reads the entire file, but splits it into a list of lines.  ex: [line1, line2,line3]
### .read()
=Reads the entire content of the file as ONE big string.
 ex: line1
     line2
     
  ## Regular expression (re)
 =allows you to navigate, and edit things such as strings. There are some key methods that we should know:
find()
findall(): returns a list of all the matches of the pattern we specified found in the source
replace()


=
re.findall("resturant", myString) # to find the word resturand in mystring
#find all of the digit ONLY 
re.findall("\d+", myString)
#find all of the WORDS ONLY 
re.findall("\w+", myString)
 to find word before and after : "\w+ restaurant \w+"
## search
#find if play is in this text

re.search("play",story)

## Metacharacters¶
= It is witha special meaning


# W3D2
## CSV Files : comma seprated value


    =It is a simple file format used to store tabular data (like a spreadsheet or database).
=Each line in a CSV file represents a row of data, and each value in that row is separated by a comma.

   ## file handel : csv.reader(f, delimiter= '"')
   
   
   ## JSON files : Java Script object notation
   
   = bunch of dictonary
   
   ex:
   dict = {
    'key1':
        'value1',
    'key2':
        'value2',
    'key3':
        'value3'
}


# w3D3

shows_year = list(set(shows_year))
this code removes the duplicate and prints the otupt in a list without the duplicate number
ex: [2015, 2015, 2014, 2013, 2014] to[2013, 2014, 2015}

shows_year.sort(reverse=True)
this code sort from recent to oldest or greatest to least

# W4D1   Numpy
numpy
import numpy as np
np.
## array
= a list
### coverting list to an array
arr1 = np.array(data1)
## checking the diameter of array
arr2.ndim
### checking shape
arr1.shape
## type
arr1.dtype
 ## A Multidimensional Array
 #make a 2D array
 arr2d = np.array([[1, 2, 3],[4,5,6],[7,8,9]])
 #make a 3D array
arr3d = np.array([[[1,2,3],[4,5,6],[7,8,9],[10,11,12]]])

## Transpose
convert the row into colum and colum into row
#find the transpose of the matrix
arr5.T
### to convert the list into matrix size
arr5_reshaped = arr5.reshape((3,5))
arr5_reshaped.T


# W4D2 APIs

### web scarping 
=comman way to take/collect data or stuff from internet/website.
### robots.txt  : use this file to see what parts of the site can legally be scraped.
= This file tells scrapers what they are allowed or not allowed to access. 
For example, CNN’s file shows:

What parts of the site can be scraped,

Which tools or "robots" are allowed,

Which folders (like ads or polls) are off-limits.

## API
= An API is a way for two computers or programs to talk to each other.
You (the user) use a program (called the client) to ask another computer (called the server) for information.
The server is where the information is stored, and it sends back a response to your request.
###  documentation
= This tells you how the API works and where to find the data (these places are called endpoints).

### endpoint 
= it is like a specific address on the internet where a certain piece of information is kept.

## import request
This is library that makes a HTTP request and gets backend information from a website, such as RSS feed.

pokemonName = 'charmander'
pokemonSearch = requests.get("https://pokeapi.co/api/v2/pokemon/"+pokemonName).json()

## Exercise 
#this is a key
aKey = "815f527f75d594aa272fc6c9205136b2"

#the api root information is found here - https://www.last.fm/api/intro
rootURL = "http://ws.audioscrobbler.com/2.0/"

#write a querey
artistSearchQuery = requests.get(rootURL+"?method=artist.search&artist=eminem&api_key="+
                          aKey+"&format=json").json()
                          
                          
  # W4D3
  
  ## web scraper
  sometimes webistes doesn't conatain a API, so we can create something called a web scraper instaed to get the data.
  In web scarper, we  skip the client section(your coputer)and talk directly to the Server(t)he computer that holds the website using code to get data from the web page.
  
  =To build a Web Scraper, you need a few tools. One of the most important is a Python library called:
  ## request : import request
  =This tool lets your program send a message to the website (called an HTTP request) and get back the HTML content of a page.
  They also include a link to the official documentation so you can learn more about how requests works.
  
  ## XML : Extensible Markup Language
  =It’s a way to store and organize data so that both humans and computers can read it easily.

## Beautiful soup 
= It is a Python library for pulling data out of HTML and XML files.