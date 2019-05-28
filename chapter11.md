---
title: '12. Writing your own functions'
description: ""
---

## 12.1. Summing up in list ex.

```yaml
type: NormalExercise
key: 27c62a8487
xp: 100
```



`@instructions`
Sum up all the negative numbers in a list.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
import random

def sumNegative(lst):
    sum = 0
    for e in lst:
        if e < 0:
            sum = sum + e
    return sum

lst = []
for i in range(100):
    lst.append(random.randrange(-1000, 1000))

print(sumNegative(lst))
```

`@sct`
```{python}

```

---

## Pi Leibniz ex.

```yaml
type: NormalExercise
key: 629d28cf07
xp: 100
```



`@instructions`
Write a function called myPi that will return an approximation of PI (3.14159…). Use the Leibniz approximation.

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

## Pi Madhava ex.

```yaml
type: NormalExercise
key: 3462763919
xp: 100
```



`@instructions`
Write a function called myPi that will return an approximation of PI (3.14159…). Use the Madhava approximation.

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

## Leap years ex.

```yaml
type: NormalExercise
key: 2731a122fd
xp: 100
```



`@instructions`
3 criteria must be taken into account to identify leap years:
1. The year is evenly divisible by 4;
2. If the year can be evenly divided by 100, it is NOT a leap year, unless;
3. The year is also evenly divisible by 400. Then it is a leap year.
Write a function that takes a year as a parameter and returns True if the year is a leap year, False otherwise.

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

## Caesar cipher ex.

```yaml
type: NormalExercise
key: 642007862b
xp: 100
```



`@instructions`
Write a function called rot13 that uses the Caesar cipher to encrypt a message. The Caesar cipher works like a substitution cipher but each character is replaced by the character 13 characters to ‘its right’ in the alphabet. So for example the letter a becomes the letter n. If a letter is past the middle of the alphabet then the counting wraps around to the letter a again, so n becomes a, o becomes b and so on.

`@hint`
Hint:Whenever you talk about things wrapping around its a good idea to think of modulo arithmetic.

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

## List summing up ex.

```yaml
type: NormalExercise
key: 6525edf3e6
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

---

## List average ex.

```yaml
type: NormalExercise
key: 9751b02f15
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
