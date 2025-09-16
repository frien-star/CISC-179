## Decision statements   
Order of priority:   
  ### if   
Every decision statement must involve if first
  ### elif   
Must be used between decision statements 
  ### else   
Always used in the last branch of a decision statement   
### Example:
``` python
today = input("What is today?")
if (today == "Friday"):
    print("Go for a dinnder")
  elif(today == "Saturday"):
    print("Get lazy!")
else: print("Not a day!")
```
## Comparison Operators
May be used to further modify decision statments.   
List of operators:   
* ```python
  # less than:
  <
  ```
* ```python
  # Less than or equal:
  <=
  ```
* ``` python
  # Greater than:
  >
  ```
* ``` python
  # Greater than or equal:
  >= 
  ```

* ```python
  # Equal:
  == 
  ```
* ``` python
  # Not equal:
  !=
  ```
  Examples:
  ```python
  # Comparisons just by themselves will print a true or false statement on output:
  2 > 5 # Prints true
  2 < 5 # Prints false

  x = int(input("designate a number: "))
  if(x > 5):
    elif(x >= 10)
  else("this should not be possible!")
  ```
  ## Logical Operators
  * ### 'And' Statements
  * ### 'or' Statements
  * ### 'not' Statements
  Logical operators do not need to be capitalized
  ``` python
  # and: Both expressions must be true to output true, otherwise, false...
  10 > 4 and 50 < 100 # true

  # or: Both expressions need to be false to output false
  # if one expression or the other is true, the statement outputs true...
  10 > 4 or 50 > 100 # true

  # not: Inverts the results
  10 > 4 # True
  not(10 > 4) # Now false
  ```
