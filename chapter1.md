---
title: '1. Python Basics'
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
1. [tracking down programming errors and correcting them.]
2. removing all the bugs from your house. 
3. finding all the bugs in the program.
4. fixing the bugs in the program.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sct`
```{python}

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

**True or False: the following is a legal variable name in Python: 
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

## 1.3. input ex.

```yaml
type: NormalExercise
key: 3d3195bb1d
xp: 100
```

Sometimes we need a way to get input from the user. Luckily, in Python there is a built-in function to accomplish this task. As you might expect, it is called input.

```
n = input("Please enter your name: ")
```
The input function allows the user to provide a prompt string. When the function is evaluated, the prompt is shown. The user of the program can enter the name and press return. When this happens the text that has been entered is returned from the input function, and in this case assigned to the variable n. In the console, make sure you run this example a number of times and try some different names in the input box that appears.




`@instructions`
**What will you do to convert input value in _k_ to integer?**

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
n = input("Please enter your name: ")
print("Hello", n)
#It is very important to note that the input function returns a *string* value. 

#Even if you asked the user to enter their age, you would get back a string like "17". It would be your job, as the #programmer, to convert that string into an int or a float, using the int or float converter functions we saw earlier.

k = input('Enter your age:')
#what to do to convert it to integer?
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## 1.4. Str into variable ex.

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

## 1.5. Compound Interest ex.

```yaml
type: NormalExercise
key: eb0edab974
xp: 100
```

The formula for computing the final amount if one is earning compound interest is given on Wikipedia as ![Compound Interest](https://www.thecalculatorsite.com/images/compound-interest-formula-diagram.png)

`@instructions`
Write a Python program that assigns the principal amount of 10000 to variable P, assign to n the value 12, and assign to r the interest rate of 8% (0.08). Then have the program prompt the user for the number of years, t, that the money will be compounded for. Calculate and print the final amount after t years.

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
