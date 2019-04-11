# Exercise 5

## Goal: works with lists

### 5A: Create a list with: "dog", "cat", "python"

### 5B: Create a new list based on 5A: "DOG", "CAT", "PYTHON". Use the list of 5A

### 5C: Create a new list with all the values between 0 and 20 which can be devided by 3 (and remaining = 0)

### 5D: given this comprehension, remove the doubles
```
     double = [ n + m for n in range(0,5) for m in range(0,5)]
```

Hints:

* 5A: list.append
* 5B: list comprehension & upper function (```"abc".upper()```)
* 5C: list comprehension & range function + if condition
* 5C: remaining = "%"
* 5D: think of a set

## Example of list comprehension:

```
even = [ n for n in [1,2,3,4,5,6] if n % 2 == 0]
```

or all the possible pc's in NLD

```
pc = ["{}{}{}".format(n,chr(m).upper(),chr(o).upper()) for n in range(1000,9999) for m in range(97,123) for o in range(97,123)]
```
