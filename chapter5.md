---
title: 'Getting Started in Python Exercises '
description: ''
---

## 5.1. Revising lists

```yaml
type: NormalExercise
key: 26ac9314b6
xp: 100
```



`@instructions`
Write a program that takes a list of numbers _input_list_ (for example, input_list = [5, 10, 15, 20, 25]) and makes a new list _final_list_ of only the first and last elements of the given list.

`@hint`


`@pre_exercise_code`
```{python}
import numpy as np
np.random.seed(200)
input_list = list(np.random.normal(300, 150, (150)))
```

`@sample_code`
```{python}
# input_list is already loaded in the console
print(input_list)

# create final_list

# print the final_list
print(final_list)
```

`@solution`
```{python}
# input_list is already loaded in the console
print(input_list)

# create final_list
final_list = [input_list[0], input_list[-1]]

# print the final_list
print(final_list)
```

`@sct`
```{python}
Ex().check_object('input_list').has_equal_value()
Ex().check_object('final_list').has_equal_value()
Ex().has_equal_output()
```
