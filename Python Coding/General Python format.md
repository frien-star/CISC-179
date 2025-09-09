  ### Semicolons
* Python does not include semicolons at the end of their lines.
### Data Memory
Variables are stored in slots. Variables with the same value refer to the original slot. Variables rewritten with a new value does not overwrite the original slot it was stored in- a new slot is written for the new value.   
To check the memory address of a variable:
* ```python
  print(hex(id(the variable's name)))
  ```
