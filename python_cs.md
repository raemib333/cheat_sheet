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
```go
x = int(input("What's x? "))
y = int(input("What's y? "))
print(x + y)
```

