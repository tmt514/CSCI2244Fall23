# Syllabus

## CSCI 2244 Randomness and Computation

Welcome to the class page!
You can find most of course-related materials here.

## Staff and Office Hours

* Instructor: [Shang-En Huang](https://tmt514.github.io/).
    * Office Hours: Monday 4-5pm; Friday 10-11am; other times request by email.
    * Location: 428G.
* Teaching Assistant: **TBD**.
* Teaching Assistant: **TBD**.

## References

### Textbook

We will use the book written by [Professor Sergio A. Alvarez](http://cs.bc.edu/~alvarez/) as the main textbook.

### Supplementary Readings

* [Grinsted](http://www.swarthmore.edu/NatSci/cgrinst1/) and [Snell](https://en.wikipedia.org/wiki/J._Laurie_Snell)'s Introduction to Probability [[pdf]](https://math.dartmouth.edu/~prob/prob/prob.pdf) [[page]](https://chance.dartmouth.edu/teaching_aids/books_articles/probability_book/book.html)
* Professor [Howard Straubing](http://www.cs.bc.edu/~straubin/)'s [CSCI2244-Spring2019 Course Site](http://www.cs.bc.edu/~straubin/csci2244-2019/syllabus.html)
* Professor [Sergio A. Alverez](http://cs.bc.edu/~alvarez/)'s [CSCI2244-Spring2023 Course Site](http://cs.bc.edu/~alvarez/Randomness)

## Grading

* 27% Homeworks: There will be 12 problem sets.
The highest 9 PS scores count towards to your homework grade.
* 18% Exam 1. (50 minutes)
* 18% Exam 2. (50 minutes)
* 36% Exam 3. (2 hours)
* 1% if I can recognize you at the end of the semester.

## Homeworks

There will be 12 problem sets, and each problem set is released at least 168 hours before due.
The typical deadline is 10PM (ET) but I allow submissions up to 11:59PM (ET) on the same day. <b>I do not accept submissions later than 11:59PM. This is a hard constraint, no excuse, sorry.</b> (That's why we dropped 3 PS scores!)

Each homework is worth of 20 points, and usually consists of three parts:

1. Writing Assignments (Mostly Mathematical Proofs). (12 points)
2. Canvas Quizzes. (4 points)
3. Programming Assignments. (4 points)

Occasionally there are bonus questions. However, bonus questions are usually significantly more challenging, and require much more effort.


### Typesetting Your Homework Submissions

All mathematical expressions **must be typesetted**.
A badly typesetted submission could get a [desk-rejection](https://en.wikipedia.org/wiki/Scholarly_peer_review#:~:text=At%20this%20phase%20many%20articles%20receive%20a%20%22desk%20reject%22%2C%20that%20is%2C%20the%20editor%20chooses%20not%20to%20pass%20along%20the%20article.%20The%20authors%20may%20or%20may%20not%20receive%20a%20letter%20of%20explanation.)
without any credit.
The easiest way to typeset the homeworks in this course is to use [LaTeX](https://en.wikipedia.org/wiki/LaTeX).
We will provide LaTeX templates for each homework assignment
and you can utilize [Overleaf](https://www.overleaf.com/) to write down the solutions.

### IPython Notebooks

All programming assignments will be in the **IPython Notebook format**(`.ipynb`).
We highly recommend you to install [Jupyter Notebook](https://ipython.org/notebook.html) on your computer.
However, installing Jupyter Notebook locally is not necessary.
Sometimes there could be technical issues (that would be good learning experiences for the hardcore CS stuff).
If you encounter such a situation right before the homework deadlines, there are other options for you.
For example, you can utilize [Google Colab](https://colab.research.google.com/) which provides basic computing resources in ipython format that suit our needs.


## Exams

* Closed book exams.
* I will provide one **common info sheet** and unlimited scratch papers for you.
* You are allowed to bring 1 page (2-sided) of **hand written** cheat sheet.

## Academic Honesty

You should be responsible for all the mathematical works and the submitted codes.
Please read the [Boston College academic integrity policy](https://www.bc.edu/bc-web/academics/sites/university-catalog/policies-procedures.html#tab-academic_integrity_policies).
Dishonest behaviors may be reported and then reviewed by the Academic Integrity Board.

## Services for Students with Disabilities

Please see [this page](https://www.bc.edu/content/bc-web/offices/student-affairs/sites/dean-of-students/disability-services.html) for the students with disabilities who need help.

## Wellness

Your health and well-being are important!
Please be aware that Boston College provides
a range of support services for students who need help on mental health.
Please see [this page](https://www.bc.edu/content/bc-web/offices/student-affairs/sites/counseling.html).


## Prerequisites

``` mermaid
graph LR
  subgraph prerequisite
    direction TB
    A(CSCI 2243 <br/><b>Logic and Computation</b>) -.-|OR| C(MATH 2216 <br/><b>Intro to abstract Math</b>)
  end
  P(CSCI 1101 <br/><b>Computer Science I</b>) --> prerequisite
  prerequisite --> D(CSCI 2244 <br/><b>Randomness and Computation</b>)
  click C "http://fmwww.bc.edu/gross/MATH2216/" "A good resource to MATH 2216."
```

* We will need a little bit of MATH 1101/1102 (<b>Calculus I/II</b>). For example, please don't be afraid of the symbols in the following expression:

$$ \int_{-\infty}^\infty e^{-x^2} \, \mathrm{d}{x} = \sqrt{\pi}. $$

* The longer time you stare at it, the more comfortable you will be (<s>no, not at all</s>).
* If your CS1 course did not use Python, don't worry! Python will be very easy to learn after getting all concepts from CS1. See [https://docs.python.org/tutorial/](https://docs.python.org/tutorial/) to get started.

## How To Success

!!! tip "Quote from Prof. Alvarez"

    The not-so-secret recipe for doing well on the exams is to work diligently on the problem sets and to stay up to date on the course material.


## Schedule and Plans

{{ read_excel('./syllabus.xlsx', engine='openpyxl', colalign=("center","center",), keep_default_na=False) }}


