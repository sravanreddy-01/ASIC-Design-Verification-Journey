# Day 8 - Karnaugh Maps (K-Maps)

## Topics Covered

* Introduction to Karnaugh Maps
* K-Map Cell Organization
* Gray Code Arrangement
* 2 Variable K-Maps
* 3 Variable K-Maps
* 4 Variable K-Maps
* Grouping Rules
* Pair, Quad and Octet Formation
* Boolean Expression Simplification using K-Maps

---

## What is a K-Map?

A Karnaugh Map (K-Map) is a graphical method used to simplify Boolean expressions.

K-Maps help reduce the number of logic gates required to implement a circuit.

Benefits:

* Simplified Boolean Expressions
* Reduced Hardware Complexity
* Reduced Area
* Reduced Power Consumption

---

## Number of Cells in a K-Map

For n variables:

Number of Cells = 2ⁿ

Examples:

2 Variables → 4 Cells

3 Variables → 8 Cells

4 Variables → 16 Cells

5 Variables → 32 Cells

---

## Gray Code Organization

K-Maps are arranged using Gray Code.

Example Order:

00

01

11

10

Gray Code is used because adjacent cells differ by only one bit.

This allows proper grouping and simplification.

---

## K-Map Types

### 2 Variable K-Map

Contains 4 cells.

Used for simple Boolean functions.

---

### 3 Variable K-Map

Contains 8 cells.

Used for medium complexity Boolean functions.

---

### 4 Variable K-Map

Contains 16 cells.

Commonly used in Digital Logic Design.

---

## Grouping Rules

Valid Groups:

1 Cell

2 Cells

4 Cells

8 Cells

16 Cells

Invalid Groups:

3 Cells

5 Cells

6 Cells

7 Cells

---

## Important Rule

Always create the largest possible groups.

Larger groups eliminate more variables and produce simpler Boolean expressions.

---

## Corner Cell Adjacency

Corner cells are considered adjacent.

This is one of the most important K-Map concepts.

A cell can be adjacent to:

* Left
* Right
* Top
* Bottom

including wrap-around adjacency.

---

## Pair Grouping

A pair consists of 2 adjacent 1s.

Pair grouping eliminates one variable.

---

## Quad Grouping

A quad consists of 4 adjacent 1s.

Quad grouping eliminates two variables.

---

## Octet Grouping

An octet consists of 8 adjacent 1s.

Octet grouping eliminates three variables.

---

## Purpose of K-Maps

K-Maps are used to:

* Simplify Boolean Expressions
* Reduce Number of Gates
* Reduce Circuit Complexity
* Improve Digital Circuit Design

---

## Important Interview Questions

1. What is a Karnaugh Map?
2. Why is Gray Code used in K-Maps?
3. How many cells are present in a 4-variable K-Map?
4. Can a K-Map group contain 6 cells?
5. Why should larger groups be preferred?
6. Are corner cells adjacent?
7. What is the purpose of K-Maps?
8. How many cells exist for n variables?

---

## Key Takeaways

Today I learned Karnaugh Maps and their use in simplifying Boolean expressions. I learned K-Map organization using Gray Code, grouping rules, corner adjacency, and how larger groups help create simpler digital circuits.
