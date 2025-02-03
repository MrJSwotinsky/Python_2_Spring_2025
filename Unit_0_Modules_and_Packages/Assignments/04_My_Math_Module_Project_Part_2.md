# Unit 0, Assignment 04: My Math Module Project, Part 2
Due: Wednesday, February 5th 2025

## Reading
[edube.org](edube.org) (1.3.1.4 Modules and Packages)<br><br>

## Assignmment
1. Create a new file in your `My_Math_Module_Project` directory titled, `LastNameFirstInitial_Math_Module_Part_2.md`.
2. Open:
    * `LastNameFirstInitial_Math.py`. 
    * `LastNameFirstInitial_Main.py`.

**Throughout this assignment, you will be navigating back and forth between these three files.**

3. Copy/Paste the questions below into `LastNameFirstInitial_Math_Module_Part_2.md`, and replace `Full_Name` with your full name.  As you work, respond to each prompt.

```markdown
## Math Module Project, Part 2
Full_Name

**1. In Step 1, you created a private variable to store the value of pi.  What is the difference between a private variable and a public variable? What are the two different ways to indicate that a variable is private?

**2. Why might you want pi to be a private variable?**

**3. Explain why private variables in Python aren't really private.**

**4. In Step 10, you declared your counter variable as global.  What is the difference between a global variable and a local variable?**

**5. Why was it necessary to declare your counter variable as global in your sphere formula functions and your distance formula function, but not in the function that returns the value of the counter itself?**
```

4. In `LastNameFirstInitial_Math.py`, create a private variable to store the value of pi (you may estimate pi = 3.1415926535).  Respond to prompts 1, 2, and 3.<br><br>
5. In `LastNameFirstInitial_Math.py`, create a function that takes the radius of a sphere as an argument, and returns the volume of the sphere.<br>Hint: The formula for the volume of a sphere is: $V = \frac{4}{3}\pi r^3$.<br><br>  
6. In `LastNameFirstInitial_Math.py`, create a function that takes the radius of a sphere as an argument, and returns the surface area of the sphere.<br>Hint: The formula for the surface area of a sphere is: $V = 4 \pi r^2$.<br><br> 
7. In `LastNameFirstInitial_Math.py`, create a function that takes the x and y coordinates of two points (i.e. x1, y1, x2, y2), and returns distance between the two points.<br>Hint: The distance formula is: $d = \sqrt{(x_{2} - x_{1})^{2} + (y_{2} - y_{1})^{2}}$.<br><br>  
8. Save and test your functions by calling them from `LastNameFirstInitial_Main.py`.<br><br>
9. Add a counter to `LastNameFirstInitial_Math.py` that tracks how many times a function from your module has been called.
   * First, define a counter variable.
   * Next, declare your counter variable as global in each function.
   * Next, add a line of code to increment your counter variable in each function.
   * Finally, write a function to return the value of your counter.<br><br>
10. Save and test by calling your functions from `LastNameFirstInitial_Main.py`.  Respond to prompts 4 and 5.
