---
title: '9. Logic, Control Flow and Filtering'
description: ""
---

## 9.1. Evaluating expressions ex.

```yaml
type: NormalExercise
key: 45c18fcf69
xp: 100
```

First think and then experiment in the console: 

What do these expressions evaluate to?
3 == 3
3 != 3
3 >= 4
not (3 < 4)

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Insert exercise title here

```yaml
type: NormalExercise
key: 267f407332
xp: 100
```

Programming is a lot of googling and searching! 

For this exercise try researching how you can prompt user to input some data. DO NOT BE AFRAID to ask Google questions. Rumors are that it knows everything. 

Also, did you know that there is 'google' for programmers. Check it out too! [here](https://stackoverflow.com )


`@instructions`
Write a program that: 
1) asks user to input a number
2) then evaluates whether that number is even or odd.

`@hint`
1) https://stackoverflow.com
2) % and https://stackoverflow.com

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}

num = int(input("Enter a number: "))
mod = num % 2
if mod > 0:
    print("This is an odd number.")
else:
    print("This is an even number.")
	
```

`@sct`
```{python}

```
