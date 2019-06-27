---
title: 'Logic, Control Flow and Filtering Exercises '
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

## 9.2 Searching for best study place

```yaml
type: NormalExercise
key: d1d43b4324
xp: 100
```

To make the best decision in the shortest time, humans use different frameworks and heuristics. In this part we will look at decision trees based on real-life scenarios.

The first exercise is part of your daily routine on Minerva. Weather in San Francisco is mostly without changes for weeks. But even slight change can influence location, where you will spend your day.

![Decision Tree Diagram](https://cdn1.imggmi.com/uploads/2019/5/29/9b85df14a25542f40bbdb39b04909127-full.png)

`@instructions`
Based on weather you can go:

Sunny day:
-Study outside

Rain:
60 % probability of studying in Res Hall
40 % probability of studying in nearby Cafe

Storm:
-Study in Res hall


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
