---
title: '13. ACCUMULATOR PATTERN'
description: ""
---

## Global vs. Local variable

```yaml
type: TabExercise
key: 6a8a6b0912
xp: 100
```

An assignment statement in a function creates a _local_ variable for the variable on the left hand side of the assignment operator. It is called local because this variable only exists _inside the function_ and you **cannot** use it outside. For example, consider the square function:
```
1   def square(x):
2	    y = x * x
3	    return y
4	
5	z = square(10)
6	print(y)
```
Do you think the code will output any error message?? Try it yourself.


Source (fyi): [here](https://interactivepython.org/courselib/static/thinkcspy/Functions/Variablesandparametersarelocal.html)

`@pre_exercise_code`
```{python}

```

***

```yaml
type: MultipleChoiceExercise
key: 0917e14953
xp: 100
```

`@question`
Do you think the code will output any error message?? Try it yourself.
Copy-paste the code to console and see!
```
def square(x):
  y = x * x
  return y

z = square(10)
print(y)
```

`@possible_answers`
- No error message
- [NameError: name 'y' is not defined]
- SyntaxError: invalid syntax

`@hint`


`@sct`
```{python}

```

---

## Accumulator1.0

```yaml
type: NormalExercise
key: 85e617a191
xp: 100
```

In the previous example, we wrote a function that computes the square of a number. The algorithm we used in the function was simple: multiply the number by itself. In this section we will reimplement the square function and use a different algorithm, one that relies on addition instead of multiplication.

If you want to multiply two numbers together, the most basic approach is to think of it as repeating the process of adding one number to itself. The number of repetitions is where the second number comes into play. For example, if we wanted to multiply three and five, we could think about it as adding three to itself five times. Three plus three is six, plus three is nine, plus three is 12, and finally plus three is 15. Generalizing this, if we want to implement the idea of squaring a number, call it n, we would add n to itself n times.

Source: [here](https://interactivepython.org/courselib/static/thinkcspy/Functions/TheAccumulatorPattern.html)

`@instructions`
1) Do this by hand first and try to isolate exactly what steps you take. You’ll find you need to keep some “running total” of the sum so far, either on a piece of paper, or in your head. Remembering things from one step to the next is precisely why we have variables in a program. This means that we will need some variable to remember the “running total”. It should be initialized with a value of zero. Then, we need to update the “running total” the correct number of times.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Challenge: any ideas on how to implement the same action in Python? Experiment in the console!
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Accumulator2.0

```yaml
type: NormalExercise
key: 6b17ee4a57
xp: 100
```

In words we could say it this way. To square the value of n, we will repeat the process of updating a running total n times. To update the running total, we take the old value of the “running total” and add n. That sum becomes the new value of the “running total”.

This pattern of iterating the updating of a variable is commonly referred to as the **accumulator pattern**. We refer to the variable as the accumulator. This pattern will come up over and over again. Remember that the key to making it work successfully is to be sure to initialize the variable before you start the iteration. Once inside the iteration, it is required that you update the accumulator.

`@instructions`
1) Study the code in the console! 

2) Note that the heading of the function definition is the same as it was before. All that has changed is the details of how the squaring is done. This is a great example of “black box” design. We can change out the details inside of the box and still use the function exactly as we did before.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
def square(x):
    runningtotal = 0
    for counter in range(x):
        runningtotal = runningtotal + x

    return runningtotal

squareResult = square(10)
print("The result of", 10, "squared is", squareResult)
```

`@solution`
```{python}
Notice that the variable runningtotal starts out with a value of 0. Next, the iteration is performed x times. Inside the for loop, the update occurs. runningtotal is reassigned a new value which is the old value plus the value of x.
```

`@sct`
```{python}

```

---

## Summing up

```yaml
type: NormalExercise
key: 449c3bfaa5
xp: 100
```



`@instructions`
Write a fruitful function sumTo(n) that returns the sum of all integer numbers up to and including n. So sumTo(10) would be 1+2+3...+10 which would return the value 55.

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

## List summing up ex.

```yaml
type: NormalExercise
key: ace1d97526
xp: 100
```



`@instructions`
Sum up all the even numbers in a list.

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

## Newton ex.

```yaml
type: NormalExercise
key: 6eacea1474
xp: 100
```



`@instructions`
Write a function called mySqrt that will approximate the square root of a number, call it n, by using Newton’s algorithm. Newton’s approach is an iterative guessing algorithm where the initial guess is n/2 and each subsequent guess is computed using the formula: newguess = (1/2) * (oldguess + (n/oldguess)).

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

## List average ex.

```yaml
type: NormalExercise
key: 18523bbcd0
xp: 100
```



`@instructions`
Create a list containing 100 random integers between 0 and 1000 (use iteration, append, and the random module). Write a function called average that will take the list as a parameter and return the average.

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

## Calc number of characters/numbers in string

```yaml
type: NormalExercise
key: cea0a9a0e6
xp: 100
```



`@instructions`
Write a Python program that accepts a string and calculate the number of digits and letters.

```
Sample Data : Python 3.2
Expected Output :
Letters 6 
Digits 2
```

`@hint`
You will need to iterate over the string!

FOR ???? IN "STRING":

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
