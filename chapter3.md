---
title: '3. Functions and Packages'
description: ""
---

## 3.1. Summing up in list ex.

```yaml
type: NormalExercise
key: b4b29bbd3d
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

## 3.1. Pythogenrean Theorem ex.

```yaml
type: NormalExercise
key: db0cf5b422
xp: 100
```



`@instructions`
The Pythagorean Theorem tells us that the length of the hypotenuse of a right triangle is related to the lengths of the other two sides. Look through the math module and see if you can find a function that will compute this relationship for you. Once you find it, write a short program to try it out.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
import math

side1 = 3
side2 = 4
hypotenuse = math.hypot(side1,side2)
print(hypotenuse)
```

`@sct`
```{python}

```
