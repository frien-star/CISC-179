# Lab-2c
``` python
# <class 'int'>
# <class 'float'>
1000.0
# Hello World
# Single quote can also be used

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
