# Python 2
Tuesday, January 28th 2025

## Introduction to Modules and Packages

**AIM:** What are modules and packages, what purpose do they serve, and how can we gain access to their entities?

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TYS64T.4</ins>: Write and analyze programs and code segments that utilize built-in and user-defined modules and packages.

**SUCCESS CRITERIA:**
- [ ] I can describe modules and packages and explain what purpose they serve.
- [ ] I can import and use entities from modules using a variety of different strategies.
- [ ] I can describe the advantages and disadvantages of different import strategies.
- [ ] I can leverage documentation to develop my understanding of specific modules and the entities contained within them.

|DO NOW|
|---|
|1. Respond to the following in your notes:<br><ul><li>What mobile apps do you use the most?</li><li>What do you like about them?</li><li>What features do they have?</li></ul>**Be prepared to share!**|

1. Mobile App Discussion
2. Modules
3. Documentation
4. Code Along - Importing Entities
5. Introduction to Modules and Packages Assignment

**ASSIGNMENT:** 
<br>[Unit 0 Assignment 01 - Introduction to Modules and Packages](https://github.com/MrJSwotinsky/Python_2_Spring_2025/blob/main/Unit_0_Modules_and_Packages/Assignments/01_Introduction_to_Modules_and_Packages.md)

## Resources
[Random Module Documentation](https://docs.python.org/3/library/random.html)<br><br>
[edube.org](edube.org) (1.1.1.1 Modules - 1.1.1.11 Section Summary)<br><br>
**Code Reference:** <br>
|Code|Description|
|---|---|
|`import module_1`| imports `module_1`.<br><br>When this import strategy is used, entities must be accessed using dot notation.<br><br>For example, `module_1.entity_1()` accesses `entity_1()` of `module_1`.|
|`from module_1 import *`| imports all entities of `module_1`.<br><br>When this import strategy is used, entities must be accessed without using dot notation.<br><br>For example, `entity_1()` accesses `entity_1()` of `module_1`.|
|`from module_1 import entity_1`| imports only `entity_1()` of `module_1`.<br><br>When this import strategy is used, entities must be accessed without using dot notation.<br><br>For example, `entity_1()` accesses `entity_1()` of `module_1`.|
|`import module_1 as m1`| imports `module_1` using the alias `m1`.<br><br>When this import strategy is used, entities must be accessed using their alias and dot notation.<br><br>For example, `m1.entity_1()` accesses `entity_1()` of `module_1`.|
|`from module_1 import entity_1 as e1`| imports only `entity_1()` (using the alias `e1`) of `module_1`.<br><br>When this import strategy is used, entities must be accessed using their alias without using dot notation.<br><br>For example, `e1()` accesses `entity_1()` of `module_1`.|
|`from module_1 import entity_1, entity_2`| imports only `entity_1()` and `entity_2` of `module_1`.<br><br>When this import strategy is used, entities must be accessed without using dot notation.<br><br>For example, `entity1()` accesses `entity_1()` of `module_1` and `entity2()` accesses `entity_2()` of `module_1`.|
|`from module_1 import entity_1 as e1, entity_2 as e2`| imports only `entity_1()` (using the alias `e1`) and `entity_2` (using the alias `e2`) of `module_1`.<br><br>When this import strategy is used, entities must be accessed using their aliases without using dot notation.<br><br>For example, `e1()` accesses `entity_1()` of `module_1` and `e2()` accesses `entity_2()` of `module_1`.|
