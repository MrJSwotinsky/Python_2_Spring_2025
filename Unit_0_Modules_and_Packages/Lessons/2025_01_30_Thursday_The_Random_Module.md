# Python 2
Thursday, January 30th 2025

## The Random Module

**AIM:** What are some of the frequently used entities in the `random` module, and in what ways can we use them?

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TYS64T.4</ins>: Write and analyze programs and code segments that utilize built-in and user-defined modules and packages.

**SUCCESS CRITERIA:**
- [ ] I can explain what a random seed is.
- [ ] I can generate and display the list of entities in the `random` module.
- [ ] I can generate and display random ints, floats, elements of a sequence, and lists of elements of a sequence.
- [ ] I can describe the following specific entities including what arguments they take, what they return, and how they relate to each other: 
    - [ ] `random()`
    - [ ] `uniform()`
    - [ ] `randrange()`
    - [ ] `randint()`
    - [ ] `choice()`
    - [ ] `sample()`
- [ ] I can leverage documentation to learn about other entities within the random module and how to use them.     


|DO NOW|
|---|
|1. Write down the digits of the current time displayed on your device.  For example, if the time is 1:17, write down 1, 1, 7.<br><br>2. Open the task manager on your device, select performance, and write down the digits of the first CPU status you notice.  For example, if the first CPU status you notice is 28%, write down 2, 8.<br><br>3. Add up all the digits you wrote down.  For example using the digits above, add 1 + 1 + 7 + 2 + 8 = 19.|

**AGENDA**
1. Device Data Share Out
2. Pseudorandomness and Random Seeds
3. Displaying a Module's Entities
4. Frequently Used Enitities in the `random` Module
    * `random()`
    * `uniform()`
    * `randrange()`
    * `randint()`
    * `choice()`
    * `sample()` 
5. Random Module Lab

**ASSIGNMENT:** 
<br>[Unit 0 Assignment 02 - Random Module Lab](https://github.com/MrJSwotinsky/Python_2_Spring_2025/blob/main/Unit_0_Modules_and_Packages/Assignments/02_Random_Module_Lab.md)

## Resources
[Random Module Documentation](https://docs.python.org/3/library/random.html)<br><br>
[edube.org](edube.org) (1.2.1.1 Useful Modules AND 1.2.1.5 Useful Modules|random - 1.2.1.8 Useful Modules|random)<br><br>
**Code Reference:** <br>
|Code|Description|
|---|---|
|`random()`|generates a random float between 0 and 1.|
|`uniform(min, max)`|generates a random float between `min` and `max`.<br><br>**Example/** `uniform(50, 100)` will generate a random float between 50 and 100.|
|`randrange(min, max, step)`|generates a random int between `min` and `max` **(including max)** and incrementing by `step`.<br><br>The default value of `min` is 0. The default value of `step` is 1.<br><br>**Example/** `randrange(100)` will generate a random int between 0 and 100. **(including 100)**<br><br>**Example/** `randrange(50,100,10)` will generate 50, 60, 70, 80, 90, or 100. |
|`randint(min, max)`|generates a random int between `min` and `max` **(excluding max)**.<br><br>The default value of `min` is 0.<br><br>**Example/** `randrange(100)` will generate a random int between 0 and 100. **(excluding 100).**<br><br>**Note:** `randint()` has no `step` parameter.|
|`choice(sequence)`|randomly selects an item from a sequence (e.g. a list, a string, etc.).<br><br>**Example/** `choice(['Apple', 'Banana', 'Clementine', 'Dragonfruit', 'Elderberry'])` will randomly select `'Apple'`, `'Banana'`, `'Clementine'`, `'Dragonfruit'`, or `'Elderberry'`.<br><br>**Example/** `choice('Python')` will randomly select `'P'`, `'Y'`, `'T'`, `'H'`, `'O'`, or `'N'`.|
|`sample(sequence, num)`|generates a random sample of `num` items from a sequence (e.g. a list, a string, etc.).<br><br>**Example/** `sample(['Apple', 'Banana', 'Clementine', 'Dragonfruit', 'Elderberry'], 3)` will generate a list containing 3 randomly selected elements from `'Apple'`, `'Banana'`, `'Clementine'`, `'Dragonfruit'`, or `'Elderberry'`.<br><br>**Example/** `sample('Python', 3)` will generate a list containing 3 randomly selected characters from `'P'`, `'Y'`, `'T'`, `'H'`, `'O'`, or `'N'`.|
