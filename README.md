# Lua Basics
## Variables
Variables are used to store values. They have a name and a value, and are created simply by assigning a value to them. For example:
```
age = 30
weight = 75.5
name = "John"
```
## Data types
Lua has several data types, including numbers, strings, Booleans, and tables. Numbers can be integers or floating-point values, and can be written with or without a decimal point. Strings are sequences of characters, and are written using single or double quotes. Booleans represent true or false values. Tables are data structures that can store any type of value.

## Operators
Lua supports a variety of operators, such as arithmetic operators (e.g., +, -, *, /), relational operators (e.g., <, >, ==, ~=), and logical operators (e.g., and, or, not). These operators can be used to perform calculations and compare values.

## Control structures
Lua has several control structures that allow you to control the flow of your program. These include if statements, for loops, and while loops. For example:
```
if age > 18 then
  print("You are an adult.")
else
  print("You are a minor.")
end
```
```
for i = 1, 10 do
  print(i)
end
```
```
local i = 1
while i <= 10 do
  print(i)
  i = i + 1
end
```
## Functions
Functions are blocks of code that can be called from other parts of your program. They can take parameters and return a value. For example:
```
function add(x, y)
  return x + y
end

local result = add(2, 3)
print(result) -- prints 5
```
These are just a few of the basics of Lua. There are many other concepts to learn, such as metatables, coroutines, and more. I recommend finding a good tutorial or textbook to learn more about the language.
