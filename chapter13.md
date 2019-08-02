---
title: 'FINISH: TRY OUT PRELIMINARY ASSESSMENT'
description: 'Time to try whether you can tackle preliminary assessment 2019!'
---

## str_finder(lst)

```yaml
type: NormalExercise
key: 6e0978fa81
xp: 100
```



`@instructions`
Write a function called str_finder(lst) that accepts a list as an argument and returns True if there is a string in it or False otherwise. 
You can use the test cases below to check whether your function is working properly:
```
>>> str_finder([1.5, "Bob’s donuts", 3, True])
Out: True

>>> str_finder([0.05, True, 45, 100**23])
Out: False

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

## equation_solver(a, b, c)

```yaml
type: NormalExercise
key: 212095afb7
xp: 100
```



`@instructions`
Write a function called equation_solver(a, b, c) that takes three numbers as parameters of the quadratic equation in a standard form ax² + bx + c  and outputs a list with all roots of the equation, or a string “No real roots” otherwise. 
You can use the test cases below to check whether your function is working properly:
```
>>> equation_solver(5, 6, 1)
Out: [-0.2, -1.0]

>>> equation_solver(5, 2, 1)
Out: “No real roots”

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

## bikes_to_mean()

```yaml
type: NormalExercise
key: 3066ed4162
xp: 100
```

This [.csv file](https://doc-00-60-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/4tj25u0ffsbtr85m0ma336os4sff6m91/1564761600000/08552425112971249762/*/15UC8VgyWdHGHHFNg1gJ-2B7TCGhFihy7?e=download) contains the number of bikes that passed through Market Street in San Francisco each day in 2017. You should write a function bikes_to_mean() that downloads this data into your program and computes the average number of bikes that passed through Market Street daily in 2017. Your function should not receive arguments and should find the mean by iterating through the numbers in the second column of the file. You should check your result by comparing it to the mean returned by using the “mean” function in the statistics module. Ultimately, your function should return a tuple in the format (mean, boolean), in which boolean is a “True” or “False” value, depending on whether your mean matches the value obtained using the statistics module.

`@instructions`


`@hint`
If download link is not working, please message us on slack in #summer-prep-coding

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
#Note: This problem is hard and will likely require you to debug your code. Be mindful of the data type you are manipulating when accessing entries in the .csv file. The code snippet below prints every row of a .csv file contained in a given URL. The use of other modules is allowed only to import the .csv file, but the mean itself should not be computed using Python modules. 
import csv, codecs
from urllib.request import urlopen
url = “url_string”
response = urlopen(url)

cr = csv.reader(codecs.iterdecode(response,'utf-8'))
for row in cr:
    print(row)
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## factors(num)

```yaml
type: NormalExercise
key: 868c0d0eae
xp: 100
```

Write a function called factors(num) that takes a number as a parameter and returns all of its factors (that is, a number that divides into another without a remainder)  in an ascending list , or the string ‘None’ otherwise. 
You can use the test cases below to check whether your function is working properly:
```
>>> factors(6)
Out: [1, 2, 3, 6]

>>> factors(0)
Out: None

```

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

## pig_game(players)

```yaml
type: NormalExercise
key: 51d2ab8b10
xp: 100
```

In this exercise, you will be using the random and matplotlib libraries in Python. Write a simulation of the Two-Dice Pig Game. The rules of the game are as follows: 
There are at least 2 players;
Each player rolls two standard dice. If neither shows a 1, their sum is added to the player’s total score, and the turn ends;
If a single 1 is rolled, the player scores nothing, and the turn ends;
If two 1s are rolled, the player’s entire score is lost, and the turn ends;
Whoever accumulates 23 points first wins.
If more than 1 player accumulates 23 points or more in the same turn, then the game ends in a tie, and all players with 23 points or more win.

`@instructions`
1) Write a function called pig_game(players) that inputs the number of players (the maximum number of players is 4) and simulates the game.

2) Your program should produce a line graph that shows the players’ running scores after each turn. The plot should look similar to the one below:

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

## pi_estimator()

```yaml
type: NormalExercise
key: 5d1343e2f9
xp: 100
```

Minervans love pi(es)! Help them estimate the value of pi using Python. Write a function called pi_estimator() that does not take any parameter and outputs your estimation of pi’s value as a single float number. 
(Optional) To supplement the function, write a 150-word explanation (add it as a #comment) of why you think this is the best approach (i.e. is algorithmically efficient) to solving the problem.

`@instructions`


`@hint`
Hint:  (You are encouraged to come up with your own approach to this problem, but if needed, use the following hint.) 
Imagine a circle contained within a square (this square is the smallest it could be while still fitting the circle inside). The circle’s center is located at [0, 0], and its radius has a value of 1. By generating random points and checking whether or not they are within the circle’s radius, you may count the total number of points in the circle. The ratio (num_inside_circle/all_points)*4 should help you find the pi value.

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
