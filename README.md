# CS 101: Introduction to Programming with Python

**Course Syllabus**

> A first course in computer science. No prior programming experience is
> assumed; if you have written code before, this course will deepen and
> formalize what you already know.

---

## Course Information

| | |
|---|---|
| **Course number** | CS 101 |
| **Title** | Introduction to Programming with Python |
| **Credits** | 3 |
| **Level** | Undergraduate, first year |
| **Format** | Lecture + supervised lab; three lessons per module |
| **Offered** | Fall and Spring |

This is an open course. Every textbook on the reading list is available free
online, and the teaching materials below are released under a Creative
Commons license so you may keep, remix, and reuse them.

---

## Course Description

CS 101 introduces the science of computation through the Python programming
language. Students learn to think algorithmically and to express those ideas
as correct, readable programs. The course begins with the mechanics of the
language, moves through fundamental control structures and functions, and
finishes by composing small programs that read data, make decisions, and
automate real work.

Python is chosen for three reasons: it reads close to English, it is used
seriously in industry and research, and it is free. Everything you need to
follow this course can be installed on your own machine in a few minutes, and
several of the assigned books can be completed entirely in a browser.

## Prerequisites

- High-school algebra.
- Comfort using a computer: opening applications, creating files, and using a
  browser. No programming or terminal experience required.

## Learning Outcomes

By the end of this course, a successful student will be able to:

1. Explain what a program is and trace how the Python interpreter executes
   simple statements.
2. Write programs that store and manipulate data using the core types
   (numbers, strings, booleans, lists, dictionaries).
3. Use conditions and loops to make a program that branches and repeats.
4. Define and call functions, and explain the difference between a function
   and a procedure.
5. Read and write text files, and work with data structures to solve small,
   realistic problems.
6. Debug programs by reading error messages and testing incrementally.

---

## Open Textbooks

A dozen free, high-quality books follow, ordered from the most beginner
friendly to the most challenging. All are readable online in a browser; most
also offer PDF and EPUB editions. Pick one as your primary text and use the
others for reference or a different voice.

### Part A: Foundations (start here)

1. **Think Python, 3rd Edition (Interactive)** by Allen B. Downey
   <https://allendowney.github.io/ThinkPython/>
   The course's primary text. Short chapters, lots of small examples, and a
   running series of exercises. The interactive edition runs directly in the
   browser, so you can edit and execute code as you read.

2. **Python for Everybody (PY4E)** by Dr. Charles Severance
   <https://www.py4e.com/book>
   A data-oriented introduction aimed at readers with no programming
   background. Every chapter pairs with a video lecture; the site includes
   autograded exercises and a practice quiz per chapter.

3. **How to Think Like a Computer Scientist: Interactive Edition** (Runestone)
   <https://runestone.academy/ns/books/published/thinkcspy/index.html>
   A community-maintained, fully interactive version of the classic text, with
   embedded code blocks, coloring, and auto-graded exercises. Excellent if you
   prefer to practice as you read.

4. **A Byte of Python** by Swaroop C. H.
   <https://python.swaroopch.com/>
   A short, friendly primer intended for total beginners. Good first read if a
   big textbook feels intimidating; it covers the essential language features
   in a weekend's reading.

5. **Think Python, 2nd Edition** by Allen B. Downey (Green Tea Press)
   <https://greenteapress.com/wp/think-python-2e/>
   The earlier edition of the primary text, available free under a Creative
   Commons license. Use it if you prefer a more traditional print-style layout
   or the older chapter numbering referenced in some archives.

### Part B: Applications and practice

6. **Automate the Boring Stuff with Python, 3rd Edition** by Al Sweigart
   <https://automatetheboringstuff.com/>
   Practical programming for total beginners. Where most texts stop at
   language features, this one shows you how to do real work: rename files,
   scrape web pages, fill out forms, and work with spreadsheets. The free
   online edition is the canonical version.

7. **Invent Your Own Computer Games with Python, 4th Edition** by Al Sweigart
   <https://inventwithpython.com/invent4thed/>
   Learn by building games. Each chapter presents the complete source code for
   a small game (Guess the Number, Hangman, Tic Tac Toe) and teaches the
   underlying concepts from the example. A great way to stay motivated.

8. **Dive Into Python 3** by Mark Pilgrim
   <https://diveintopython3.net/>
   A book for people who already know how to program in another language and
   want to pick up Python 3 quickly. Strong on strings, comprehensions,
   generators, and working with files and web services.

### Part C: Reference and depth

