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
 
 
 # W2D1
 ### While loop
 ### For loop
 
 An iterable is something you can go through one item at a time, usually in a loop.
 
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
 
