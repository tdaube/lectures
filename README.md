# MY470 Computer Programming


## Michaelmas Term 2020

## Instructors

* [Milena Tsvetkova](m.tsvetkova@lse.ac.uk), *Office hours*: Fridays 10:00–11:00 and 15:00–16:00, on Zoom
* [Friedrich Geiecke](f.c.geiecke@lse.ac.uk), *Office hours*: Tuesdays 10:30–12:30, on Zoom
* [Sian Brooke](s.j.brooke@lse.ac.uk), *Office hours*: Fridays 13:00–15:00, on Zoom
* Lana Bilalova (GTA)

## Course Information

* Interactive lecture sessions take place online (Zoom links on Moodle) on:
  * Mondays 14:00–15:00
  * Tuesdays 11:00–12:00

* Seminars take place on:
  * Tuesdays 10:00–11:00 in CLM.2.02
  * Tuesdays 12:00–13:00 on Zoom, link on Moodle
  * Tuesdays 17:00–18:00 in PAN.G.01
  * Tuesdays 18:00–19:00 in PAN.G.01

No lecturer sessions or classes will take place during School Reading Week 6.


## Course Description

This course introduces students to the fundamentals of computer programming as students design, write, and debug computer programs using the programming languages Python and R. The course will also cover the foundations of computer languages, algorithms, functions, variables, object orientation, scoping, and assignment. The course will rely on practical examples from computational social science and social data science.

## Organization

This course is an introduction to the fundamental concepts of programming for students who lack a formal background in the field, but will include more advanced problem-solving skills in the later stages of the course. Topics include algorithm design and program development; data types; control structures; functions and parameter passing; recursion; searching and sorting; and an introduction to the principles of object-oriented programming.

## Prerequisites

This is an introductory class and no prior experience with programming is required.

## Software

The course will use Python and R. We will use the Anaconda distribution to install Python and manage packages and Jupyter Notebook to write code. We will use RStudio to write code in R. Lectures and assignments will be posted on GitHub. Students are expected to use GitHub also to submit problem sets and final exam.

## Materials

