# Unit 0, Assignment 02: Random Module Lab
Due: Friday, January 31st 2025

## Reading
[edube.org](edube.org) (1.2.1.1 Useful Modules AND 1.2.1.5 Useful Modules | random - 1.2.1.8 Useful Modules | random)<br><br>

## Assignmment
1. Create a new Python file in your in your `Python_2_Unit_0_Assignments_and_Labs` folder titled `LastNameFirstInitial_Random_Module_Lab.py`.
2. Copy/Paste the starter code below, replace `Full_Name` with your full name, and complete the lab below.

**As you work, remember to commit frequently and include an appropriate commit message.**

```python
# Random Module Lab
# Full_Name

# Write your code for step 1 below:

print('Random Module Entities:\n')
# Write your code for step 2 below:

print('\nRandom Seed:\n')
# Write your code for steps 3, 4, and 5 below:

print('\nRandom Floats:\n')
# Write your code for step 6 below:

print('\nRandom ints between 0(inclusive) and 5(inclusive) - one argument:\n')
# Write your code for step 7 below:

print('\Random ints between 0(inclusive) and 5(inclusive) - two arguments:\n')
# Write your code for step 8 below:

print('\nRandom ints between 5(inclusive) and 10(inclusive):\n')
# Write your code for step 9 below:

print('\nRandom ints between 0(inclusive) and 5(exclusive) - one argument:\n')
# Write your code for step 10 below:

print('\nRandom ints between 0(inclusive) and 5(exclusive) - two arguments:\n')
# Write your code for step 11 below:

print('\nRandom ints between 5(inclusive) and 10(exclusive):\n')
# Write your code for step 12 below:

print('\nRandom evens between 10 and 20:\n')
# Write your code for step 13 below:

colors = ['red', 'orange', 'yellow', 'green', 'blue', 'purple']
greeting = 'Hello, World!'

print('\nRandom colors:\n')
# Write your code for step 14 below:

print('\nRandom characters:\n')
# Write your code for step 15 below:

print('\nRandom lists of colors:\n')
# Write your code for step 16 below:

print('\nRandom strings:\n')
# Write your code for step 17 below:

# Use comments respond to the following questions and prompts for step 18 below each question/prompt:

# What import strategy must be used in order to be able to display the entities within a module?

# What must you do to display the entities of a module that has been imported using an alias?

# In questions 3, 4, and 5 you generated a set of random numbers in a few different ways.  First, you generated random numbers without setting a seed.  Next, you generated random numbers by setting a seed within a for loop.  Finally, you generated a random numbers by settting a seed before a for loop.  How did the results differ? In your own words, explain what is happening.

# Describe `random()` and `uniform()`  What arguments does each function take?  What does each function return? What is the major difference between `random()` and `uniform()?`

# Describe `randrange()` and `randint()`.  What arguments does each function take?  What does each function return? What are the two major differences between `randrange()` and `randint()?`

# Describe `choice()` and `sample()`.  What arguments does each function take?  What does each function return? What is the major differences between `choice()` and `sample()?`
```

## Lab
1. Import the random module.
2. Write a line of code to display the list of entities in the `random` module.
3. Write a for loop to generate and display 10 random floats between between 0 and 1.
4. Add a line of code within your for loop to set the seed to a specific number (any number, you choose the number, try out some different numbers to see what happens).
5. Comment out the line of code that sets a random seed within your for loop, and replace it with a line of code that sets a random seed before your for loop.
6. Write a for loop to generate and display 10 random floats between 5 and 10.
7. Write a for loop **using one argument only** to generate and display 10 random ints between 0(inclusive) and 5(inclusive).
8. Write a for loop **using two arguments** to generate and display 10 random ints between 0(inclusive) and 5(inclusive).
9. Write a for loop to generate and display 10 random ints between 5(inclusive) and 10(inclusive).
10. Write a for loop **using one argument only** to generate and display 10 random ints between 0(inclusive) and 5(exclusive).
11. Write a for loop **using two arguments** to generate and display 10 random ints between 0(inclusive) and 5(exclusive).
12. Write a for loop to generate and display 10 random ints between 5(inclusive) and 10(exclusive).
13. Write a for loop to generate and display 10 random even numbers between 10 and 20.
14. Write a for loop to generate and display 10 random colors from the list, `colors = ['red', 'orange', 'yellow', 'green', 'blue']`
15. Write a for loop to generate and display 10 random characters from the string, ` greeting = 'Hello, World!'`
16. Write a for loop to generate and display 10 random lists containing 3 colors each using the colors from `colors = ['red', 'orange', 'yellow', 'green', 'blue']`
17. Write a for loop to generate and display 10 random lists containing 3 characters each using the characters from `greeting = 'Hello, World!'`
18. At the bottom of your code, use comments to respond to the following questions and prompts:
     * What import strategy must be used in order to be able to display the entities within a module?
     * What must you do to display the entities of a module that has been imported using an alias?
     * In questions 3, 4, and 5 you generated a set of random numbers in a few different ways.  First, you generated random numbers without setting a seed.  Next, you generated random numbers by setting a seed within a for loop.  Finally, you generated a random numbers by settting a seed before a for loop.  How did the results differ? In your own words, explain what is happening.
     * Describe `random()` and `uniform()`  What arguments does each function take?  What does each function return? What is the major difference between `random()` and `uniform()?`
     * Describe `randrange()` and `randint()`.  What arguments does each function take?  What does each function return? What are the two major differences between `randrange()` and `randint()?`
     * Describe `choice()` and `sample()`.  What arguments does each function take?  What does each function return? What is the major difference between `choice()` and `sample()?`
       
