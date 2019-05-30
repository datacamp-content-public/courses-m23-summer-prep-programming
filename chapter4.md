---
title: 'Numpy Exercises '
description: ""
---

## 4.1. Searching for function ex.

```yaml
type: MultipleChoiceExercise
key: ea732d05f5
xp: 50
```

Numpy arrays are more powerful than lists. There is large amounts of functions that can be used to perform special operations. To find the function, that we need, we use online documentation and Google/Bing/Ecosia/Baidu... 

Using documentation and search engines find the function to remove all items present in array _b_ from array _a_.
```
import numpy as np
a = np.array([1,2,3,4,5])
b = np.array([5,6,7,8,9])
```
Which function should you use?

`@possible_answers`
- np.diff(a,b)
- np.zeros(a,b)
- [np.setdiff1d(a,b)]
- np.removefrom(a,b)
- np.union(a,b)

`@hint`
Did you try to search online?

`@pre_exercise_code`
```{python}
import numpy as np

a = np.array([1,2,3,4,5])
b = np.array([5,6,7,8,9])
```

`@sct`
```{python}
msg1 = "No, np.diff(...) takes diffrent arguments and does diffrent things."
msg2 = "No, np.zeros(...) is generates array full of zeros. Try google more."
msg3 = "That's correct!"
msg4 = "No. Try google more, this function does not exist."
msg5 = "No. Try read the documentation."

Ex().has_chosen(correct=3, msgs = [msg1, msg2, msg3, msg4, msg5])
```

---

## 4.2. Counting elements ex.

```yaml
type: NormalExercise
key: 3a5c1c0d76
xp: 100
```

Numpy arrays are more powerful than lists. There is large amounts of functions that can be used to perform special operations.

`@instructions`
In this task, there is loaded huge array _prices_, which contains prices of all products in large store. Your task is to write code, which calculates, how many items in the store has price less than 10$.

`@hint`
Try to re-watch the Numpy chapter.

`@pre_exercise_code`
```{python}
import numpy as np
np.random.seed(200)
prices = np.random.normal(30, 15, (2500))
```

`@sample_code`
```{python}
import numpy as np
# prices array is already loaded

number_of_cheap_products = _____
print(number_of_cheap_products)

```

`@solution`
```{python}
import numpy as np
# prices array is already loaded

number_of_cheap_products =  len(prices[prices < 10])
print(number_of_cheap_products)
```

`@sct`
```{python}
Ex().has_output("210", pattern = False)
```
