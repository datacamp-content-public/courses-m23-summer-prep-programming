---
title: '10. Loops'
description: ""
---

## 10.1. ex.

```yaml
type: NormalExercise
key: 2b50d303a9
xp: 100
```



`@instructions`
Write a program that prints "We are M23!"" 100 times.

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

## 10.2. Example -> elpmaxe ex.

```yaml
type: NormalExercise
key: 42c59d43f2
xp: 100
```



`@instructions`
Write a Python program that accepts a word from the user and reverse it.

example -> elpmaxe

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

## 10.3. Range ex.

```yaml
type: NormalExercise
key: d9e3dedb74
xp: 100
```

Python range() accepts an integer and returns a range object, which is nothing but a sequence of integers. Let’s understand how to use range() function with the help of simple examples.

Study the code in the console to see how it can be used!

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
#first example 
listexample = list(range(3))
print(listexample)
#Question: What happens if you provide a negative value? Try it below!
 

#second example
a = ['Mary', 'had', 'a', 'little', 'lamb']
for i in range(len(a)):
    print(i, a[i])
    
#third example    
#what if you provide 2 or even 3 parameters to _range(PARAMETERS)_ instead of one?  
#try it out! Print the lists  below
list(range(1,7))
list(range(1,7,3))
list(range(-17,7, 2))


```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## 10.4. Range m.c.

```yaml
type: MultipleChoiceExercise
key: 20df05fcbe
xp: 50
```

What command correctly generates the sequence 2, 5, 8?

`@possible_answers`
- range(2, 5, 8)
- range(2, 8, 3)
- [range(2, 10, 3)]
- range(8, 1, -3)

`@hint`


`@pre_exercise_code`
```{python}

```

`@sct`
```{python}

```

---

## 10.5. Multiplication Table ex.

```yaml
type: NormalExercise
key: 6bcb68a16a
xp: 100
```



`@instructions`
Write a Python program to create the multiplication table (from 1 to 10) of a number.
```
Expected Output:

Input a number: 6                                                       
6 x 1 = 6                                                               
6 x 2 = 12                                                              
6 x 3 = 18                                                              
6 x 4 = 24                                                              
6 x 5 = 30                                                              
6 x 6 = 36                                                              
6 x 7 = 42                                                              
6 x 8 = 48                                                              
6 x 9 = 54                                                              
6 x 10 = 60 
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

## 10.6 Month ex.

```yaml
type: NormalExercise
key: 719f151d9a
xp: 100
```



`@instructions`
Write a program that uses a for loop to print
```
One of the months of the year is January
One of the months of the year is February
One of the months of the year is March
```

etc …

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
for amonth in ['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'November', 'December']:
    print("One of the months of the year is", amonth)
```

`@sct`
```{python}

```
