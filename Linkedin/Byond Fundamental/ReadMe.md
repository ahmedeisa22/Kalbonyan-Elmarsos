# what will learn in this course ?
  1. programming patterns and syntax 
  2. basis like debugging and program plaining
  3. oop and memory management

   ---
   ## Collection
**Collection**: Group multiple items together and storing them with a single name, called a variable

**Advanges of collections**:
* Uses your code structure to indicate that multiple piece of data are related.
* Avoid creation a potentially huge number of variables to track with in our code.
* Offer simplified eyntax.
  
**List**: simple collection that groups pieces of data together in a certin order and assign the collections a name. -> **this is a name of collection in python**

```py
guests = [
  'maria',
  'dola',
  'eisa'
]
```

**Dictionary** is the same as list but with a lable for each item.

```py
food = {
  'appetizers':'humans',
  'entree':'gyro wraps',
  'dessert':'baklava'
}
```
notice that we use differnt carely bracess {} but list use []


Access list  => name + [inedx]   inedex start 0 by default  

ex
` print(guests[0])` will print maria

acces Dictionary => name + [name]

ex
print(food['appetizers']) will print humans

**in python** you can use list with any data type (string , integer , boolean)

**python list:**
```py
[
  'avacado', # string
  15, #integer
  True # bool
]
```
but may other languages require that all type of collection must be the same data type like **c++ or java**

**c++ list**:
```c++
[
  'ahmed'.
  '15',
  'eisa'
] // thees are all string
```
**in python the data alos can change you can add or move items**

```py
[
  'avacado', # string
  15, #integer
  True # bool
]
```` 
move item :
```py
[
  'avacado', # string
  15, #integer
  False # bool
]
```` 

**mutable**: can be changed
**imutable** cann't be changed

**Tuple**: this is a data in python and use **()** not [] or {}    **imutable list**

| python | c++,java |
| :----: | :------: |
|  list  |  array   |


**Dictionary**:
* Associative array
* map
* table
---


## Iteration
need start point and end point

**infinteloop** occur when you didn't put endpoint or something wrong means freez the programs

this is loop in python
```py
spices = [
    'salt',
    'pepper',
    'cumin',
    'turmeric',
]
for spice in spices:
    print(spice)
print('No more boring omelettes!') #bact ident 
```
spice : is avariable name that we can use to itrate to reffernce the current value
in => is keyword idicates that what follows is the set of valuse that we want to itrate.

---
## External code

 developers often create code to accomplish basic tasks and then share it with the developer community for free. Instead of reinventing the wheel.

 ##### Shared Code:

 * **module:** python file that contain code, like vairables and functions.

* **package or library:** using multiple modules together so they are distributed and used in a group.
* **framework:** when a code is not used together but used in a specific way.

**import :** keyword in python let's the python complier know that i want reference code in a seprate file.

the different between framework and library;

library gives you set of tools 
framework define how you should accomplish a task

in **python** popular library is:
* TensFrow
* Pandas for machine task
* NumPy Socpy is a mathmatic operation

**python framework**
* Djano
* flask
which are both use for web

**JavaScript Library**
* Lodash
* jQuery

**JavaScript Framework**
* React 
* Angular
* Vue
---
## string
is a collection of charachers

**concatenation** when multiple strings are combined together
into a single string

EX:
```py
string name = 'ahmed'
print("my name is:" + name)
```
there are some functions treat with the string

* string.capitalize() => capital the first letter of string

EX
```py
name = ahmed
print(name.capitalize())

>>> Ahmed
```
* string.find() => is this inside the string or not if true return index location
  **Slice:** Getting part of a string value
* string[beign:end] => select in string

**Regular Expression:** allow you to description of a pattern that you want to march also known as Regex contain from:
* numbers
* character
* letter
  
for intstance:
- / hello/ -> a specific word 
- \d -> a character
- \w -> word
- . -> any char
- (+)) -> one
- (*)-> 0 or more
- ? -> 0 or 1

---
## plainnig a program
 learn more about the available syntax and structures, you'll discover multiple ways to accomplish the same task. And you'll have to choose among them and decide the best way to build the program you're trying to create. And just like with tools, there are some constructions to avoid, some that are accepted standards and some that are totally up to your preference.

 **Style Guide** Documentation on approaches to code.

 for python => PEP 8 is short for = Python Enhancement proposal number 8.
 other languages have their guide style

 python > google giude
 javaScript > Aibnb js Style Guide()

 **PseudoCode** Writting a description of what're trying to do using plain language.

 if you write code before pesudocode like you booking hotel before plainnig to travel.
 
 ---
## I/o > INPUT / OUYPUT
---
## Debugging
bugs : are the wrong or something that happen and stop program

**debug:** identifying and fixing bugs.

there  are  three main of bugs:
1. Syntax error
2. Run-time-error
3. Logic error
   
   **Syntax error:** code that doesn't match the rule of the language.
   EX:
   ```py
     if tem > 50  #no colon
        do something
   ```
   **Run-time-error:** in call a function that is ever defined it's not an obvious until code run

**Logic error** the code runs but doesn't excute the code that i expect

Ex
```py
  i = 10
  while i < 0:
    print("eisa")
    i+=1
  ```
**IDEs** short for > Integrated Development Enviroments

**Advantges**
* Syntax Highlighting
* AutoCompelete
* Linting -> you write the name wrong and this make red line under it.
  



