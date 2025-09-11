
### Data Memory
Variables are stored in Nemory addresses. Variables with the same value will refer to the original address. Variables rewritten with a new value will not overwrite the original address it was stored in- a new address is written instead.   
* Memory addresses are usually outputted as hexadecimal.
* Variables can be assigned values or strings as needed.
To check the memory address of a variable:
* ```python
  print(hex(id(the variable's name)[Index number])) 
  ```
  * Index number: Specically indexes a character in the variable/string (Optional to include)
