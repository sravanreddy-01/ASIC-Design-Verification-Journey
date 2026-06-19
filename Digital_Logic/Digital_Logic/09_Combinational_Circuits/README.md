# Day 9 - Combinational Circuits and Adders

## Overview

Combinational circuits are digital circuits whose outputs depend only on the current inputs. They do not store any previous information and therefore have no memory elements.

### Characteristics

* Output depends only on present inputs.
* No memory elements.
* No feedback path.
* Faster than sequential circuits.

### Examples

* Half Adder
* Full Adder
* Multiplexer (MUX)
* Decoder
* Encoder

---

# Half Adder

A Half Adder is a combinational circuit used to add two single-bit binary numbers.

## Inputs

* A
* B

## Outputs

* Sum (S)
* Carry (C)

## Truth Table

| A | B | Sum | Carry |
| - | - | --- | ----- |
| 0 | 0 | 0   | 0     |
| 0 | 1 | 1   | 0     |
| 1 | 0 | 1   | 0     |
| 1 | 1 | 0   | 1     |

## Boolean Expressions

Sum:

S = A ⊕ B

Carry:

C = A · B

---

# Full Adder

A Full Adder is a combinational circuit used to add three single-bit binary numbers.

## Inputs

* A
* B
* Cin (Carry Input)

## Outputs

* Sum
* Cout (Carry Output)

## Boolean Expressions

Sum:

Sum = A ⊕ B ⊕ Cin

Carry Output:

Cout = AB + ACin + BCin

Alternative Form:

Cout = AB + Cin(A ⊕ B)

---

# Full Adder Using Half Adders

A Full Adder can be implemented using:

* Two Half Adders
* One OR Gate

## Implementation

First Half Adder:

S1 = A ⊕ B

C1 = AB

Second Half Adder:

Sum = S1 ⊕ Cin

C2 = S1 · Cin

Final Carry:

Cout = C1 + C2

---

# Ripple Carry Adder

A Ripple Carry Adder is formed by connecting multiple Full Adders in series to perform multi-bit binary addition.

## Working Principle

* Carry output from one Full Adder becomes the carry input of the next Full Adder.
* The carry propagates through each stage sequentially.

## Advantages

* Simple design
* Easy to implement

## Disadvantages

* High propagation delay
* Delay increases with the number of bits

---

# Key Interview Points

1. A combinational circuit has no memory.
2. Half Adder has two inputs and two outputs.
3. Full Adder has three inputs and two outputs.
4. A Full Adder can be implemented using two Half Adders and one OR gate.
5. Ripple Carry Adders are used for multi-bit addition.
6. The main drawback of Ripple Carry Adders is propagation delay.

---

# Summary

* Combinational circuits depend only on present inputs.
* Half Adders add two binary bits.
* Full Adders add three binary bits.
* Multiple Full Adders form a Ripple Carry Adder.
* Ripple Carry Adders are simple but suffer from carry propagation delay.
