# Day 10 - Multiplexers (MUX) and Shannon Expansion Theorem

## Topics Covered

* XOR Properties
* Cascading of XNOR Gates
* Multiplexers (MUX)
* 2:1 Multiplexer
* 4:1 Multiplexer
* MUX Output Equations
* Shannon Expansion Theorem
* Higher Order MUX Implementation

---

## XOR Properties

### Property 1

A ⊕ A = 0

### Property 2

A ⊕ 0 = A

### Property 3

A ⊕ 1 = A'

### Property 4

If:

A ⊕ B = C

Then:

A ⊕ C = B

and

B ⊕ C = A

---

**XNOR Cascading**

XNOR cascading has different behavior compared to XOR.

The output depends on whether an even or odd number of inputs are equal.

Examples:

A ⊙ B

A ⊙ B ⊙ C

A ⊙ B ⊙ C ⊙ D

During class, special emphasis was given to XNOR cascading behavior and how parity relationships change when additional inputs are added.

XNOR gates are commonly used in:

Equality Comparators
Error Detection Circuits
Digital Comparison Logic

## Multiplexer (MUX)

A Multiplexer is a combinational circuit that selects one of many inputs and forwards it to a single output.

MUX is also called:

Data Selector

---

## Structure of Multiplexer

For n select lines:

Number of Data Inputs = 2ⁿ

Number of Outputs = 1

Examples:

2:1 MUX

* 2 Data Inputs
* 1 Select Line
* 1 Output

4:1 MUX

* 4 Data Inputs
* 2 Select Lines
* 1 Output

8:1 MUX

* 8 Data Inputs
* 3 Select Lines
* 1 Output

---

## 2:1 Multiplexer

Inputs:

I0, I1

Select Line:

S

Output:

Y

### Output Equation

Y = S'I0 + SI1

Operation:

If S = 0 → Output = I0

If S = 1 → Output = I1

---

## 4:1 Multiplexer

Inputs:

I0, I1, I2, I3

Select Lines:

S1, S0

Output:

Y

### Output Equation

Y = S1'S0'I0 + S1'S0I1 + S1S0'I2 + S1S0I3

---

## Shannon Expansion Theorem

Any Boolean function can be expressed using a selected variable and its complement.

Formula:

F = X'F(X=0) + XF(X=1)

Where:

F(X=0) = Function value when X = 0

F(X=1) = Function value when X = 1

---

## Importance of Shannon Expansion

* Used for MUX Realization
* Used for Logic Design
* Simplifies Complex Boolean Functions

---

## Higher Order MUX Using Lower Order MUX

Higher-order multiplexers can be built using lower-order multiplexers.

Examples:

### 4:1 MUX using 2:1 MUX

Requires:

* 3 Two-to-One MUXes

### 8:1 MUX using 2:1 MUX

Requires:

* 7 Two-to-One MUXes

This follows a tree structure.

---

## Applications of Multiplexers

* Data Routing
* Communication Systems
* Processor Design
* Digital Systems
* Logic Function Implementation

---

## Important Interview Questions

1. What is a Multiplexer?
2. Why is a MUX called a Data Selector?
3. What is the output equation of a 2:1 MUX?
4. How many select lines are required for a 4:1 MUX?
5. How many data inputs exist in an 8:1 MUX?
6. What is Shannon Expansion Theorem?
7. Why is Shannon Expansion important?
8. How can a 4:1 MUX be implemented using 2:1 MUXes?
9. What are the applications of MUX?
10. State some XOR properties.

---

## Key Takeaways

Today I learned XOR properties, XOR cascading concepts, Multiplexers (MUX), output equations for 2:1 and 4:1 MUXes, Shannon Expansion Theorem, and the implementation of higher-order multiplexers using lower-order multiplexers.
