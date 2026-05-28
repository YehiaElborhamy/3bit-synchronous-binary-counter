# 3-Bit Synchronous Binary Counter
3-bit synchronous binary counter designed using JK flip-flops, K-maps, simulation, and hardware implementation.
A digital logic design project that implements a 3-bit synchronous binary counter using JK flip-flops, truth tables, excitation tables, Karnaugh maps, simulation, and hardware implementation.

---

## Project Overview

This project demonstrates the design and implementation of a 3-bit synchronous binary counter that counts from `000` to `111` and then resets back to `000`.

The counter uses three JK flip-flops connected to the same clock signal, allowing all flip-flops to change state simultaneously. This synchronous design helps reduce ripple delay and improves counting reliability.

---

## Features

- 3-bit binary counting sequence
- Counts from `000` to `111`
- Synchronous operation using a common clock signal
- JK flip-flop based design
- Truth table and excitation table analysis
- K-map simplification
- Simulation and hardware implementation

---

## Tools & Technologies

- Digital Logic Design
- JK Flip-Flops
- Karnaugh Maps (K-Maps)
- Logic Gates
- Breadboard Hardware Implementation
- Simulation Tools

---

## How It Works

The counter consists of three JK flip-flops:

- The least significant bit toggles on every clock pulse.
- The second bit toggles when the first bit is `1`.
- The most significant bit toggles when both lower bits are `1`.

This produces the binary counting sequence:

```text
000 → 001 → 010 → 011 → 100 → 101 → 110 → 111 → 000
