# Unit 0, Assignment 03: My Math Module Project, Part 1
Due: Monday, February 3rd 2025

## Reading
[edube.org](edube.org) (1.3.1.2 Modules and Packages - 1.3.1.2 Modules and Packages)<br><br>

## Assignmment
1. Create a new folder in your Computer Science Portfolio titled `My_Math_Module_Project`.
2. Within your new folder, create three new files:
    * `LastNameFirstInitial_Math_Module_Part_1.md`.
    * `LastNameFirstInitial_Math.py`. 
    * `LastNameFirstInitial_Main.py`.

**Throughout this assignment, you will be navigating back and forth between these three files.**

3. Copy/Paste the questions below into `LastNameFirstInitial_Math_Module_Part_1.md`, and replace `Full_Name` with your full name.  As you work, respond to each prompt.

```markdown
## Math Module Project, Part 1
Full_Name

**1. In Step 6 you opened the new `pycache` folder containing a single file.  The file itself is not read-able by humans, but it has a purpose.  What is the name of the file in `pycache` and what is its purpose?**

**2. In Step 8 you ran `LastNameFirstInitial_Main.py`.  What was displayed, and why was it displayed even though `LastNameFirstInitial_Main.py` did not have any print statements.  In general, when a module file is imported to a main file, what happens whenever the main file is run?**

**3. In Step 9 you ran `LastNameFirstInitial_Math.py`.  What was displayed?  In general, when **any** file containing `print(__name__)` is run, what name will be displayed?**

**4. In Step 10 you ran `LastNameFirstInitial_Main.py`.  What was displayed?  In general, when a module containing `print(__name__)` is imported to a main file and the main file is run, what will be displayed?**

```

4. In `LastNameFirstInitial_Main.py`, import `LastNameFirstInitial_Math.py`, save, and run.
5. Run `LastNameFirstInitial_Main.py`.  You should not notice anything in the IDLE.  However, something happened in the background...  
6. Open the folder containing `LastNameFirstInitial_Main.py` and `LastNameFirstInitial_Math.py`.  You should see a new subfolder, titled `pycache` containing a single file.  Respond to question 1.
7. Add the following line of code to `LastNameFirstInitial_Math.py`: `print('Test')` and save.
8. Run `LastNameFirstInitial_Main.py`.  Respond to question 2.
9. In `LastNameFirstInitial_Math.py`, comment out `print('Test')`, add the following line of code: `print(__name__)`, save, and run.  Respond to question 3.
10. Run `LastNameFirstInitial_Main.py`.  Respond to question 4.
