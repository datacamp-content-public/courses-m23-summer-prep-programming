---
title: '13. ACCUMULATOR PATTERN'
description: ""
---

## Revisiting functions Theory!

```yaml
type: NormalExercise
key: b4e726e6f0
xp: 100
```

An assignment statement in a function creates a _local_ variable for the variable on the left hand side of the assignment operator. It is called local because this variable only exists _inside the function_ and you **cannot** use it outside. For example, consider the square function:
```
1   def square(x):
2	    y = x * x
3	    return y
4	
5	z = square(10)
6	print(y)
```
Do you think the code will output any error message?? Try it yourself.

Source: [here](https://interactivepython.org/courselib/static/thinkcspy/Functions/TheAccumulatorPattern.html)

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
def square(x):
  y = x * x
  return y

z = square(10)
print(y)
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Calc number of characters/numbers in string

```yaml
type: NormalExercise
key: cea0a9a0e6
xp: 100
```



`@instructions`
Write a Python program that accepts a string and calculate the number of digits and letters.
```
Sample Data : Python 3.2
Expected Output :
Letters 6 
Digits 2
```

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

## 13.1. List average ex.

```yaml
type: NormalExercise
key: 18523bbcd0
xp: 100
```



`@instructions`
Create a list containing 100 random integers between 0 and 1000 (use iteration, append, and the random module). Write a function called average that will take the list as a parameter and return the average.

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

## 13.  List summing up ex.

```yaml
type: NormalExercise
key: 0e436c965e
xp: 100
```



`@instructions`
Sum up all the even numbers in a list.

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
