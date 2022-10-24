```python
# Exercise Variables - 1
# Create a firstName variable and assign the value Mario to it.
firstname = 'Mario'
```


```python
# Exercise Variables - 2
# Create an age variable and assign the value 25 to it.
age = 25 
```


```python
# Exercise Variables - 3
#Create a sentence variable and assign the value Hello, I'm Mario! to it without using double quotes.
sentence = """Hello, I'm Mario!"""
```


```python
# Exercise Variebles - 4
# Create an amount variable and assign a float value to it.
amount = 156.5
```


```python
# Exercise Variebles - 5
# Create a set of 3 variables and assign True as value of each one.
a, b, c = True, True, True
```


```python
# Exercise Variebles - 6
# Remove the illegal characters in the variable 1my-first2_Name = 'Mario'.
my_first_name = 'Mario'
```


```python
# Exercise Variables - 7
# Write single quotes or double quotes correctly
val = "Hi, my name is John Doe, 'python'"
```


```python
# Exercise Variables - 8
# Create 3 different variables and assign 3 different values. Write only one operation. Print them on terminal`
first_ = 'md'
second_ = 'mohibur'
third = 'rahman'
print(first_,second_,third)
```


```python
# Exercise Variables - 9
# Swap the value of the variables
a = 2
b = 5
b , a = a , b
print(a,b)
```


```python
# Exercise Variables - 10
# Print the length of each variable.

hello = 'Hello!'
name = 'Jhon Doe'
age = '40'

print(f'{len(hello)} \n,{(len(name))}')
print(len(name), end='')
print(len(age))
```


```python
# Exercise Variables - 11
# Modify the variables as suggested
a = 'hello'  #capitalize
b = 'tom'  #uppercase
c = 'LAURA'  #lowercase 
question = 'How are you' #change o in e
age_question = 'How old are you?' #use the correct method to create a string for each word
print(a, b, c, question, age_question)

a = a.capitalize()
b = b.upper()
c = c.lower()
question = question.replace('o', 'e')
age_question = age_question.replace('How old are you?', 'How old are you ?')
print(a, b, c, question, age_question)
word_1 = age_question.split(' ')
word_1 = age_question.split(' ')
print(word_1[0])
print(word_1[1])
print(word_1[2])
```


```python
# Exercise Variables - 12
# Create two variables called name and age. Then create a variable called hello and print the name and the age. Use the formatted string literal.

name = 'Mike'
age = '30'
hello = "Hello, "+ name + "."+ " You are " + age
print(hello)

```


```python
# Exercise Operators - 1
# Insert the appropriate logical operator in order to print False

print(2>2) # Should print False
```


```python
# Exercise Operators - 2
# Change the logical operators in order to print True

print(True and (0 == 0 or True)) # Should print True
```


```python
# Exercise Operators - 3
# Print the rest of the 5/2 division

