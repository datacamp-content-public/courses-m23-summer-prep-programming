---
title: 'Python Basics Exercises '
description: 'After completing the ​Python Basics Assignment - please do the following exercises to check your understanding.'
free_preview: true
---

## 1.1. Debugging m.c.

```yaml
type: MultipleChoiceExercise
key: 38dc9d2368
xp: 50
```

**MORE ON DEBUGGING**
Programming is a complex process. Since it is done by human beings, errors may often occur. Programming errors are called bugs and the process of tracking them down and correcting them is called debugging. Some claim that in 1945, a dead moth caused a problem on relay number 70, panel F, of one of the first computers at Harvard, and the term bug has remained in use since. For more about this historic event, see ['first bug'](http://en.wikipedia.org/wiki/File:H96566k.jpg)(it is fun!:).

**Debugging is:**

`@possible_answers`
- [tracking down programming errors and correcting them.]
- removing all the bugs from your house. 
- finding all the bugs in the program.
- fixing the bugs in the program.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sct`
```{python}
msg1 = "In context of programming, this is not correct."
msg2 = "Try Again."
msg3 = "That's correct!"

Ex().has_chosen(correct=1, msgs = [msg3, msg1, msg2, msg2])
```

---

## 1.2. Variable name m.c.

```yaml
type: PureMultipleChoiceExercise
key: 601ecf2c0b
xp: 50
```

Variable names can be arbitrarily long. They can contain both letters and digits, but they have to begin with a letter or an underscore. Although it is legal to use uppercase letters, by convention we don’t. If you do, remember that case matters. Bruce and bruce are different variables.

The underscore character (_)_ can also appear in a name. It is often used in names with multiple words, such as my_name or price_of_tea_in_china. There are some situations in which names beginning with an underscore have special meaning, so a safe rule for beginners is to start all names with a letter.

If you give a variable an illegal name, you get a syntax error.

In the example below, each of the variable names is illegal:
```
76trombones = "big parade"
more$ = 1000000
class = "Computer Science 101"
```
76trombones is illegal because it does not begin with a letter. more$ is illegal because it contains an illegal character, the dollar sign. But what’s wrong with class?

It turns out that class is one of the Python keywords. Keywords define the language’s syntax rules and structure, and they cannot be used as variable names. Python has thirty-something keywords.

**True or False: the following is a legal variable name in Python:** 
```
A_good_grade_is_A+
```

`@hint`


`@possible_answers`
- True
- [False]

`@feedback`
- The + character is not allowed in variable names (everything else in this name is fine).

---

## 1.3. Storing string into variable.

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```



`@instructions`
Take the sentence: "All work and no play makes Jack a dull boy". 
Store each word in a separate variable, then print out the sentence on one line using print.

`@hint`
Do you know that function print(...) can take multiple arguments of any datatype? For example print("Hello","World") will print "Hello World". All arguments are automatically separated by space.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Define variables
word1 = "All"


# Print the sentence


```

`@solution`
```{python}
# Define variables
word1 = "All"
word2 = "work"
word3 = "and"
word4 = "no"
word5 = "play"
word6 = "makes"
word7 = "Jack"
word8 = "a dull"
word9 = "boy"

# Print the sentence
print(word1, word2, word3, word4, word5, word6, word7, word8, word9)

```

`@sct`
```{python}
Ex().has_output("All work and no play makes Jack a dull boy", pattern = False)
```

---

## 1.4. Compound Interest ex.

```yaml
type: NormalExercise
key: eb0edab974
xp: 100
```

The formula for computing the final amount if one is earning compound interest is given on Wikipedia as ![Compound Interest](https://www.thecalculatorsite.com/images/compound-interest-formula-diagram.png)

`@instructions`
Write a Python program that assigns the principal amount of 10000 to variable P, assigns to n the value 12, and assigns to r the interest rate of 8% (0.08). Then the program calculates and prints the final amounts after 1, 5 and 10 years. Calculate and print the final amount after t years.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Your code




# Print the result
print("Final amount after 1 year:", year1)
print("Final amount after 5 years:", year5)
print("Final amount after 10 years:", year10)

```

`@solution`
```{python}
# Your code

P = 10000
n = 12
r = 0.08

year1 = P*(1+r/n)**(n*1)
year5 = P*(1+r/n)**(n*5)
year10 = P*(1+r/n)**(n*10)

# Print the result
print("Final amount after 1 year:", year1)
print("Final amount after 5 years:", year5)
print("Final amount after 10 years:", year10)

```

`@sct`
```{python}
Ex().check_object('P').has_equal_value()
Ex().check_object('n').has_equal_value()
Ex().check_object('r').has_equal_value()
Ex().has_equal_output()
```