9. **The Coder's Apprentice** by Pieter Spronck
   <https://spronck.net/pythonbook>
   A thorough course book written for readers with no prior programming
   knowledge. Numerous exercises per chapter, end-of-chapter summaries, and
   downloadable code listings. Free as a PDF.

10. **How to Think Like a Computer Scientist** (Open Book Project edition)
    <https://www.openbookproject.net/thinkcs/python/english2e/>
    The original openly licensed edition, stable and complete, with a simple
    chapter-per-page layout. Useful as a second, quietly-archived reference.

11. **Python Programming** (Wikibooks)
    <https://en.wikibooks.org/wiki/Python_Programming>
    A community-written reference that covers the language and standard
    library in depth. Not a linear tutorial, but the best place to look up a
    specific topic quickly.

12. **The Python Tutorial** (official)
    <https://docs.python.org/3/tutorial/>
    The language's own tutorial, maintained by the Python Software Foundation.
    Authoritative and concise; the final authority for any syntax question.

### How to choose

- Reading nothing but one Part A book is enough to pass.
- Add one Part B book if you want projects that do something visible.
- Keep a Part C book open while you code; it answers the "wait, is there a
  built-in for this?" questions.

---

## Tools and Environment

- **Python 3.12 or newer.** Install from <https://python.org/>. This course
  uses Python 3; Python 2 is not supported.
- A text editor or IDE of your choice. Any editor works; VS Code, PyCharm
  Community, and Thonny are common choices.
- If you cannot install software, use an online environment such as the
  Runestone textbook's built-in interpreter or thinkpython's Colab notebooks.
- **A terminal.** Several readings assume you can run `python3 script.py` from
  a command line. Getting comfortable with the terminal is part of the
  course's outcome.

### Running your first program

Create a file named `hello.py` containing:

```python
print("Hello, world!")
```

Then, from a terminal in the same directory:

```
python3 hello.py
```

If you see `Hello, world!` printed, your environment is ready.

---

## Lessons

The course is organized into three lessons, each building on the last. Work
through them in order. Each lesson is self-contained: a set of objectives,
assigned reading, the core concepts with worked examples, and a short
assignment.

### Lesson 1: Programs, Variables, and Expressions

**Objectives** After this lesson you can: distinguish between a value, an
expression, and a statement; use Python's interactive shell; store data in
variables; and write arithmetic and string expressions.

**Reading**

- *Think Python 3e*, Chapters 1 and 2.
- *A Byte of Python*, "First Steps" and "Operators and Expressions".
- *The Python Tutorial*, sections 1 through 3.

**Key ideas**

- A **value** is a piece of data: `5`, `"hello"`, `True`.
- A **variable** is a name that refers to a value: `x = 5`.
- An **expression** is a combination of values, variables, and operators that
  evaluates to a value: `x + 3`.
- A **statement** is an instruction the interpreter runs: `print(x)`.
- **Types** matter: `7 + 3` is `10`, but `"7" + "3"` is `"73"`.

**Worked example**

```python
name = "Ada"
age = 36
print(name + " is " + str(age) + " years old.")
print(age * 12, "months")
```

**Practice** In the shell, predict the value of each of these before running
them, then check yourself:

```python
5 // 2
5 % 2
2 ** 10
"ab" * 3
0.1 + 0.2
```

**Assignment 1** Write a program that converts a temperature in Celsius to
Fahrenheit using `F = C * 9 / 5 + 32`. Read the Celsius value from a variable
you set at the top of the file, and print both the Celsius and the Fahrenheit
values to the nearest tenth.

---

### Lesson 2: Decisions and Repetition

**Objectives** After this lesson you can: make a program take different paths
with `if`/`elif`/`else`; repeat work with `for` and `while` loops; use
`range` to loop a known number of times; and write a boolean expression.

**Reading**

- *Think Python 3e*, Chapters 3 and 4.
- *Python for Everybody*, Chapters 3 and 4.
- *The Python Tutorial*, section 4.

**Key ideas**

- A **boolean expression** is `True` or `False`: `age >= 18`.
- **Conditional execution** picks a path based on a boolean:
  ```python
  if score >= 90:
      print("A")
  elif score >= 80:
      print("B")
  else:
      print("C")
  ```
- A **loop** repeats a block. Use `for` when you know how many times; use
  `while` when you repeat until a condition changes.
  ```python
  for n in range(5):
      print(n)

  n = 0
  while n < 5:
      print(n)
      n += 1
  ```

**Worked example**

```python
total = 0
for n in range(1, 101):
    total += n
print("The sum of 1..100 is", total)
```

