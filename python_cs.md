# Python

#### This cheat sheet is based on the CS50P lectures, 2023.03.30

types
``` go
string
int
float
double
```

get user input and print it
```go
name = input("What is your name?")
print("My name is", name)
```
### strings
```go
# Ask the user for their name
name = input("What's your name? ")

# Remove whitespace from the str
name = name.strip()

# Capitalize the first letter of each word
name = name.title()

```
put together
```go
# Remove whitespace from the str and capitalize the first letter of each word
name = name.strip().title()
OR
# Ask the user for their name, remove whitespace from the str and capitalize the first letter of each word
name = input("What's your name? ").strip().title()

```

### integers
ganze zahlen, auch negativ
```go
x = int(input("What's x? "))
y = int(input("What's y? "))
print(x + y)
```

### float
Dezimalzahlen, auch negati
```go
x = float(input("What's x? "))
z = round(x + y)
z = x / y
z = round(x / y, 2)

#formatt the float to xx.xx
print(f"{z:.2f}")
```

### functions
```go
#Define your own funtion
def hello(name):
  text = "Hello, " + name
  print(text)
  
#Defin function with return value
def get_name():
  name = input("What is your name?")
  return name
  
#Call funtion
hello("Benni")
get_name()
```
### if, else, elif
```go
if x < y:
    print("x is less than y")
elif x > y:
    print("x is greater than y")
else:
    print("x is equal to y")
```
### or, and
```go
if x < y or x > y: ...
if x != y: ...
if score >= 90 and score <= 100: ...
```
### Modulo
```go

```

