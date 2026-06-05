# Day 2 - Signed and Unsigned Number Representations

## Topics Covered

* Floating Point Basics
* Nibble
* Byte
* Word
* Signed Numbers
* Unsigned Numbers
* Signed Magnitude Representation
* 1's Complement
* 2's Complement
* Range Calculations

---

## Floating Point Numbers

Floating point numbers are used to represent decimal values.

Examples:

* 3.14
* 0.625
* -10.75

Integers are stored as binary values, while decimal numbers are stored using floating point representation.

---

## Nibble, Byte and Word

### Nibble

A nibble consists of 4 bits.

Example:

1010

### Byte

A byte consists of 8 bits.

Example:

10101100

### Word

A word is a group of bits processed together by the processor.

Traditionally:

* 16 bits

Modern systems:

* 32-bit processor → 32-bit word
* 64-bit processor → 64-bit word

---

## Unsigned Numbers

All bits are used to represent magnitude.

Formula:

Minimum = 0

Maximum = 2ⁿ - 1

Examples:

4-bit unsigned:
0 to 15

8-bit unsigned:
0 to 255

---

## Signed Magnitude Representation

The Most Significant Bit (MSB) is used as the sign bit.

0 → Positive

1 → Negative

Examples:

00000101 = +5

10000101 = -5

Range Formula:

-(2ⁿ⁻¹ - 1) to +(2ⁿ⁻¹ - 1)

Examples:

4-bit:
-7 to +7

8-bit:
-127 to +127

Note:
Signed magnitude has two representations for zero.

+0 = 00000000

-0 = 10000000

---

## 1's Complement

1's complement is obtained by inverting all bits.

Example:

00000101

↓

11111010

This is the 1's complement of 5.

---

## 2's Complement

Steps:

1. Find 1's complement.
2. Add 1.

Example:

00000101

1's complement:

11111010

Add 1:

11111011

Result:

11111011 represents -5.

---

## Why 2's Complement is Used

* Only one representation for zero
* Easier arithmetic operations
* Simpler hardware implementation
* Used in modern processors and digital systems

---

## Important Ranges

4-bit Unsigned:
0 to 15

4-bit Signed Magnitude:
-7 to +7

4-bit 2's Complement:
-8 to +7

8-bit Unsigned:
0 to 255

8-bit Signed Magnitude:
-127 to +127

8-bit 2's Complement:
-128 to +127

---

## Interview Questions

1. What is a nibble?
2. What is a byte?
3. What is a word?
4. What is 1's complement?
5. What is 2's complement?
6. Why is 2's complement preferred?
7. What is the range of 8-bit signed magnitude numbers?
8. What is the range of 8-bit 2's complement numbers?

---

## My Notes

Today I learned how negative numbers are represented in digital systems using signed magnitude, 1's complement and 2's complement representations. I also understood why 2's complement is preferred in modern computers.
