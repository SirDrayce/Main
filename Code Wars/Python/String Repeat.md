# [String Repeat](https://www.codewars.com/kata/57a0e5c372292dd76d000d7e)

### Kyu:  8

### Instructions:  
Write a function called repeat_str which repeats the given string src exactly count times.
```
repeatStr(6, "I") // "IIIIII"
repeatStr(5, "Hello") // "HelloHelloHelloHelloHello"
```

## Solution

```
def repeat_str(repeat, string):
    return repeat * string
```
