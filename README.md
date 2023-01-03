# Homework 0

This homework will not count for a grade but is highly recommended to get comfortable with using GitHub Classroom & practice concepts covered in our first week together.

## Reminders

### Git & GitHub
If you haven't already gotten set up with GitHub, you'll want to look at [Git Basics](https://uchicago-cs.github.io/student-resource-guide/tutorials/git-basics.html) from the UChicago CS Student Resource Guide.

### Environment 
For this entire course, we are assuming you are running your code on the CS department Linux environment.  This environment already has Python 3.8 installed, as well as relevant packages such as `pytest`.

You are free to develop in a setup of your choosing, but due to the infinite possible variations stemming from different operating systems, versions of Python, etc., we will not be able to provide support for issues you may run into specific to your local environment.

You may want to look at [Using VS Code and SSH](https://uchicago-cs.github.io/student-resource-guide/vscode/ssh.html) if you want to edit files on your machine and run them on the department's Linux servers.

### Style Guide
We expect you to follow the department [style guide](https://uchicago-cs.github.io/student-resource-guide/style-guide/python.html).

This counts towards 10-20% of your grade. This is not just to be picky, following code style guidelines is important in a professional setting, where you will find that reading code is just as important as writing it.

### Running `pytest`

Each problem comes with some helpful tests.  These are not guaranteed to be comprehensive, it may benefit you to consider other cases as well.

You can run `pytest` from this directory to run all tests for the homework.

It is likely more useful to either run `pytest` from within a subdirectory (e.g. `problem1/`) or `pytest problem1` from the main directory.

If you'd like `pytest` to stop after a single failure, add the `-x` flag.

It can also be useful to add the `-v` tag sometimes to get more verbose output.

## Problems

### Problem 1

Open `problem1/leap_year.py`, and implement the `is_leap_year`` function according to the specifications provided.

### Problem 2

Open `problem2/duplicates.py`, and implement the `find_duplicates`` function according to the specifications provided.

### Problem 3

The Collatz conjecture is a famous unsolved problem in math that asks if the function

<picture>
  <source media="(prefers-color-scheme: light)" srcset="collatz.svg" height="100px">
  <img alt="The Collatz Conjecture Function" src="collatz.svg" height="100px" style="filter: invert(1);">
</picture>

converges on *1* for all initial values of *n*.

(Source: https://en.wikipedia.org/wiki/Collatz_conjecture)

We're going to implement two functions that will allow us to test given values of n.

Open `problem3/collatz.py`, and implement the two functions.

Note: Keep the difference between `/` and `//` in mind.

**Reference**: https://docs.python.org/3/glossary.html#term-floor-division

**Optional**: 
For those who are curious and would like to see a great visual essay about the attempts to solve the Collatz conjecture, this 22-minute video is highly recommended (but not required to solve the problem): [Vertasium's Collatz Conjecture Video](https://www.youtube.com/watch?v=094y1Z2wpJg)
