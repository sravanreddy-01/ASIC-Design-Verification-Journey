# Day 4 - Binary Arithmetic and BCD

## Topics Covered

* Binary Addition
* Binary Subtraction
* Subtraction Using 2's Complement
* Binary Coded Decimal (BCD)
* Introduction to Gray Code

---

## Binary Addition

Binary addition follows the same concept as decimal addition but uses only 0 and 1.

### Rules

0 + 0 = 0

0 + 1 = 1

1 + 0 = 1

1 + 1 = 10

When 1 + 1 occurs:

Sum = 0

Carry = 1

### Example

1010

*

0110

=

10000

Decimal Verification:

10 + 6 = 16

---

## Binary Subtraction

Binary subtraction follows borrowing rules similar to decimal subtraction.

### Rules

0 - 0 = 0

1 - 0 = 1

1 - 1 = 0

0 - 1 requires borrowing

### Example

1010

*

0011

=

0111

Decimal Verification:

10 - 3 = 7

---

## Subtraction Using 2's Complement

Digital systems often perform subtraction using addition.

Formula:

A - B = A + (2's Complement of B)

### Example

10 - 3

10 = 1010

3 = 0011

2's Complement of 3:

0011

↓

1100

↓

1101

Addition:

1010

*

1101

=

10111

Ignoring the carry:

0111

Result = 7

---

## Binary Coded Decimal (BCD)

BCD represents each decimal digit separately using 4 bits.

### Example

Decimal Number:

45

BCD Representation:

4 = 0100

5 = 0101

Result:

0100 0101

---

### Example

Decimal Number:

79

BCD Representation:

7 = 0111

9 = 1001

Result:

0111 1001

---

## Applications of BCD

BCD is commonly used in:

* Digital Clocks
* Calculators
* Seven Segment Displays
* Financial Systems

---

## Introduction to Gray Code

Gray Code is a binary numbering system where consecutive numbers differ by only one bit.

Example:

000

001

011

010

110

111

101

100

Gray Code is cyclic because the last and first values also differ by only one bit.

---
---

## Gray Code

Gray Code is a binary numbering system where two consecutive values differ by only one bit.

This helps reduce errors during transitions in digital systems.

---

## Binary to Gray Code Conversion

### Rules

1. The MSB of Gray Code is the same as the MSB of Binary.
2. Each next Gray bit is found by XORing adjacent Binary bits.

### Formula

If Binary = B3 B2 B1 B0

Then Gray = G3 G2 G1 G0

G3 = B3  
G2 = B3 ⊕ B2  
G1 = B2 ⊕ B1  
G0 = B1 ⊕ B0  

### Example

Binary:

1011

Conversion:

G3 = 1  
G2 = 1 ⊕ 0 = 1  
G1 = 0 ⊕ 1 = 1  
G0 = 1 ⊕ 1 = 0  

Gray Code:

1110

So:

1011₂ = 1110 Gray

---

## Gray Code to Binary Conversion

### Rules

1. The MSB of Binary is the same as the MSB of Gray.
2. Each next Binary bit is found by XORing the previous Binary bit with the current Gray bit.

### Formula

If Gray = G3 G2 G1 G0

Then Binary = B3 B2 B1 B0

B3 = G3  
B2 = B3 ⊕ G2  
B1 = B2 ⊕ G1  
B0 = B1 ⊕ G0  

### Example

Gray Code:

1110

Conversion:

B3 = 1  
B2 = 1 ⊕ 1 = 0  
B1 = 0 ⊕ 1 = 1  
B0 = 1 ⊕ 0 = 1  

Binary:

1011

So:

1110 Gray = 1011₂

---

## Importance of Gray Code

Gray Code is important because only one bit changes between consecutive values.

This reduces transition errors in digital systems.

---

## Applications of Gray Code

- Rotary Encoders
- Position Sensors
- Digital Communication
- FSM State Encoding
- Error Reduction in Digital Circuits

---

## Key Point

Binary values may change multiple bits between consecutive numbers, but Gray Code changes only one bit.

Example:

Binary transition:

011 → 100

Here, 3 bits change.

Gray Code transition:

010 → 110

Here, only 1 bit changes.

## Important Interview Questions

1. What is binary addition?
2. What is binary subtraction?
3. How is subtraction performed using 2's complement?
4. What is BCD?
5. Why is BCD used?
6. What is Gray Code?
7. Why is Gray Code called cyclic?
8. Where is Gray Code used?

---

## Key Takeaways

Today I learned binary arithmetic operations including addition and subtraction. I also learned how digital systems perform subtraction using 2's complement addition. In addition, I understood the concept of Binary Coded Decimal (BCD) and the basic idea behind Gray Code.
