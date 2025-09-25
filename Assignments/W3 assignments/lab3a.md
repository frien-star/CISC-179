```python
# 1.
char = input("Type a single character ")
ascii_conv = ord(char)
print("The ASCII value of", char, "is", ascii_conv)
# Comment: I didn't really know if it was possible to answer this problem
# based on what I was currently taught at this point of the course.
# As you can see, I searched and used a command that was not
# previously taught to me. While it does technically allow me
# to index every character via a prompt what their ASCII value is...
# I feel I missed the point of doing this question.

# 5a.
num_1 = int(input("Select a first number "))
num_2 = int(input("Select a second number "))
num_3 = int(input("Select a third number "))

if(num_1 > num_2 and num_1 > num_3):
    print(num_1, "is the greatest integer")
if(num_2 > num_1 and num_2 > num_3):
    print(num_2, "is the greatest integer")
if(num_3 > num_2 and num_3 > num_1):
    print(num_3, "is the greatest integer")

# 5b.
# Method one:
M1 = int(input("Pick an integer: "))
if(M1 % 2 == 0):
    print("This is an even integer!")
else: print("This is an odd integer!")

# Method Two:
M2 = int(input("Pick another integer!: "))
if(M2 % 2 ):
    print("This is an odd integer!")
else: print("This is an even integer!")

# Method Three:
M3 = int(input("Pick yet another integer!: "))
if(M3 / 2 ):
    print("This is an even integer!")
else: print("This is an odd integer!")

# 5c.
Grade = int(input("Enter your grade number: "))
if (Grade >= 90): # Checks if it is higher or equal to 90
    print("A. Work of genuinely supperior quality")
elif (Grade >= 80 and Grade <= 89):
    print("B. Passing performance falls approximately in the upper distribution ")
elif (Grade >= 71 and Grade <= 79):
    print("C. Passing performance falls aproximately in the center")
elif (Grade >= 65 and Grade <= 70):
    print("Passing performance falls approximately in the lower distribution of passing grades")
else: print("Failing performance that does not satisfy the basic requirements of the course and needs to be improved in significant ways.")

# 5d.


# 5e.
EoO = int(input("Enter your number "))
zero = 0
result = EoO & zero
if (result):
    print("even")
else:
    print("odd")

# 6.
name = input("What's your name? ")
time = int(input("What time is it? "))

if (time < 1200):
    print("Hi "+name + ", good morning!")
elif (time < 1800): # if the first condition fails
    print("Hi "+name + ", good afternoon!")
elif (time > 1800): # if all the second condition fails
    print("Hi "+name + ", good evening!")
else: print("Good Bye") # if all other conditions fail

# 7. output is "one"
x = 1
y = 1.0
z = "1"

if x == y:
    print("one")
if y == int(z):
    print("two")
elif x == y:
    print("three")
else:
    print("four")
```