The main course texts will be:
* Guttag, John V. *Introduction to Computation and Programming Using Python: With Application to Understanding Data*. MIT Press, 2016.
* Miller, Bradley N. and David L. Ranum. [*Problem Solving with Algorithms and Data Structures Using Python*](http://interactivepython.org/runestone/static/pythonds/index.html).
* Grolemund, Garrett and Hadley Wickham. [*R for Data Science*](http://r4ds.had.co.nz). O’Reilly, 2016.

Additional resources include:
* [Intermediate and advanced Python documentation](http://docs.python.org/3/)
* [Python Wikibook](https://en.wikibooks.org/wiki/Python_Programming)
* Matthes, Eric. [*Python Crash Course Cheat Sheet*](https://ehmatthes.github.io/pcc/cheatsheets/README.html).

## Assessment

Take home exam (50%) and in-class assessment (50%). Students will be expected to produce 9 weekly problem sets in the MT. The first problem set is formative. The remaining 8 problem sets will be marked, and will provide 50% of the mark.

Doctoral students registered for MY570 will be required to complete a substantive project of their own choice in place of the take home exam. You will be required to develop Python software that addresses a sufficiently complex computational social science task. Examples of possible projects include a software package that collects and analyses online data, an experimental game, or an agent-based model. The project should be approved by the instructors, so please get in touch with us well in advance.

Problem sets will be distributed by Tuesday evening and due at 12:00 noon the following Monday.

The take home exam will be distributed on Monday, December 14, 2020 and due at 12:00 noon on Monday, January 18, 2021.

Please note that the deadlines are final. Late submissions for the weekly problem sets will automatically receive score 0, except in the case of a valid documented legal or medical excuse. Late submissions for the final take home exam will be penalized according to LSE's standard assessment rules. More information can be found [here](https://info.lse.ac.uk/current-students/services/assessment-and-results/exceptional-circumstances/extension-policy).

## Assessment Criteria
Your code will be evaluated both on whether it completes the task and on the extent to which it is written using the concepts, paradigms, and best practices covered in the course, most notably, legibility, modularity, and optimization.

|**Mark**         |**Criteria**   |
|:----------------|:--------------|
|Pass (50-59)     |The code runs and does what it is expected to |
|Merit (60-69)    |The code runs, does what it is expected to, and is modular and legible |
|Distinction (70-100) |The code runs, does what it is expected to, and is modular, legible, and optimized |


## Collaboration and Plagiarism Policy

Weekly assignments and the final take home exam are individual unless we instruct you otherwise. For all summative assessment, you need to write the code entirely by yourself (or together with your partner if you have been assigned one).

**You are not allowed to:**
* Show your code to other students
* View and copy code by other students (current or past)
* View and copy example solutions that may have leaked

**You may:**
* Talk about the assignments and your approach to solving them with others
* Use general online resources such as Stack Overflow or Python documentation for general queries (e.g. "how to unpack a tuple"). However, if you borrow substantive blocks of code or specific solutions from online forums or blogs, you need to cite your source in the comments.
* Use the forum "Clarifying Questions about Assignments" on the course Moodle site to ask and answer questions about the instructions in the assignments.

Violation of the plagiarism policy for the course will be dealt with in accordance with the [LSE Regulations on Assessment Offences](https://info.lse.ac.uk/Staff/Divisions/Academic-Registrars-Division/Teaching-Quality-Assurance-and-Review-Office/Assets/Documents/Calendar/RegulationsAssessmentOffences-Plagiarism.pdf).

## Communication Channels

**Questions about the content:**
* Ask during the lecture sessions or your seminar
* Schedule office hours with Sian or Milena

**Questions about the upcoming assignment:**
* Post a question on Slack (no code allowed!)
* Post a question on the Moodle forum "Clarifying questions about assignments" (no code allowed!)
* Schedule office hours with Sian or Milena

**Questions about your marked assignment:**
* See the example answers to help you understand the comments
* Schedule office hours with Sian or Milena

**Personal emergencies (e.g. cannot access assignment, cannot meet a deadline):**
* E-mail Milena


## Schedule

---
### Week 1. What is Computation?

In the first week, we will introduce the basic concepts in computer programming: computers, algorithms, programming languages, and programs. We will then discuss the elements of programming languages: primitive constructs, syntax, static semantics, and semantics. We will further introduce the essential primitives for all programming languages: data types, operators, expressions, variables and values.

*Readings*:

* Guttag. Chapters 1-2.1, pp.1–15.
* Wing, Jeannette M. (2006). [Computational thinking](http://tech-insider.org/academia/research/acrobat/0603.pdf). *Communications of the ACM*, 49(3), 33–35.

*Lab*: **Anaconda, Jupyter, and GitHub**
* Installing Python with Anaconda
* Introduction to Jupyter and other IDEs
* Submitting assignments on GitHub

---
### Week 2. Data Types in Python

In the next five weeks of the course, we will use Python to get familiar with the elements of programming languages. We will begin with scalar data types, operators, expressions, and value assignment to variables. We will also cover non-scalar, also known as compound or structured, data types (lists, tuples, sets, and dictionaries) and discuss the difference between mutable and immutable and ordered and unordered types. As lists are very commonly used, we will further overview the most common list operations, including indexing, slicing, appending, splitting, aliasing, and cloning.  

*Readings*:
* Guttag. Chapters 2.3, 5.1-5.3, 5.5-5.6, pp.18–21, 65–73, 77–84.

*Lab*: **Working with Strings and Lists in Python**
* Programming with simple statements, including `print()`, `len()`, `append()`, `extend()`, `pop()`, `remove()`, `split()`, `join()`, `sort()`, and `sorted()`

---
### Week 3. Control Flow in Python

Control flow defines the order in which statements are evaluated and executed in a program. In Python, indentation plays a crucial role in determining the control flow. In this week, we will discuss branching and iteration and how to write these in Python using `if`-`else` statements, `while` loops, `for` loops, `range()`, `break`, and `continue`. We will also introduce the extremely useful concept of list comprehensions. To exemplify the use of conditional statements and iteration, we will go over several simple numerical search and approximation algorithms.

*Readings*:
* Guttag. Chapters 2.2, 2.4–3, pp.15–18, 22–38.

*Lab*: **For Loops and List Comprehensions in Python**
* Control flow best practices and pitfalls
* Nested dictionary and list comprehensions

---
### Week 4. Functions in Python

Good programmers are not measured by the amount of code they write but by the amount of functionality in their code. Good programming relies on abstraction and decomposition. Decomposition creates structure while abstraction helps hide details. Decomposition and abstraction can be achieved with functions and classes and in this week, we will introduce functions. We will discuss function arguments and variable scope and by means of an example, we will introduce the concept of recursion.

*Readings*:
* Guttag. Chapter 4, pp.39–63.

*Lab*: **Writing and Calling Functions in Python**
* Function specification
* What are functions good for?

---
### Week 5. Classes in Python

Object-oriented programming is a programming paradigm that helps increase modularity, reduce complexity, and foster code reuse. Objects are a data abstraction consisting of (1) an internal representation i.e. object attributes and (2) an interface for interacting with the objects through methods and functions. Objects are instances of classes and classes determine the type of an object. In this week, we will discuss how to define classes in Python and how to create instances of a class. We will also touch upon class inheritance and hierarchies, as well as generators.

*Readings*:
* Guttag. Chapter 8, pp.109–134.

*Lab*: **Programming in Teams**
* Using GitHub as a collaboration tool

---
### Week 7. Testing and Debugging in Python

Writing computer programs is easy but making them work properly is hard. We test programs to check if they work as intended and we debug them when we find out that they don’t. In this lecture, we will discuss different ways to test and debug programs. We will cover common error messages and how to catch them with `try`, `except`, `raise`, and `assert`.

*Readings*:
* Guttag. Chapters 6–7, pp.85–108.

*Lab*: **Unit Testing, Exceptions, and Assertions in Python**
* Using .py files to structure programs and conduct testing
* Defensive programming with `try`, `except`, and `assert`

---
### Week 8. The R Programming Language

This week, we will review many concepts studied until now by learning how they are implemented in the R programming language. After a general introduction to R, we will discuss basic data structures. We will then continue with the control flow, a discussion of functions in R, and reading in data and plotting. We will conclude the lecture with an outlook on tools which are currently used in a typical data science workflow with R.

* [Lecture slides](wk8/my470-week08-r.pdf)

*Readings*:
* Venables, W. N. et. al.  2017.  [_An Introduction to R_](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf).  Chapters 1-6, 9-10.
* The [Introduction to R handout](wk8/Introductory_R.pdf).
* (optional, but recommended) Zuur, A., Ieno, E. N., & Meesters, E. (2009). _A Beginner's Guide to R_. Springer Science & Business Media.
* (optional) Patrick Burns.  2011.  _The R Inferno_.  http://www.burns-stat.com/pages/Tutor/R_inferno.pdf

*Lab*: **Vectorised operations**
* [R Markdown intro](wk8/01-rmarkdown.Rmd)
* [Exercises](wk8/02-exercises.Rmd)

---
### Week 9. Algorithms and Order of Growth

Algorithms are recipes that consist of a sequence of simple steps, control flow, and stopping rule. To evaluate the scalability of algorithms and to compare their efficiency, we use the abstraction “order of growth”. Order of growth expresses how the maximum amount of time needed grows as the size of the input grows. We will discuss different complexity classes and ways to analyze the complexity of programs.

*Readings*:
* Guttag. Chapter 9, pp.135–149.
* Bradley and Ranum. [Chapter 2](http://interactivepython.org/runestone/static/pythonds/AlgorithmAnalysis/toctree.html).

*Lab*: **Order of Growth**
* Reading programs written in Python and R and evaluating their time complexity

---
### Week 10. Searching and Sorting Algorithms

We will use the concepts and approaches introduced in the previous lecture to look at the complexity of several classic algorithms on searching and sorting. The goal is to get a better intuition of how to approach problems of efficiency. We will use examples written in both Python and R.   

*Readings*:
* Guttag. Chapter 10.1–10.2, pp.151–164.
* Bradley and Ranum. [Chapter 5](http://interactivepython.org/runestone/static/pythonds/SortSearch/toctree.html).

*Lab*: **Functional Programming in Python**
* `lambda`, `filter`, `map` and `reduce`


---
### Week 11. Graph Algorithms
We will continue getting a better understanding of abstract data types and computational complexity by covering stacks, queues, trees, graphs, and algorithms for graphs. The lecture will end with an overview of what we have learned in the course and possible steps you can take to further develop your programming skills.

*Readings*:
* Bradley and Ranum. [Chapter 4.1-4.14](https://runestone.academy/runestone/books/published/pythonds/BasicDS/toctree.html).
* Guttag. Chapter 12.2, pp.190–201.

*Lab*: **Useful Python Modules and Libraries**
* `datetime` and `pickle`
* `numpy`, `pandas`, `statsmodels`, `networkx`, `scikitlearn`
