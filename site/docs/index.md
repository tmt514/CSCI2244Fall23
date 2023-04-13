# Syllabus

## CSCI 2244 Randomness and Computation

Welcome to the class page!
You can find most of course-related materials here.

## References

### Textbook

We will use the book written by [Professor Sergio A. Alvarez](http://cs.bc.edu/~alvarez/) as the main textbook.

### Supplementary Readings

* [Grinsted](http://www.swarthmore.edu/NatSci/cgrinst1/) and [Snell](https://en.wikipedia.org/wiki/J._Laurie_Snell)'s Introduction to Probability [[pdf]](https://math.dartmouth.edu/~prob/prob/prob.pdf) [[page]](https://chance.dartmouth.edu/teaching_aids/books_articles/probability_book/book.html)

## Grading

* 40% Homeworks: There will be 12 problem sets, and each problem set is released at least 168 hours before due.
The highest 9 PS scores count towards to your homework grade. The typical deadline is 10PM (ET) but I allow submissions up to 11:59PM (ET) on the same day. <b>I do not accept submissions later than 11:59PM. This is a hard constraint, no excuse, sorry.</b> (That's why we dropped 3 PS scores!)
* 15% Exam 1.
* 15% Exam 2.
* 30% Exam 3 (Optional: 15% Exam 3 + 15% Final Project).

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

* We will need a little bit of MATH 1101/1102 (<b>Calculus I/II</b>). For example, please don't be afraid with the symbols in the following expression:

$$ \int_{-\infty}^\infty e^{-x^2} \, \mathrm{d}{x} = \sqrt{\pi}. $$

* The longer time you stare at it, the more comfortable you will be (<s>no, not at all</s>).

## How To Success

!!! tip "Quote from Prof. Alvarez"

    The not-so-secret recipe for doing well on the exams is to work diligently on the problem sets and to stay up to date on the course material.


## Schedule and Plans

{{ read_excel('./syllabus.xlsx', engine='openpyxl', colalign=("center",), keep_default_na=False) }}


