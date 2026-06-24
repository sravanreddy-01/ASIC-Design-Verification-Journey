# Day 12 - Encoders, Priority Encoders, Subtractors and Comparators

## Topics Covered

* Encoder
* Priority Encoder
* Half Subtractor
* Full Subtractor
* Comparator
* Magnitude Comparator
* Truth Tables
* Output Equations
* Circuit Design Concepts

---

## Encoder

An Encoder is a combinational circuit that converts an active input line into a binary code.

For n output lines:

Number of Inputs = 2ⁿ

Examples:

### 4:2 Encoder

* 4 Inputs
* 2 Outputs

### 8:3 Encoder

* 8 Inputs
* 3 Outputs

---

## Working Principle

Only one input should be active at a time.

The encoder generates the corresponding binary code at the output.

---

## Priority Encoder

A Priority Encoder resolves conflicts when multiple inputs are active simultaneously.

The highest-priority active input is selected and encoded.

Benefits:

* Eliminates ambiguity
* Used in interrupt systems
* Used in processor control logic

---

## Half Subtractor

A Half Subtractor performs subtraction of two single-bit inputs.

Inputs:

* A
* B

Outputs:

* Difference
* Borrow

### Equations

Difference = A ⊕ B

Borrow = A'B

---

## Full Subtractor

A Full Subtractor performs subtraction of three bits:

* A
* B
* Borrow In

Outputs:

* Difference
* Borrow Out

Used in multi-bit subtraction circuits.

---

## Comparator

A Comparator compares two binary numbers.

It determines:

* A > B
* A = B
* A < B

---

## Magnitude Comparator

A Magnitude Comparator compares the magnitude of two binary numbers.

Typical Outputs:

* Greater Than
* Equal To
* Less Than

Only one output remains active at a time.

---

## Applications

### Encoder

* Keyboard Encoding
* Interrupt Handling
* Data Compression

### Priority Encoder

* Processor Interrupt Systems
* Arbitration Logic

### Subtractor

* Arithmetic Logic Units (ALU)
* Digital Processors

### Comparator

* Sorting Systems
* Digital Measurement Systems
* Decision Making Circuits

---

## Important Interview Questions

1. What is an Encoder?
2. What is the difference between Encoder and Decoder?
3. What is a Priority Encoder?
4. Why is a Priority Encoder required?
5. What is a Half Subtractor?
6. What is the Borrow output equation?
7. What is a Full Subtractor?
8. What is a Comparator?
9. What are the outputs of a Magnitude Comparator?
10. Where are Comparators used?

---

## Key Takeaways

Today I learned Encoder circuits, Priority Encoders, Half and Full Subtractors, Comparator circuits, Magnitude Comparators, their truth tables, output equations, and applications in digital systems.