**Practice** Write a loop that prints every even number from 2 to 20. Then
write a `while` loop that counts down from 5 to 1 and prints "Go!" at the end.

**Assignment 2** Write a program that asks how many integers it should read
(use `input()`), reads that many integers, and then prints the largest and
the smallest. Handle the case where the user enters zero numbers without an
error.

---

### Lesson 3: Functions and Structured Problem Solving

**Objectives** After this lesson you can: define a function with `def`; pass
arguments and return values; explain the difference between a function that
returns a value and one that produces a side effect; and break a problem into
small, testable functions.

**Reading**

- *Think Python 3e*, Chapter 5.
- *The Coder's Apprentice*, "Functions" and "Simple Functions".
- *Python for Everybody*, Chapter 4.

**Key ideas**

- A **function** is a named block of code you can call:
  ```python
  def greet(name):
      return "Hello, " + name
  ```
- A **returned value** can be used in an expression; a **side effect** (like
  printing) happens but is not a value.
- Functions let you write a program once and reuse it, and they are the
  smallest unit worth unit testing.
- **Scope** matters: variables defined inside a function are local to it.

**Worked example**

```python
def is_odd(n):
    return n % 2 != 0

def classify(n):
    if is_odd(n):
        return "odd"
    return "even"

for n in range(1, 6):
    print(n, classify(n))
```

**Practice** Write a function `average(a, b)` that returns the average of two
numbers. Then write `average_list(nums)` that takes a list and returns its
average. Both should be usable from a `main()` that prints a couple of test
cases.

**Assignment 3** Write a small program with at least three functions that
computes a simple grade report. Read a list of scores (each 0 to 100), compute
the average, assign a letter grade, and print a one-line summary per student.
Keep the input reading, the grade computation, and the printing in separate
functions so each can be tested on its own.

---

## Course Schedule (14 weeks)

| Week | Topic | Lesson |
|------|-------|--------|
| 1 | What is a program; installing Python | Lesson 1 |
| 2 | Values, variables, expressions, types | Lesson 1 |
| 3 | Input, output, and the interactive shell | Lesson 1 |
| 4 | Strings and string methods | Lesson 1 |
| 5 | Booleans and comparisons | Lesson 2 |
| 6 | Conditional execution (`if`/`elif`/`else`) | Lesson 2 |
| 7 | `for` loops and `range` | Lesson 2 |
| 8 | `while` loops and loop patterns | Lesson 2 |
| 9 | Defining functions, arguments, return values | Lesson 3 |
| 10 | Scope and local variables | Lesson 3 |
| 11 | Lists and recursion (introduction) | Lesson 3 |
| 12 | Files and reading data | Lesson 3 |
| 13 | Putting it together: a graded project | Lesson 3 |
| 14 | Review and final project presentations | All |

---

## Assessment

| Component | Weight |
|-----------|--------|
| Three lessons (assignments 1, 2, 3) | 45% |
| Weekly short quizzes | 15% |
| Midterm | 20% |
| Final project | 20% |

**Grading scale:** A 93+, A- 90, B+ 87, B 83, B- 80, C+ 77, C 73, C- 70, D 60,
F below 60.

---

## Course Policies

### Late work

Assignments are due at the start of the week in which they appear. Late work
is accepted for one week with a 10% penalty per day, unless an extension was
arranged in advance for a documented reason.

### Collaboration

You are encouraged to discuss concepts with classmates. However, the code you
submit must be your own. Copying another student's work, or submitting the
output of an automated tool without understanding it, is a violation of the
academic integrity policy and will be treated as such.

### Academic integrity

All work submitted for a grade must be your own. Sharing or receiving answer
files is not permitted. If you use material from outside this course, cite it.
When in doubt, ask.

### Accessibility

This course is designed to be open and usable by everyone. All required
reading is free and available online. If you need an accommodation, contact
the instructor early in the term so it can be arranged.

---

## Resources

- **Official Python documentation:** <https://docs.python.org/3/>
- **Python tutorial:** <https://docs.python.org/3/tutorial/>
- **Python on this course's machine:** everything runs through `python3`; the
  same code works on Windows, macOS, and Linux.
- **Community help:** the `#learnpython` channels are generally friendly to
  beginners. Describe what you expected, what happened, and include the exact
  error message.

---

*This syllabus is offered as open course material. You are free to copy,
adapt, and redistribute it for non-commercial teaching use under the terms of
the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 license. The
books listed above retain their own licenses as noted by their authors.*