import math
float_ = 5/2
full_, after_decimal = math.modf(float_)
print(full_, after_decimal)
print(5//2)
print(5%2)
print(5/2)
```


```python
# Exercise Operators - 4
# Insert the appropriate logical operator in order to print True.

print(not ("testing" == "testing" and "Mario" == "Cool Guy")) # Should print True

```


```python
# Exercise Operators - 5
# Initialize and print the sentence variable using the appropriate operators.
firstName = "Mario"
lastName = "Rossi"

sentence = (f'{firstName} {lastName}')

print(sentence) # Should print "Mario Rossi"


```


```python
# Exercise Operators - 6
# Check if "Nike" is in brands array using the appropriate logical operator

brands = ["Adidas", "Nike"]
print("Nike" in brands) # Should print True

```


```python
# Exercise Operators - 7
# Check if "Reebok" is not in brands array using the appropriate logical operator

brands = ["Adidas", "Nike"]
print("Reebok" not in brands) # Should print True

```


```python
# Exercise Methods - 1
"""With type command you can see the type of a variable in python eg: type(1) print each components type with this way you can see most significant data types in python

print(__("Hello World"))
print(__(True))
print(__(False))
print(__(33))
print(__(24.5))
print(__(4+1j))
print(__(4j))
print(__(["lion", "monkey", "dog","fish"]))
print(__(("lion", "monkey", "dog","fish")))
print(__({"name" : "John", "surname" : "Doe", "age":22}))
print(__({"lion", "monkey", "dog","fish"})) """
print(type("Hello World"))
print(type(True))
print(type(False))
print(type(33))
print(type(24.5))
print(type(4+1j))
print(type(4j))
print(type(["lion", "monkey", "dog","fish"]))
print(type(("lion", "monkey", "dog","fish")))
print(type({"name" : "John", "surname" : "Doe", "age":22}))
print(type({"lion", "monkey", "dog","fish"}))
```


```python
# Exercise Methods - 2
""" the number types can be converted to each other wit the int() float() complex() methods also float numbers can be rounded with the method round()

convert num1 to float and assign to itself
convert num2 to int and assign to itself
convert num3 to complex and assign to itself
use round method for num4 and assign to itself
use round method for num5 and assign to itself
print them all
print their types """

num1 = float(1.3)
num2 = int(2.3)
num3 = complex(1j) 
num4 = round(1.4) 
num5 = round(1.5)

print(num1 ,'\n', type(num1))
print(num2 ,'\n', type(num2))
print(num3 ,'\n', type(num3))
print(num4 ,'\n', type(num4))
print(num5 ,'\n', type(num5))
```


```python
# Exercise Methods - 3
""" to convert a number to string we can use str() function this is called casting

cast num1 to string and assign to num1_str
check the length of the string
get the third element of string (the one in the 3rd order)
get the 3-5 elements of string (both inclusive) by string slicing
!!!check if num2 in string (cast if necessary)
!!!check if num3 in string (cast if necessary)
concatenate 0 to the string from left and assign to string_with_0
get the characters of string_with_0 from start to position 4 (end point exclusive)
get the characters of string_with_0 from position 5 until the end
use negative indexing to reach the "567" string_with_0 """

num1 = 1122334455666
# cast num1 to string and assign to num1_str
num1_str = str(num1)
# check the length of the string
print(len(num1_str))
# get the third element of string (the one in the 3rd order)
print(num1_str[2])
# get the 3-5 elements of string (both inclusive) by string slicing
print(num1_str[3:5+1])
#!!!check if num2 in string (cast if necessary)
num2 = str(2.3)
print(type(num2))
print(num2 in num1_str)
# !!!check if num3 in string (cast if necessary)
num3 = str(complex(1j)) 
print(type(num3))
print(num3 in num1_str)
#concatenate 0 to the string from left and assign to string_with_0
string_with_0 = '0' + num1_str
# get the characters of string_with_0 from start to position 4 (end point exclusive)
print(string_with_0[4:-1])
# get the characters of string_with_0 from position 5 until the end
print(string_with_0[5:])
# use negative indexing to reach the "567" string_with_0
print(string_with_0[-9:-6])
    
```


```python
# optional
num1 = "01122334455666"
x=num1[8:5:-1]
new_str_reverse = ''.join(sorted(x))
print(new_str_reverse)
```


```python
# Exercise Conditions - 1
# print if num1 or num2 is greater num1 = 335 num2 = 66
num1 , num2 = 355 , 66
if num1 > num2:
    print('num1 is greater')
else:
    print('num2 is greater')
```


```python
# Exercise Conditions - 2
# check if number1 is greater than number 2 and print number1 is greater than number2 then check and if number 2 is greater than number 1 and print number2 is greater than number1 finally at the end if both conditions incorrect print number2 equals to number1

number1 = 66 
number2 = 66

if number1 > number2:
    print('number1 is greater than number2')
elif number1 < number1:
    print('number2 is greater than number1')
else:
    print('number2 equals to number1')
```


```python
# Exercise Conditions - 3
# Compare those 2 numbers and write X greater than Y But be sure you are making the check for all the conditions
import random

X = random.randint(1,100)
Y = random.randint(1,100)
if X > Y:
    print('X is greater than Y')
elif X < Y:
    print('Y is greater than X')
else:
    print('X equals to Y')
# Compare the numbers to eachother 

```


```python
# Exercise Conditions - 4
# Compare those 2 numbers' absolute values and write X's absolute value greater than Y's absolute value Use abs function to do that
# eg.
# abs(-5) -> 5
# abs function makes all numbers positive

import random

number1 = random.randint(-100,100)
number2 = random.randint(-100,100)

if abs(number1) > abs(number2):
    print('number1 is greater')
else:
    print('number2 is greater')
    
```


```python
# Iterators - While Loop, Exercise -1
"""Create ` * **

` this shape with print and while loop statements
"""

# Iterators - While Loop
# Create ` * **
i = 1 
while i<6:
    print("*"*i)
    i = i+ 1


```


```python
# Iterators - For Loop, Exercise -2
Create
"""
*
***
*****
this shape with print, for loop, if and continue statements"""


for n in range(1,10,2):
    print("*" * n)
    
    if n < 4:
        continue
    else:
        break
    

    
```


```python
# Iterators - For Loop, Exercise -3
""" Check if it is time for coffee break if it is just break
To do that lets iterate through given list don't change the COFFEE BREAK statement.
just find another way to do it """

todo = ["exercise1", "exercise2", "exercise3","coffee break" ,"exercise4","exercise5","exercise6"]
for x in todo:
    if x.upper() == "COFFEE BREAK":
        print(x)
        break
  
```


```python
# Iterators - For Loop, Exercise -4
""" 
Iterate each elements of list1,tuple1,set1 and print them out
For the dict1 iterate all elements but only print the ones who are living on land in the form of x lives in y """

list1 = ["lion", "monkey", "dog","fish"]
tuple1 = ("lion", "monkey", "dog","fish")
set1 = {"lion", "monkey", "dog","fish"}
dict1 = {"lion":"land", "monkey":"land", "dog":"land","fish":"water"}


print("---- printng item from the list ---- \n")
for item in list1:
    print(item)  
print()
print("---- printng items from the tuple ---- \n")
for item in tuple1:
    print(item)
print()
print("---- printng items from the set ---- \n")
for item in set1:
    print(item)
    
print()
print("---- printng items from the dict1 ---- \n")
for key, value in dict1.items():
        if value == 'land':
            print(key)
```


```python
# Data Structures, Exercise -4
"""
Remember list,set,dictionary are mutable and tuple is immutable list,tuple elements can be reached by index
for dictionary it is not an option to reach by index the element key has to be known to reach
and for set the items cannot be reached directly but it is possible to iterate.

print the lengths of list1,tuple1,set1,dict1
print the first element of list1 and tuple1
print the value of lion key of dict1
change the 2nd position element of list1 to "rabbit"
try to change the 2nd position element of the tuple to "rabbit" and explain what happened.
add "monkey" to list1
remove "rabbit" from list1
in dict1 the number of feet is written as value to each animal the fixh has wrong value just fix it.

"""
list1 = ["lion", "monkey", "dog","fish"]
tuple1 = ("lion", "monkey", "dog","fish")
set1 = {"lion", "monkey", "dog","fish"}
dict1 = {"lion":4, "monkey":2, "dog":4,"fish":2}

# print the lengths of list1,tuple1,set1,dict1
print( f'''The length of lsit1 is {len(list1)}.
The length of tuple1 is {len(tuple1)}.
The length of set1 is {len(set1)}.
The length of dict1 is {len(dict1)}.''')
print()
# print the first element of list1 and tuple1
print(f'first element of list1 is {list1[0]}, first elemnet of tuple1 is {tuple1[0]}')
print()
# print the value of lion key of dict1
print(f"lion key value is {dict1['lion']}")
print()
# change the 2nd position element of list1 to "rabbit"
print(list1)
list1[1] = 'rabbit'
# after adding 'rabbit'
print(list1)
print('\n ---try to change the 2nd position element of the tuple to "rabbit" and explain what happened.--- \n')
try:
    tuple[1] = 'rabbit'
except TypeError:
    print(" 'object does not support item assignment', because the tuple is immuatable.  \n")
    
# add "monkey" to list1
print(list1) # before adding the monkey 
list1.append('monkey')
print(list1, '\n') # after adding the monkey 
# remove "rabbit" from list1
list1.remove('rabbit')
print(list1, '\n')
dict1['fish'] = 0
print(dict1)

```
