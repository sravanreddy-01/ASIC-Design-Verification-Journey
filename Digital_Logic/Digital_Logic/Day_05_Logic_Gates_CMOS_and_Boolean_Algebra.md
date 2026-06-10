# Day 5 - Logic Gates, CMOS and Boolean Algebra

## Topics Covered

* Logic Gates
* Truth Tables
* Boolean Expressions
* CMOS Inverter
* CMOS NAND Gate
* CMOS NOR Gate
* SSI, MSI, LSI and VLSI
* Boolean Algebra Laws
* De Morgan's Theorem
* Boolean Expression Simplification

---

## Basic Logic Gates

### AND Gate

Boolean Expression:

Y = A.B

Truth Table:

A B | Y

0 0 | 0

0 1 | 0

1 0 | 0

1 1 | 1

Rule:

Output is 1 only when all inputs are 1.

---

### OR Gate

Boolean Expression:

Y = A + B

Truth Table:

A B | Y

0 0 | 0

0 1 | 1

1 0 | 1

1 1 | 1

Rule:

Output is 1 if at least one input is 1.

---

### NOT Gate

Boolean Expression:

Y = A'

Truth Table:

A | Y

0 | 1

1 | 0

Rule:

Produces the complement of the input.

---

### NAND Gate

Boolean Expression:

Y = (A.B)'

Rule:

Output is 0 only when all inputs are 1.

Universal Gate.

---

### NOR Gate

Boolean Expression:

Y = (A+B)'

Rule:

Output is 1 only when all inputs are 0.

Universal Gate.

---

### XOR Gate

Boolean Expression:

Y = A ⊕ B

Truth Table:

A B | Y

0 0 | 0

0 1 | 1

1 0 | 1

1 1 | 0

Rule:

Outputs 1 when inputs are different.

---

### XNOR Gate

Boolean Expression:

Y = (A ⊕ B)'

Rule:

Outputs 1 when inputs are the same.

---

## Universal Gates

NAND and NOR are called Universal Gates because any logic gate can be implemented using only NAND gates or only NOR gates.

---

## CMOS Technology

CMOS stands for:

Complementary Metal Oxide Semiconductor

CMOS circuits use:

* PMOS
* NMOS

Advantages:

* Low Power Consumption
* High Noise Immunity
* Widely Used in Digital IC Design

---

## CMOS Inverter

Input = 0

PMOS = ON

NMOS = OFF

Output = 1

Input = 1

PMOS = OFF

NMOS = ON

Output = 0

---

## CMOS NAND Gate

Pull-Up Network:

PMOS in Parallel

Pull-Down Network:

NMOS in Series

---

## CMOS NOR Gate

Pull-Up Network:

PMOS in Series

Pull-Down Network:

NMOS in Parallel

---

## Levels of Integration

### SSI

Small Scale Integration

Few logic gates.

### MSI

Medium Scale Integration

Hundreds of gates.

### LSI

Large Scale Integration

Thousands of gates.

### VLSI

Very Large Scale Integration

Millions or billions of transistors.

Examples:

* CPUs
* GPUs
* ASICs
* SoCs

---

## Boolean Algebra Laws

### Idempotent Law

A + A = A

A.A = A

---

### Complement Law

A + A' = 1

A.A' = 0

---

### Commutative Law

A + B = B + A

A.B = B.A

---

### Associative Law

(A+B)+C = A+(B+C)

(A.B).C = A.(B.C)

---

### Distributive Law

A(B+C) = AB + AC

---

## De Morgan's Theorem

Formula 1:

(A+B)' = A'B'

Formula 2:

(A.B)' = A' + B'

These formulas are widely used in logic simplification.

---

## Boolean Expression Simplification

Examples:

A + A = A

A.A = A

A + A' = 1

A.A' = 0

A + AB = A

Boolean algebra helps reduce hardware complexity, area and power consumption.

---

## Important Interview Questions

1. What is a Universal Gate?
2. Why are NAND and NOR called Universal Gates?
3. What is CMOS?
4. Explain CMOS inverter operation.
5. What is XOR?
6. What is XNOR?
7. State De Morgan's Theorem.
8. What is VLSI?
9. What is the difference between NAND and NOR?
10. Why is Boolean simplification important?

---

## Key Takeaways

Today I learned the seven basic logic gates, their truth tables and Boolean expressions. I also learned CMOS implementation basics, levels of integration, Boolean algebra laws, De Morgan's theorem and logic simplification techniques used in digital circuit design.
