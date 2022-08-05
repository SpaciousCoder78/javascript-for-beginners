# javascript-for-beginners
A javascript tutorial for beginners

# Contents
- [Introduction](https://github.com/SpaciousCoder78/javascript-for-beginners/blob/main/README.md#introduction) [](url)
- [Hello World Program](https://github.com/SpaciousCoder78/javascript-for-beginners#creating-a-hello-world-program) [](url)
- [Comments](https://github.com/SpaciousCoder78/javascript-for-beginners#comments) [](url)
- [Variables](https://github.com/SpaciousCoder78/javascript-for-beginners#variables) [](url)
- [Constants](https://github.com/SpaciousCoder78/javascript-for-beginners/blob/main/README.md#constants) [](url)
- [String Indexing](https://github.com/SpaciousCoder78/javascript-for-beginners/blob/main/README.md#string-indexing) [](url)
- [String Methods](https://github.com/SpaciousCoder78/javascript-for-beginners/blob/main/README.md#string-methods) [](url)
- [String Concatentation](https://github.com/SpaciousCoder78/javascript-for-beginners/blob/main/README.md#string-concatenation) [](url)
- [If else condition](https://github.com/SpaciousCoder78/javascript-for-beginners/blob/main/README.md#if-else-condition) [](url)
- [Nested if condition](https://github.com/SpaciousCoder78/javascript-for-beginners/blob/main/README.md#nested-if-condition) [](url)
- [Else if condition](https://github.com/SpaciousCoder78/javascript-for-beginners/blob/main/README.md#nested-if-condition) [](url)
- [Switch Statement](https://github.com/SpaciousCoder78/javascript-for-beginners/tree/main#switch-statement) [](url)
- [While loop](https://github.com/SpaciousCoder78/javascript-for-beginners/tree/main#while-loop) [](url)
- [For loop]

# Introduction


Javascript is a client side high level, just in time compiled programming language which is widely used on the internet alongside HTML and CSS. 
Almost every modern browser can natively run Javascript.
You can run javascript code in your browser’s console.
You can access your browser’s console by hitting the F12 key.
 
![image](https://user-images.githubusercontent.com/88923986/174623199-e18ceb0f-19a4-4da3-b4f1-e4d203dcc7b8.png)

## Writing javascript code within HTML code
You can write javascript code within your HTML code by using <script> tag. All the javascript code goes within the tags.
 ![image](https://user-images.githubusercontent.com/88923986/174623842-5c2a5442-5907-4889-a2ac-4e8a669f34fb.png)

 
Or you can create a separate .js file and link it in your HTML code.
 
 ![image](https://user-images.githubusercontent.com/88923986/174623896-9e2c3c88-184b-4536-a76d-9976d5611b42.png)

# Creating a hello world program
Just like in python, the length of hello world program in javascript is just one line.

![image](https://user-images.githubusercontent.com/88923986/174624105-8dcd4431-e796-43a2-a3f0-b60f7d25467f.png)

# Comments

Comments are used for documentation purposes and are not executed when the program runs.
In Javascript you can add comments using //

 ![image](https://user-images.githubusercontent.com/88923986/175223617-0474e3e2-bb23-463b-891d-3e99171dfeea.png)

# Variables
Variables can store some information and the stored information can be changed at a later time
## Declaring a variable
We can declare a variable by typing “var variablename=value;”
We can also use 'let' instead of var
 
![image](https://user-images.githubusercontent.com/88923986/175541294-1fbe79f9-729a-4f99-9c81-99a8ba84a4ca.png)
## Using a variable
We can use a variable anywhere by mentioning it. 

![image](https://user-images.githubusercontent.com/88923986/175541410-59342ed8-9cdc-4150-9758-a769acf28e50.png)
## Changing value of a variable
We can change the value of a variable by redefining it. We do not have to mention var while redefining a variable.

![image](https://user-images.githubusercontent.com/88923986/175541645-d3e07a7c-0afe-4195-8e61-0e858e18194e.png)

## Rules for naming a variable

We need to follow certain rules while naming variables. Not following the rules will get us some errors.

Rules:
- Variable cannot start with a number(eg. 1value)
- We can use only underscore(_) or dollarsign($) in the beginning of a variable name
- We cannot use spaces while naming variables
 
# Constants
Constants, unlike variables, have a fixed value, which means that the value of a constant cannot be changed.

## Declaring a constant
We have to use 'const' before defining a constant
 
![image](https://user-images.githubusercontent.com/88923986/176846631-2739e3bc-e034-48b9-8665-ef827681f666.png)
 
# String Indexing
 When we declare a string, we can access individual characters of the string using index numbers. Index numbers start from zero.
 
![image](https://user-images.githubusercontent.com/88923986/176847596-4e755718-0b94-49e9-ae73-66434c9859b1.png)

## Printing a character of the string

We can print a character of the string using "variablename[indexnumber]"

![image](https://user-images.githubusercontent.com/88923986/176848471-c5f07feb-529c-41c0-9ac5-79514c82d09e.png)

## Length of the string
 
We can find the length of the string using "variablename.length"
 
![image](https://user-images.githubusercontent.com/88923986/176848785-3a4668eb-c5ac-425a-a717-9164fe661f22.png)
 
## Last Index of a string

We can find the last index of a string using "variablename.length-1"

![image](https://user-images.githubusercontent.com/88923986/176849133-2bd3c338-5be5-4c74-80cf-7c853dac6b06.png)
 
# String Methods
When dealing with strings, we can use methods like trim(), toUpperCase(), toLowercase() and string slicing.

## trim() method
 This method is used to remove whitespaces in a string
 
 ![image](https://user-images.githubusercontent.com/88923986/176851495-735d4c6d-716e-43fd-bbc4-86671b761620.png)

## toUpperCase() Method
 This method changes the text in the string to uppercase 
 
 ![image](https://user-images.githubusercontent.com/88923986/176852687-ac4fe6d5-312d-4a90-bab6-828c1f3dfada.png)

## toLowerCase() Method
 This method changes the text in the string to lowercase
 
 ![image](https://user-images.githubusercontent.com/88923986/176852980-a1367d43-40ee-4d68-b39b-4b1c8b9f4431.png)

## String Slicing
 We can slice a string by mentioning parameters using slice() function
 
 ![image](https://user-images.githubusercontent.com/88923986/176853669-db821336-d336-4317-8edd-6a3d99bbf1ba.png)
 
## typeof operator
 We can use typeof operator to find the datatype of a variable
 
 ![image](https://user-images.githubusercontent.com/88923986/176859090-42436b1a-77f5-4a48-b924-553427cefaa9.png)

## Converting number to string
 We can convert a number to string by concatenating it with ""
 
 ![image](https://user-images.githubusercontent.com/88923986/176860008-1c9549e0-b5c3-42b7-8a7d-628f91032b1c.png)

 
## Converting string to number
 
We can convert a string to number by adding a plus sign before the string
 
 ![image](https://user-images.githubusercontent.com/88923986/176860314-eb5efdaf-0453-4c74-947e-77645ad6a9d4.png)
 
# String Concatenation 
 
 We can concatenate (add) two strings by using the plus(+) sign between the two strings
 
 ![image](https://user-images.githubusercontent.com/88923986/176861265-b6e6c177-fd20-4e12-9e31-bbb17a87676d.png)
 
# If else condition
We can use if else condition using relational operators like >, <, =, ==, != etc

![image](https://user-images.githubusercontent.com/88923986/179539302-4052f5de-b62b-476e-8260-5682e068d0ab.png)
![image](https://user-images.githubusercontent.com/88923986/179539747-db7707fd-d6b7-41aa-b24d-199bfc139c90.png)

# Nested if condition

![image](https://user-images.githubusercontent.com/88923986/183103710-ccc8ffda-f30e-43bf-92e9-cc4612b97d45.png)

# Else if condition

![image](https://user-images.githubusercontent.com/88923986/183104433-86d1c1b4-8ebc-46e1-904f-ea7e45c1ddf2.png)
                                                                   
                                                                   
# Switch Statement
Switch statement can be used instead of nested if else statements

![image](https://user-images.githubusercontent.com/88923986/183106502-155ee847-18c1-43cc-a8a1-619e88fe7e5c.png)

                                                                   
                                                                   
# While loop
                                                                   
![image](https://user-images.githubusercontent.com/88923986/183109366-424c3b49-e557-4a7a-909c-fc68b6131b27.png)
                                                                   
# For loop
                                                                   
![image](https://user-images.githubusercontent.com/88923986/183111101-0ffba387-7251-426a-a21f-825a66f64533.png)

                                                                   
                                                                   








 

 





