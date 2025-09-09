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
