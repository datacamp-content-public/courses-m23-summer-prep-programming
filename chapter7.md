---
title: 'Introduction to Matplotlib Exercises '
description: ""
---

## 7.1. Plotting data

```yaml
type: NormalExercise
key: bd365b4bcc
xp: 100
```

Imagine yourself working for a company, hired to analyze the user growth rate of the company. For an analysis, you are required to visualize the data and show whether the growth is linear, exponential, etc.

If you have problems with importing the library, try no-cache version by changing url from https://**campus**.datacamp.com/... to https://**campus-no-cache**.datacamp.com/...

`@instructions`
Here is the sample data:
 
```
Year Number of users
2011    43
2012    124
2013    400
2014    682
2015    793
2016    899
2017    977
2018    1201
2019    1534
 
```

How would you visualize it? Make sure you show the dates, label the axes, put a title, and make the graph beautiful!

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# import library for plots
import ...

# load data from instructions


# create vizualization


# create labels and titles
```

`@solution`
```{python}
# import library for plots
import matplotlib.pyplot as plt

# load data from instructions
years = [2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019]
number_of_users = [43, 124, 400, 682, 793, 899, 977, 1201, 1534]

# create vizualization
plt.plot(years, number_of_users)

# create labels and titles
plt.title("Growth of the company between 2011 to 2019")
plt.xlabel("Year")
plt.ylabel("Number of users")
plt.show()
```

`@sct`
```{python}

```

---

## 7.2. Heart graphing ex. <3

```yaml
type: NormalExercise
key: 1cc95c5cfd
xp: 100
```



`@instructions`
Let's imagine you want to show gratitude to those who took care of you. You're now looking for a heart image online to print it out and glue it to your card. However, you can't find anything that looks good. That said, your job is create a heart graph that is absolutely pretty.

`@hint`
You can try to find some extra inspiration here [https://www.quora.com/What-is-the-equation-that-gives-you-a-heart-on-the-graph](https://www.quora.com/What-is-the-equation-that-gives-you-a-heart-on-the-graph)
Find equation that you like and then make a plot.

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
