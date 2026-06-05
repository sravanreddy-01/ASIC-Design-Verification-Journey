# Day 3 - Complements and Number Representations

## Topics Covered

* 1's Complement
* 2's Complement
* 1's Complement Representation
* 2's Complement Representation
* Difference Between Complement and Representation
* Interpreting 2's Complement Numbers

---

## Key Learning

Today I learned that finding the 1's or 2's complement of a binary number is different from representing a negative number using 1's or 2's complement representation.

Although the final binary result may sometimes be the same, the question and thought process are different.

---

## 1's Complement

1's complement is obtained by inverting all bits.

Example:

00010110

↓

11101001

---

## 2's Complement

2's complement is obtained by:

1. Finding the 1's complement.
2. Adding 1.

Example:

00010110

↓

11101001

↓

11101010

---

## Representing Negative Numbers

To represent a negative number:

1. Convert the positive number into binary.
2. Find its 2's complement.

Example: Represent -22

+22

00010110

1's complement

11101001

Add 1

11101010

Therefore:

-22 = 11101010

---

## Interpreting a 2's Complement Number

Example:

11110011

MSB = 1, therefore the number is negative.

Find its magnitude:

11110011

↓

00001100

↓

00001101

Decimal value = 13

Therefore:

11110011 = -13

---

## Important Observation

The following three questions may have the same binary answer but are conceptually different:

1. Find the 2's complement of 00001101.
2. Represent -13 using 8-bit 2's complement.
3. Interpret 11110011 as an 8-bit 2's complement number.

Understanding the difference between these questions is very important.

---

## Important Values

8-bit Unsigned Range:

0 to 255

8-bit Signed Magnitude Range:

-127 to +127

8-bit 2's Complement Range:

-128 to +127

---

## Interview Questions

1. What is 1's complement?
2. What is 2's complement?
3. Why is 2's complement preferred?
4. What is the range of 8-bit 2's complement numbers?
5. How do you represent a negative number using 2's complement?
6. How do you interpret a 2's complement number?

---

## My Notes

Today I understood the difference between finding complements, representing negative numbers, and interpreting 2's complement values. This was the most important takeaway from the session.
