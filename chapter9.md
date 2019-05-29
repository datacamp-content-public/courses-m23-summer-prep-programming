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

## 9.2. Does Google really know everything?

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

---

## 9.3 Searching for best study place

```yaml
type: NormalExercise
key: d1d43b4324
xp: 100
```

To make the best decision in the shortest time, humans use different frameworks and heuristics. In this part we will look at decision trees based on real-life scenarios.

The first exercise is part of your daily routine on Minerva. Weather in San Francisco is mostly without changes for weeks. But even slight change can influence location, where you will spend your day.

`@instructions`
Based on weather you can go:

Sunny day:
-Study outside

Rain:
60 % probability of studying in Res Hall
40 % probability of studying in nearby Cafe

Storm:
-Study in Res hall

![http://i64.tinypic.com/vio674.png](Decision Tree Diagram)

variable
weather contains information about tomorrow´s forecast: "sunny", "rain", "storm". Based on data provided above, write a program that prints "Outside", "Res hall", "Cafe" based on content in variable weather.

`@hint`
Library random contains function random, which generates number from 0 to 1, which can be used for generating the random choices through if statement.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
import random

# tomorrow´s weather
weather = random.choice(["sunny","rain","storm"])
print("Weather forecast for tomorrow is:", weather)

# Your code about deciding


# Print the final decision
print("You should study: ", result)

```

`@solution`
```{python}

```

`@sct`
```{python}

```
