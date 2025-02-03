# Python 2
Tuesday, February 4th 2025

## Variables (Private, Public, Global, Local) and Expanding My Math Module

**AIMS:** <br>
What are private, public, global, and local variables?<br>
How can I expand my math module to include functions that calculate mathematical formulas? 

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TYS64T.2</ins>: Apply Basic Programming Concepts (e.g., control flow, data collections, functions, exception-handling) to more complex contexts.
<br><ins>IEC.TYS64T.4</ins>: Write and analyze programs and code segments that utilize built-in and user-defined modules and packages.

**SUCCESS CRITERIA:**
- [ ] I can describe the difference between private and public variables.
- [ ] I can explain why private variables in Python aren't really private.
- [ ] I can describe the difference between global and local variables.
- [ ] I can explain when it is necessary to declare a variable as global.
- [ ] I can expand my math module to include functions that calculate mathematical formulas. 

|DO NOW|
|---|
|1. Create a new file in your `My_Math_Module_Project` directory titled, `LastNameFirstInitial_Math_Module_Part_2.md`.<br>2. Open:<ul><li>`LastNameFirstInitial_Math.py`.</li><li>`LastNameFirstInitial_Main.py`.</li></ul>|

**AGENDA**
1. Private vs. Public Variables
2. Code Along, Part 1
   * $\pi$ (approximately 3.1415926535)
   * Circle Functions
   * Triangle Area Function
4. Global vs. Local Variables
5. Code Along, Part 2 - Counter
6. Math Module Project, Part 2

**ASSIGNMENT:** 
<br>[Unit 0 Assignment 04 - Math Module Project, Part 2](https://github.com/MrJSwotinsky/Python_2_Spring_2025/blob/main/Unit_0_Modules_and_Packages/Assignments/04_My_Math_Module_Project_Part_2.md)

## Resources
[edube.org](edube.org) (1.3.1.4 Modules and Packages)<br><br>

**Notes:** <br>
|Note:|Description|
|---|---|
|**Private vs. Public Variables**|**Public Variables** in Python are standard variables that are intended to be used and can be viewed or changed.<br><br>**Private Variables** in Python are variables that are intended to be used, but **not** viewed or changed.<br><br>Variables that should be treated as private start with either a single or double underscore.<br><br>For example, `_pi` and `__pi` define private variables.<br><br>**Note:** In Python, private variables are not really private.  Rather, it is a suggestion.  In other words, when a variable starts with a single or double underscore, it is suggested that it should not be viewed or changed, but not prevented from being viewed or changed.||
|**Global vs. Local Variables**|**Global Variables** exist within the scope of an entire program.<br><br>**Local Variables** exist within the scope of a portion of a program. (e.g. a function)<br><br>To **use** a globally defined variable within a function, it is **not** neccesary to declare it as a global variable within the scope of the function.<br><br>To **modify** a globally defined variable within a function, it **is** neccesary to declare it as a global variable within the scope of the function.|

**Sample Math Formula Functions:**

```python
__pi = 3.1415926535
# Circumference of a Circle
# Accept the radius of a circle as an argument and return the circumference of the circle.
def circumference(rad):
  return 2 * pi * rad 
```

```python
__pi = 3.1415926535
# Area of a Circle
# Accept the radius of a circle as an argument and returns the area of the circle.
def circ_area(rad):
  return pi * rad * rad
```

```python
# Area of a Triangle
# Accept the base and height of a triangle as arguments and returns the area of the triangle.
def tri_area(b, h):
  return 0.5 * b * h
```

[Sample Math Formulas](https://www.matematica.pt/en/useful/math-formulas.php#google_vignette)
