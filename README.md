# CS101 Spring 2025: Lab 03

## Assigned and Due

* __Assigned__: Friday, 6th Feb 2026 at 2:35pm
* __Due__: Friday 13th 2026 at 2:35pm
* __Expiration__: Friday 20th Feb 2026 at 2:35pm
Note: the *expiration* date is the last date you can submit your work for a grade.

![pythonProgrammingGraphic](graphics/sunset_and_python.png)

## Assignment: Completing Smaller Programs in Python

Welcome! In this lab, you will practice Python programming fundamentals including _literals_, _functions_, _function calls_, _returns_, _conditionals_, and types of _loops_.

Much of this lab will act a refresher for you from your previous experiences with Python programming. 

Each assignment is organized in its own folder with starter code (with TO-DOs) to complete, and assignment sheet to let you know what to do in each assignment. After you have completed your programming exercises, you will also complete a short writing assignment reflecting on your experiences completing the programming assignments.

## Overview

This semester, we have spent a good deal of time learning some of the the basics of programming in Python. For instance, we have discussed literals, functions, loops and conditional statements. Below you are invited to complete four small programming assignments. Each assignment is designed to help you practice specific programming concepts which are described in assignment sheets, available at the links below.

As an added twist of this assignment, each programming assignment is to be composed of two files where one serves as the main program that the user interacts with and the other file contains functions that implement the core logic of the program. This structure is intended to help you practice modular programming and improve code organization.

In addition to completing the programming assignments, you will also complete a short writing assignment reflecting on your experiences completing the programming assignments. The writing assignment is described in more detail below.

## Modular Programming

In each assignment, you will edit two files: one for the main program that the user interacts with, and another file that contains special functions to implement the core logic of the program.

To connect two files, you will use the `import` statement to bring in functions from one file into another. For example, if you have a file named `math_utils.py` that contains a function `add(a, b)`, you can use this function in your `main.py` file by importing it:

In the directory, `./assignments/example_modular_programming/`, you will find a simple example of how to structure your source files for modular programming. The file structure would look like this:

File `main.py` contains, 

```python
from math_utils import add # load the function add from the file math_utils.py

num_1 = 5
num_2 = 10
result = add(num_1, num_2) # call the function in math_utils.py and use its returned value
print(f"The sum of {num_1} and {num_2} is {result}.")
```

File `math_utils.py` contains,

```python
def add(a, b):
    return a + b
```

In this example, `main.py` imports the `add` function from `math_utils.py`, allowing you to use it as if it were defined in `main.py`. This approach helps keep your code organized and modular. 

![--- --- --- --- --- --- --- --- ---](graphics/div_bar.png)

## Assignments

* [Number Guessing Game](assignments/number_guessing_game/assignment.md)
  * [Starter Code](assignments/number_guessing_game/main.py)
  * [game_logic.py](assignments/number_guessing_game/game_logic.py)

* [Palindrome Checker](assignments/palindrome_checker/assignment.md)
  * [Starter Code](assignments/palindrome_checker/main.py)
  * [palindrome.py](assignments/palindrome_checker/palindrome.py)

* [Prime Finder](assignments/prime_finder/assignment.md)
  * [Starter Code](assignments/prime_finder/main.py)
  * [prime_utils.py](assignments/prime_finder/prime_utils.py)

* [Quadratic Equation Solver](assignments/quadratic_solver/assignment.md)
  * [Starter Code](assignments/quadratic_solver/main.py)
  * [quadratic.py](assignments/quadratic_solver/quadratic.py)

* [Extra Challenge](./assignments/extra_challenge/challenge.md)
  * Add your own starter code for your own amazing project! In this challenge, try using three module files to attach to your `main.py`. Describe your work by editing the [Extra Challenge](assignments/extra_challenge/challenge.md) document.

Work through each assignment by reading the assignment sheet, editing the starter code, and testing your solutions. Use the instructor's code for demonstrations or to check your work.

![--- --- --- --- --- --- --- --- ---](graphics/div_bar.png)

## Deliverables

The following items are to be submitted for this assignment.

* __Number Guessing Game files__:
  * [number_guessing_game/main.py](assignments/number_guessing_game/main.py)
  * [number_guessing_game/game_logic.py](assignments/number_guessing_game/game_logic.py)

* __Palindrome Checker files__:
  * [palindrome_checker/main.py](assignments/palindrome_checker/main.py),
  * [palindrome_checker/palindrome.py](assignments/palindrome_checker/palindrome.py)

* __Prime Finder files__:
  * [prime_finder/main.py](assignments/prime_finder/main.py),
  * [prime_finder/prime_utils.py](assignments/prime_finder/prime_utils.py)

* __Quadratic Equation Solver files__:
  * [quadratic_solver/main.py](assignments/quadratic_solver/main.py),
  * [quadratic_solver/quadratic.py](assignments/quadratic_solver/quadratic.py)

* __Writing assignment__:
  * [Reflections](writing/reflection.md)

* __Extra Challenge__:
  * [extra_challenge/main.py](assignments/extra_challenge/main.py)



Note: As you work, please periodically commit your changes and push them to your GitHub repository. This will ensure that your work is saved and can be reviewed by your instructor.

![--- --- --- --- --- --- --- --- ---](graphics/div_bar.png)

## Submission

As you are working on your lab, you are to commit and push regularly. The commands are the following.

 ``` bash
git add -A
git commit -m ``Your notes about commit here''
git push
```

After you have pushed your work to your repository, please visit the repository at the GitHub website (you may have to log-in using your browser) to verify that your files were correctly sent.

![--- --- --- --- --- --- --- --- ---](graphics/div_bar.png)

## Project Assessment

The grade that a student receives on this assignment will have the following components.

* __GitHub Actions CI Build Status [up to 10%]__: For the lab repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes. This is only checking some baseline writing and commit requirements as well as correct running of the program. An additional reduction will given if the commit log shows a cluster of commits at the end clearly used just to pass this requirement. An addition reduction will also be given if there is no commit during lab work times. All other requirements are evaluated manually.

* __Mastery of Technical Writing [up to 50%]__: Students will also receive a checkmark grade when the responses to the writing questions presented in the `reflection.md` reveal a proficiency of both writing skills and technical knowledge. To receive a checkmark grade, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

* __Mastery of Technical Knowledge and Skills [up to 40%]__: Students will receive a portion of their assignment grade when their program implementation reveals that they have mastered all of the technical knowledge and skills developed during the completion of this assignment. As a part of this grade, the instructor will assess aspects of the programming including, but not limited to, the completeness and the correctness of the program and the use of effective source code comments.

![--- --- --- --- --- --- --- --- ---](graphics/div_bar.png)

## GatorGrade

### Checks for GatorGrade

For immediate feedback on submissions, we will be using Gator Grade to inform the of missing components in the submission. As you submit, you will notice that there is a thick red X that will change to a green check mark when all components have been included in the submission. You are encouraged to click on the red X to find a listing of the components to address.

You can check the baseline writing and commit requirements for this lab assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`: `gatorgrade --config config/gatorgrade.yml`

## Seeking Assistance

* Extra resources for using markdown include;
  + [Markdown Tidbits](https://www.youtube.com/watch?v=cdJEUAy5IyA)
  + [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Do not forget to use the above git commands to push your work to the cloud for the instructor to grade your assignment. You can go to your GitHub repository using your browser to verify that your files have been submitted. Please see the TL’s or the instructor if you have any questions about assignment submission.

Students who have questions about this project outside of the lab time are invited to ask them in the course's Discord channel or during instructor's or TL's office hours.

---
For questions or suggestions about the game, please contact the course instructor.
