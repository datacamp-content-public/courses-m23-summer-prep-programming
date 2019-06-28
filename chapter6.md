---
title: 'Loading Data in Pandas Exercises '
description: ""
---

## Pre-ex.

```yaml
type: PureMultipleChoiceExercise
key: d8ec3e3242
xp: 50
```

Hello, the dearest class of 2023!

Unfortunately, from now on the Datacamp will not be able to say whether you have submitted the correct answer:( It will accept any answer. We hope that you are honest (with yourself;) and it is best for you to do it as well as you can!
We do encourage you to ask each other for feedback (and get to know your classmates better)!

Honest confession (from Svitlana): I had 0 knowledge in programming before last summer too, and doing all the recommendations from previous Academic Team helped me A LOT during the first year. You will not regret doing it now and saving your time later.

Lastly, if needed, we can take a look at it too. Feel free to approach Juraj, Akma, Pedro, or Svitlana in Slack.

We hope you have a great summer and enjoy whatever you are doing right now!  [here](https://drive.google.com/drive/u/0/folders/0ABSyXGLltNH9Uk9PVA)

<hr />
Question: Academic Team found correlation between: 

`@hint`


`@possible_answers`
- eating Bob's Donuts and cornerstone performance
- watching narwhals and cornerstone performance
- summer assessments and cornerstone performance

`@feedback`


---

## 6.1. Car Park ex.

```yaml
type: NormalExercise
key: 08fb6ad600
xp: 100
```

You are a the owner of the legendary “XX” car park. Some investors came in to offer you a deal but they first want to know some information, which could be shown with the help of pandas and python. How lucky they are that you actually do know Pandas! But first, import the car data from your park 
```
("https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/05_Merge/Auto_MPG/cars2.csv").
```

`@instructions`
Now find the following:
1. How many cars weigh less than 2000kg?
2. What is the percentage of cars out of the whole park that have 8 cylinders?
3. What is the most heavy car?

`@hint`
pd.read_csv("") can read csv files directly from the internet. 
Try to run
```
data = pd.read_csv("https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/05_Merge/Auto_MPG/cars2.csv")
```

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Import Pandas
import pandas as pd

# Load csv file from the url into dataframe
data = 

# Show all columns
data.info()

# Your code part1
cars_under_2000 = 

# Your code part2

# Your code part3
```

`@solution`
```{python}
import pandas as pd
data = pd.read_csv("https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/05_Merge/Auto_MPG/cars2.csv")
cars_under_2000 = len(data[data.weight<2000])
```

`@sct`
```{python}

```

---

## 6.2. Baby Boom ex.

```yaml
type: NormalExercise
key: 0d4239c7e6
xp: 100
```

You work at the department that counts and records the baby names in a given year. You are bored, but your boss wants you to identify some statistics. Your boss told you to do it by hand, but you know pandas and python, which would help you to get finished with this task. The source for the baby statistics: 
```
('https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/06_Stats/US_Baby_Names/US_Baby_Names_right.csv').
```

`@instructions`
Now find out the following: 

1. Are there more male or female names in the dataset?
2. What is the name with most occurrences?

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Import Pandas
import pandas as pd

```

`@solution`
```{python}
# Import Pandas
import pandas as pd

# Load csv file from the url into dataframe
data = pd.read_csv("https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/05_Merge/Auto_MPG/cars2.csv")
```

`@sct`
```{python}

```
