# Lab-2c
``` python
# <class 'int'>
# <class 'float'>
1000.0
# Hello World
# Single quote can also be used
```
## Variable Memory Usage
``` python
var1 = 10
# Check the memory address of var1 by using the following statement
print(hex(id(var1)))

# Reassigning value to var1
var1 = 100
# Check the memory address of var1 again
print(hex(id(var1)))
```
Output:   
0x7ff9b86174c8   
0x7ff9b8618008   
Explanation: Rewriting var1 with a new value did not erase the original it was assigned. There is one memory slot for 10- another for 100
``` python
var2 = 100
# Write your print statement
# Check the memory address of var2.
print(hex(id(var2)))
# Did the Python interpreter assign a new memory address or reuse the existing one?
```
Output:   
0x7ff9cc0374c8   
0x7ff9cc038008   
0x7ff9cc038008   
An existing memory address was used instead.

## Memory Mapping
``` python
str1 = "Hello"
str2 = "World"
# Find out the memory addresses of each character in str1 and str2.
# The following is the example
print('\n')
print(" H =", hex(id(str1[0])), '\n',"E =", hex(id(str1[1])))  # where 0 is the first index and 1 is the second index
# Use the same method as described above to find the addresses of additional characters and complete the table below.

# Daniel's coding: Hello
print(" L =",hex(id(str1[2])), '\n L =', hex(id(str1[3])),'\n O =', hex(id(str1[4])))
# Daniel's coding: World
print("\n W =", hex(id(str2[0])), '\n O =', hex(id(str2[1])), '\n R =', hex(id(str2[2])), '\n L =', hex(id(str2[3])), '\n D =', hex(id(str2[4])))
```
Output:   
H = 0x7ff9aaf46b30    
 E = 0x7ff9aaf470a0   
 L = 0x7ff9aaf471f0    
 L = 0x7ff9aaf471f0    
 O = 0x7ff9aaf47280   

 W = 0x7ff9aaf46e00    
 O = 0x7ff9aaf47280    
 R = 0x7ff9aaf47310    
 L = 0x7ff9aaf471f0    
 D = 0x7ff9aaf47070   
## Problem Solving
* dogcat
* "the dog chases the cat"
* dogdogdogdog
```python
# Problem Solving
x = 50
print(x + 1)
```
## Troubleshooting
a. Is true- variable hello is assigned as a string   
b. True- '_' is an exception as a speicial character   
c. False- Exclamation marks are not an exception to special characters   
d. False- cannot use keywords   
e. False- cannot use keywords
