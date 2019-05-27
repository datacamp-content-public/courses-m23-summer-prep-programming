---
title: '11. Writing your own functions'
description: ""
---

## 11.1. Summing up in list ex.

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

## Insert exercise title here

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
