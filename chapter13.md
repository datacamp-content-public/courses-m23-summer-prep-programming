---
title: '14. TRY OUT PRELIMINARY ASSESSMENT'
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

This [.csv file](https://doc-10-7s-docs.googleusercontent.com/docs/securesc/dm497p5a4fh9b9tijedks110f4hv444a/m075v8cmpva7qvgqvba2mnlog26l06os/1559116800000/08552425112971249762/00142732287606330913/15UC8VgyWdHGHHFNg1gJ-2B7TCGhFihy7?e=download) contains the number of bikes that passed through Market Street in San Francisco each day in 2017. You should write a function bikes_to_mean() that downloads this data into your program and computes the average number of bikes that passed through Market Street daily in 2017. Your function should not receive arguments and should find the mean by iterating through the numbers in the second column of the file. You should check your result by comparing it to the mean returned by using the “mean” function in the statistics module. Ultimately, your function should return a tuple in the format (mean, boolean), in which boolean is a “True” or “False” value, depending on whether your mean matches the value obtained using the statistics module. 


`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
#Note: This problem is hard and will likely require you to debug your code. Be mindful of the data type you are manipulating when accessing entries in the .csv file. The code snippet below prints every row of a .csv file contained in a given URL. The use of other modules is allowed only to import the .csv file, but the mean itself should not be computed using Python modules. 
>>> import csv, codecs
>>> from urllib.request import urlopen
>>> url = “url_string”
>>> response = urlopen(url)

>>> cr = csv.reader(codecs.iterdecode(response,'utf-8'))
>>> for row in cr:
>>>     print(row)
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Insert exercise title here

```yaml
type: NormalExercise
key: 868c0d0eae
xp: 100
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
