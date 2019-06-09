---
title: 'Functions and Packages Exercises '
description: ""
---

## 3.1. Lists len() m.c.

```yaml
type: MultipleChoiceExercise
key: bbb3615c19
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
msg2 = "Try Again."
msg3 = "That's correct!"

Ex().has_chosen(correct=2, msgs = [msg2, msg3, msg2])
```

---

## 3.2. Lists ex.

```yaml
type: NormalExercise
key: 8179255388
xp: 100
```

Explore Python documentation [](https://docs.python.org/3/tutorial/datastructures.html) for more lists methods and experiment with some of them!

`@instructions`
1) Create a list called myList with the following six items: 76, 92.3, “hello”, True, 4, 76. Do it with both append and with concatenation.

2) With this created list, write Python statements to do the following:

1. Append “apple” and 76 to the list.
2. Insert the value “cat” at position 3.
3. Insert the value 99 at the start of the list.
4. Find and print the index of “hello”.
5. Count and print the number of 76s in the list.
6. Remove the first occurrence of 76 from the list.
7. Remove True from the list using pop and index.
8. Print the final list

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
# First part
myList = [76] + [92.3, "hello", True, 4]
myList.append(76)

#Second part
myList.append("apple")
myList = myList[:3] + "cat" + myList[3:]
myList = [99] + myList
print(myList.index("hello"))
print(myList.count(76))
del myList[1]
myList.pop(myList.index(True))
print(myList)
```

`@sct`
```{python}
Ex().check_object('myList').has_equal_value()
```

---

## 3.3. Pythogenrean Theorem ex.

```yaml
type: NormalExercise
key: db0cf5b422
xp: 100
```



`@instructions`
The Pythagorean Theorem tells us that the length of the hypotenuse of a right triangle is related to the lengths of the other two sides. Look through the math module and see if you can find a function that will compute this relationship for you. Once you find it, write a short program to try it out.

`@hint`
If you do not know - visit official Python Documentation website! [](https://docs.python.org/3/library/math.html)

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
import math

side1 = 3
side2 = 4
hypotenuse = math.hypot(side1,side2)
print(hypotenuse)
```

`@sct`
```{python}
Ex().check_object('math').has_equal_value()
Ex().has_equal_output()
```
