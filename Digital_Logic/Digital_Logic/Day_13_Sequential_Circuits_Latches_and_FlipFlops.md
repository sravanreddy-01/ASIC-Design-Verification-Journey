# Day 13 - Sequential Circuits, Latches and Flip-Flops

## Topics Covered

* Sequential Circuits
* Difference Between Combinational and Sequential Circuits
* Storage Elements
* SR Latch (NOR Gate)
* SR Latch (NAND Gate)
* JK Latch
* D Latch
* Clock Fundamentals
* Clock Parameters
* SR Flip-Flop
* JK Flip-Flop
* D Flip-Flop
* T Flip-Flop
* Waveform Analysis

---

# Sequential Circuits

A Sequential Circuit is a digital circuit whose output depends on:

* Present Inputs
* Previous State (Memory)

Unlike combinational circuits, sequential circuits contain memory elements and feedback paths.

---

# Difference Between Combinational and Sequential Circuits

| Combinational Circuit          | Sequential Circuit                           |
| ------------------------------ | -------------------------------------------- |
| Depends only on present inputs | Depends on present inputs and previous state |
| No memory                      | Contains memory                              |
| No feedback                    | Feedback present                             |
| Faster                         | Slightly slower due to storage elements      |
| Examples: Adders, MUX          | Examples: Latches, Flip-Flops                |

---

# Storage Elements

Storage elements store one bit of information.

Examples:

* Latch
* Flip-Flop
* Register

---

# SR Latch

Inputs:

* S (Set)
* R (Reset)

Outputs:

* Q
* Q'

Operations:

* S=0, R=0 → Hold
* S=0, R=1 → Reset
* S=1, R=0 → Set
* S=1, R=1 → Invalid

Implemented using both NOR and NAND gates.

Both implementations perform the same logical operation with different gate realizations.

---

# JK Latch

The JK Latch eliminates the invalid condition of the SR Latch.

Operations:

* J=0, K=0 → Hold
* J=0, K=1 → Reset
* J=1, K=0 → Set
* J=1, K=1 → Toggle

Toggle means the next state becomes the complement of the present state.

---

# D Latch

The D Latch has:

* One Input (D)
* Enable Signal

Characteristic Equation:

Q(n+1) = D

The output follows the input only while Enable is active.

Due to its simplicity, D Latches are widely used in digital systems.

---

# Clock Fundamentals

Clock synchronizes all sequential circuits.

Important Parameters:

* Time Period (T)
* Frequency (f)
* Clock Cycle
* Ton
* Toff
* Duty Cycle

Relations:

* f = 1 / T
* T = 1 / f
* Duty Cycle = (Ton / T) × 100%

---

# Latch vs Flip-Flop

Latch:

* Level Sensitive
* Controlled using Enable
* Output changes while Enable is active

Flip-Flop:

* Edge Triggered
* Controlled using Clock
* Output changes only at the active clock edge

Flip-Flops are preferred in synchronous digital systems because they provide controlled and reliable data storage.

---

# Flip-Flops

## SR Flip-Flop

Clock-controlled version of SR Latch.

---

## JK Flip-Flop

Removes the invalid state of SR Flip-Flop.

Supports Toggle operation.

---

## D Flip-Flop

Characteristic Equation:

Q(n+1) = D

Captures input only at the active clock edge.

---

## T Flip-Flop

Operations:

* T=0 → Hold
* T=1 → Toggle

---

# Waveform Analysis

Waveforms illustrate the relationship between:

* Clock
* Inputs
* Outputs

Outputs change only at the active clock edge.

If an input changes simultaneously with the active clock edge, the previous stable value is retained until the next valid sampling edge.

---

# Key Takeaways

* Sequential circuits require memory.
* Latches are level-sensitive.
* Flip-Flops are edge-triggered.
* JK Latch removes the invalid condition of SR Latch.
* D Flip-Flop is one of the most commonly used storage elements in modern digital systems.
* Clock synchronization is fundamental in sequential circuit design.
