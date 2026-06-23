# Day 11 - Demultiplexers and Decoders

## Topics Covered

* Demultiplexer (DEMUX)
* 1:2 DEMUX
* 1:4 DEMUX
* Higher Order DEMUX Realization
* Decoder
* Active High Signals
* Active Low Signals
* Enable Inputs
* 7-Segment Decoder
* Higher Order Decoder Realization

---

## Demultiplexer (DEMUX)

A Demultiplexer is a combinational circuit that routes a single input to one of many outputs based on the select lines.

DEMUX is also called:

Data Distributor

---

## Structure of DEMUX

For n select lines:

Number of Outputs = 2ⁿ

Number of Inputs = 1

Examples:

### 1:2 DEMUX

* 1 Input
* 1 Select Line
* 2 Outputs

### 1:4 DEMUX

* 1 Input
* 2 Select Lines
* 4 Outputs

---

## Function of DEMUX

A DEMUX transfers the input signal to one selected output line.

All other outputs remain inactive.

---

## Higher Order DEMUX

Higher-order DEMUX circuits can be built using lower-order DEMUX circuits.

Example:

### 1:4 DEMUX using 1:2 DEMUX

Requires:

* Three 1:2 DEMUX circuits

This follows a tree structure.

---

## Decoder

A Decoder is a combinational circuit that converts binary information into a unique output line.

A Decoder activates only one output for a given input combination.

---

## Structure of Decoder

For n inputs:

Number of Outputs = 2ⁿ

Examples:

### 2:4 Decoder

* 2 Inputs
* 4 Outputs

### 3:8 Decoder

* 3 Inputs
* 8 Outputs

---

## Active High Signals

In Active High logic:

Output is considered active when:

1 = Active

0 = Inactive

---

## Active Low Signals

In Active Low logic:

Output is considered active when:

0 = Active

1 = Inactive

Active low outputs are usually indicated using a bubble in logic diagrams.

---

## Enable Input

Many decoders contain an Enable (EN) input.

### Enable = 1

Decoder operates normally.

### Enable = 0

Decoder is disabled.

Some decoder families use active-low enable signals.

---

## 7-Segment Decoder

A 7-segment decoder converts binary or BCD input into signals that drive a 7-segment display.

Applications:

* Digital Clocks
* Calculators
* Counters
* Measurement Instruments

The seven segments are:

a, b, c, d, e, f, g

Different combinations of segments display digits 0–9.

---

## Higher Order Decoder Realization

Higher-order decoders can be implemented using lower-order decoders.

Example:

### 3:8 Decoder using 2:4 Decoders

Uses enable inputs to activate the required decoder block.

This approach is known as decoder expansion.

---

## Applications

### DEMUX

* Data Routing
* Communication Systems
* Signal Distribution

### Decoder

* Memory Address Decoding
* Display Systems
* Processor Design
* Control Logic

---

## Important Interview Questions

1. What is a DEMUX?
2. Why is a DEMUX called a Data Distributor?
3. What is the difference between MUX and DEMUX?
4. What is a Decoder?
5. What is the purpose of Enable signals?
6. What is Active High logic?
7. What is Active Low logic?
8. What is a 7-Segment Decoder?
9. How can higher-order decoders be built?
10. What are the applications of decoders?

---

## Key Takeaways

Today I learned Demultiplexers, Decoder circuits, Active High and Active Low logic, Enable signals, 7-Segment Decoders, and higher-order circuit realization using lower-order DEMUX and Decoder blocks.
