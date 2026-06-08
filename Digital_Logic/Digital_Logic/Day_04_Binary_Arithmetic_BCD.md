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
