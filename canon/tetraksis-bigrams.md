# TETRAKSIS Bigrams  
Canonical 2‑Bit Semantic Alphabet of SUBIT

This document defines the four canonical bigrams of TETRAKSIS.  
They form the minimal semantic alphabet from which the full 64‑state SUBIT grid is generated.  
Each bigram encodes three simultaneous axes: **person**, **direction**, and **season**.

---

## 1. Overview

TETRAKSIS produces exactly four bigrams:

- 10  
- 11  
- 01  
- 00  

These represent the complete 2‑bit state space.  
In SUBIT, each bigram is not only a binary value but a **semantic node** with three aligned interpretations.

---

## 2. Canonical Bigram Table

| Bigram | Person | Direction | Season |
|--------|--------|-----------|--------|
| **10** | ME     | EAST      | SPRING |
| **11** | WE     | SOUTH     | SUMMER |
| **01** | YOU    | WEST      | AUTUMN |
| **00** | THEY   | NORTH     | WINTER |

Each bigram is a compact semantic packet.  
Together, they form the generative base for SUBIT‑64.

---

## 3. Semantic Axes

### Person Axis
- ME  
- WE  
- YOU  
- THEY  

Represents the four fundamental modes of subjectivity.

### Direction Axis
- EAST  
- SOUTH  
- WEST  
- NORTH  

Represents spatial orientation and energetic flow.

### Seasonal Axis
- SPRING  
- SUMMER  
- AUTUMN  
- WINTER  

Represents cyclic time and developmental phase.

Each axis aligns perfectly with the four bigrams, forming a unified semantic coordinate system.

---

## 4. Formal Definition

```
BIGRAMS = {
  10: (ME,   EAST,  SPRING),
  11: (WE,   SOUTH, SUMMER),
  01: (YOU,  WEST,  AUTUMN),
  00: (THEY, NORTH, WINTER)
}
```

---

## 5. Role in SUBIT‑64

The four bigrams serve as the **alphabet** for constructing the 64‑state SUBIT grid.

A SUBIT‑64 state is defined as:

```
SUBIT = A B C
A = Person bigram
B = Direction bigram
C = Season bigram
```

Since each bigram has four possible values:

```
4 × 4 × 4 = 64 states
```

Thus, the TETRAKSIS bigrams are the fractal seed of the entire SUBIT ontology.

---

## 6. Status

This document defines the canonical bigram specification for SUBIT‑TETRAKSIS v1.0.
