---
title: '2. Python Lists'
description: ""
---

## 2.1. Lists ex.

```yaml
type: NormalExercise
key: a914db4710
xp: 100
```



`@instructions`
Create a list called myList with the following six items: 76, 92.3, “hello”, True, 4, 76. Do it with both append and with concatenation, one item at a time.
Starting with the list of the previous exercise, write Python statements to do the following:

1. Append “apple” and 76 to the list.
2. Insert the value “cat” at position 3.
3. Insert the value 99 at the start of the list.
4. Find the index of “hello”.
5. Count the number of 76s in the list.
6. Remove the first occurrence of 76 from the list.
7. Remove True from the list using pop and index.

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

## 2.2. True/False m.c.

```yaml
type: MultipleChoiceExercise
key: c4114ca86b
xp: 50
```

A list can contain only integer items.

`@possible_answers`
- True
- [False]

`@hint`


`@pre_exercise_code`
```{python}

```

`@sct`
```{python}

```

---

## 2.3. Lists len() m.c.

```yaml
type: MultipleChoiceExercise
key: 5a928e03af
xp: 50
```

As with strings, the function len returns the length of a list (the number of items in the list). However, since lists can have items which are themselves lists, it important to note that len only returns the top-most length. In other words, sublists are considered to be a single item when counting the length of the list.

Find out the length of the following lists in the console!

```
alist =  ["hello", 2.0, 5, [10, 20]]
print(len(alist))
print(len(['spam!', 1, ['Brie','Pol le Veq'], [1, 2, 3]]))
```

**What is printed by the following statements?**
```
alist = [3, 67, "cat", 3.14, False]
print(len(alist))
```


`@possible_answers`
- 4
- [5]
- 6

`@hint`


`@pre_exercise_code`
```{python}

```

`@sct`
```{python}

```
