- Comments
- pseudocode
docs.python.org

```
# Say hell to user
print("hello,", name, sep = ' ')


# Say hell to user
print("hello,", end = ' ')
print(name)
```

- Parameters 
Sep, End - NamedParameter

- Format string

```
# Say hell to user
print(f"hello, {name}")
```

```
# Capitalize name
# name = name.capitalize()
name = name.title()
```

Chaining command
```
# Remove whitespaces from str and capitalize
name = name.strip().title()
```


- int

+ add, - subtract ,  * multiply, / divide, % modulo

interactive mode

```
 $ python
Python 3.12.1 (main, Nov 27 2025, 10:47:52) [GCC 13.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 1 + 1
2
>>> print("hello, world")
hello, world
>>> 
```

Calculator
```
x = input("What's x? ")
y = input("What's y? ")

z = int(x) + int(y) 

print(z)
```
 
 Restructured
 ```
x = int(input("What's x? "))
y = int(input("What's y? "))

print(x + y)
 ```

- float

round()

```
x = float(input("What's x? "))
y = float(input("What's y? "))

print(round(x + y))
```

format
```
x = float(input("What's x? "))
y = float(input("What's y? "))

z = round(x + y)

print(f"{z:,}")
```

Rounding
```
x = float(input("What's x? "))
y = float(input("What's y? "))

z = round(x / y, 2)

print(z)
```

using format string
```
x = float(input("What's x? "))
y = float(input("What's y? "))

z = x / y

print(f"{z:.3f}")
```

def # function

```
def hello(to="world"):
    print(f"hello, {to}")

hello()
name = input("What's your name? ")
hello(name)
```

main method
```
def main():
    hello()
    name = input("What's your name? ")
    hello(name)

def hello(to="world"):
    print(f"hello, {to}")

main()
```

scope

return

```
def main():
    x = int(input("What's x? "))
    print("x squared is,", square(x))

def square(x):
    return x * x

main()
```