# Lab-2b
## 1. Literals
```Python
print(5 + 2 - 2)
# ______________________
print(5 / 2)
# ______________________
print(6 // 2) # // integer division
# ______________________
print(2. * 3)
# ______________________
print(2 < 4)
# ______________________
print(2 >= 2)
# ______________________
print("Hello"+"World")
# ______________________
print("bla" * 3)
# ______________________
print(2 * 3 ** 3)
# ______________________
print(5 * 25 // 13 + 100 / 2 % 13 // 2)
# arithmetic proof:
# 125 // 13 + 100 / 2 % 13 // 2
# 9 + 100 / 2 % 13 // 2
# 9 + 50 % 13 // 2
# 9 + 8 // 2
# 9 + 4
# 13
# End of proof
# ______________________
print(2 * 3 % 5)
# ______________________
print((2 % -4), (2 % 4), (2 ** 3 ** 2))
# ______________________
```
### 1.Literals Answers
* 5
* 2.5
* 3
* 6.0
* True
* True
* "HelloWorld"
* "bla bla bla"
* 54
* 13
* 1
* 61
## 2. Datatype
```python
  type("Hello")
# ______________________
type(1+"2")
# ______________________
type(1.)
# ______________________
type('A')
# ______________________
type(500)
# ______________________
type(True)
# ______________________
type("False")
# ______________________
```
### 2. Datatype Answers
* String
* Error occurs- two types- int and string
* float
* int
* boolean
* string disguised as a boolean

## 3. Operator Precedence
3a. -2 + 2 * 4 ** 2 / 2 // 2 - 4 * 4 % 10   
3b. Proof:   
* -2 + 2 * 16 / 2 // 2 - 4 * 4 % 10
* -2 + 32 / 2 // 2 - 4 * 4 % 10
* -2 + 16 // 2 - 4 * 4 % 10
* -2 + 8 - 4 * 4 % 10
* -2 + 8 - 16 % 10
* -2 + 8 - 6
* 6 - 6
* 0   
3c. Verified:   
```Python
print(-2 + 2 * 4 ** 2 / 2 // 2 - 4 * 4 % 10)
```
## Challenges 
* Processing and calculating without python what each arithmetic solution was. It was especially hard with the longer sequences, where I would reach a completely different answer than what python had calculated.
* Some words like- "Literals" or "operators" and any other terminology I was umfamiliar with threw me off intially. I'm still somewhat unclear what some of them are even after looking it up.
