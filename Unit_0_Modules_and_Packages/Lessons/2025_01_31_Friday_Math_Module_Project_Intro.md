# Python 2
Friday, January 31st 2025

## Math Module Project Intro

**AIM:** How can we start building our own module?

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TYS64T.4</ins>: Write and analyze programs and code segments that utilize built-in and user-defined modules and packages.

**SUCCESS CRITERIA:**
- [ ] I can describe the behavior of a module upon import.
- [ ] I can describe what the `__name__` variable is and how its value is determined.

|DO NOW|
|---|
|1. Create a new folder in your Computer Science Portfolio titled `My_Math_Module_Project`.<br><br>2. Within your new folder, create three new files:<br><ul><li>`LastNameFirstInitial_Math_Module_Part_1.md`.</li><li>`LastNameFirstInitial_Math.py`. </li><li>`LastNameFirstInitial_Main.py`.</li>|

**AGENDA**
1. Math Module Task Overview
2. Directory Organization
3. Module Behavior Upon Import
4. The `__name__` Variable
5. Math Module Project, Part 1

**ASSIGNMENT:** 
<br>[Unit 0 Assignment 03 - Math Module Project, Part 1](https://github.com/MrJSwotinsky/Python_2_Spring_2025/blob/main/Unit_0_Modules_and_Packages/Assignments/03_My_Math_Module_Project_Part_1.md)

## Resources
[edube.org](edube.org) (1.3.1.2 Modules and Packages - 1.3.1.3 Modules and Packages)<br><br>

**Notes:** <br>
|Note:|Description|
|---|---|
|**Directory Organization**| All moduled that should be imported to a file in the same directory as that file.|
|**Module File Name vs. Module Import Name**|The name of a module should end with the `.py` extension.  However, on import `.py` should be excluded.<br><br>For example, `LastNameFirstInitial_Math.py` should be imported as `LastNameFirstInitial_Math`|
|**Module Behavior Upon Import**|The code in a module will be executed exactly one time upon import.<br><br>This allows its functions to be defined, variables to be defined, etc.<br><br>If a module contains a command (for example, a print statement), that command will also be executed upon import.<br><br>If a module is imported twice (for example, one on time as part of a package and a second time individually), its code will still only be executed once.|
|**The `__pycache__` Folder**|When a module is imported, a new subdirectory within its directory will appear, titled `__pycache__`.<br><br> The `__pycache__` folder will contain a file within it ending in `.pyc`.<br><br>The `.pyc` extension indicates that the file contains partially compiled Python code.<br><br>The purpose of this file is to provide faster execution and run time for all future imports of the same module.|

**Code Reference:** <br>
|Code|Description|
|---|---|
|`__name__`|When a Python script is run directly, the value of `__name__` is set to `__main__`.<br><br>When a module is imported, the value of `__name__` is set to the name of the module.|
|#!/usr/bin/env python3 |Hashbang Needed at the top of a module for Unix and Unix-like OS's (e.g. Mac)|
