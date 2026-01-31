# SUBIT‑64 Map  
Canonical Structure Derived from TETRAKSIS

SUBIT‑64 is the 64‑state semantic grid generated from the four TETRAKSIS bigrams.  
Each SUBIT state is a 6‑bit configuration composed of **three bigrams**, representing:

- **Person** (subjective mode)  
- **Direction** (spatial vector)  
- **Season** (temporal phase)

This document defines the canonical mapping rules and structural logic of SUBIT‑64.

---

## 1. Bigram Alphabet (from TETRAKSIS)

SUBIT‑64 uses the four canonical bigrams:

| Bigram | Person | Direction | Season |
|--------|--------|-----------|--------|
| 10 | ME   | EAST  | SPRING |
| 11 | WE   | SOUTH | SUMMER |
| 01 | YOU  | WEST  | AUTUMN |
| 00 | THEY | NORTH | WINTER |

These four bigrams form the complete 2‑bit semantic alphabet.

---

## 2. SUBIT‑64 Construction

A SUBIT‑64 state is defined as:

```
SUBIT = A B C
```

Where:

- **A** = Person bigram  
- **B** = Direction bigram  
- **C** = Season bigram  

Each component has four possible values:

```
A ∈ {10, 11, 01, 00}
B ∈ {10, 11, 01, 00}
C ∈ {10, 11, 01, 00}
```

Thus:

```
4 × 4 × 4 = 64 states
```

---

## 3. Coordinate Interpretation

Each SUBIT state encodes a triple:

```
(Person, Direction, Season)
```

Example:

```
10 01 00
= ME / WEST / WINTER
```

This triple defines a **subjective–spatial–temporal configuration**.

---

## 4. Canonical SUBIT‑64 Grid (Structure Only)

Below is the structural layout of the 64 states.  
The full semantic table is provided in `subit64-table.md`.

### A = 10 (ME)

```
10 10 10   ME / EAST  / SPRING
10 10 11   ME / EAST  / SUMMER
10 10 01   ME / EAST  / AUTUMN
10 10 00   ME / EAST  / WINTER

10 11 10   ME / SOUTH / SPRING
10 11 11   ME / SOUTH / SUMMER
10 11 01   ME / SOUTH / AUTUMN
10 11 00   ME / SOUTH / WINTER

10 01 10   ME / WEST  / SPRING
10 01 11   ME / WEST  / SUMMER
10 01 01   ME / WEST  / AUTUMN
10 01 00   ME / WEST  / WINTER

10 00 10   ME / NORTH / SPRING
10 00 11   ME / NORTH / SUMMER
10 00 01   ME / NORTH / AUTUMN
10 00 00   ME / NORTH / WINTER
```

### A = 11 (WE)

```
11 10 10   WE / EAST  / SPRING
11 10 11   WE / EAST  / SUMMER
11 10 01   WE / EAST  / AUTUMN
11 10 00   WE / EAST  / WINTER

11 11 10   WE / SOUTH / SPRING
11 11 11   WE / SOUTH / SUMMER
11 11 01   WE / SOUTH / AUTUMN
11 11 00   WE / SOUTH / WINTER

11 01 10   WE / WEST  / SPRING
11 01 11   WE / WEST  / SUMMER
11 01 01   WE / WEST  / AUTUMN
11 01 00   WE / WEST  / WINTER

11 00 10   WE / NORTH / SPRING
11 00 11   WE / NORTH / SUMMER
11 00 01   WE / NORTH / AUTUMN
11 00 00   WE / NORTH / WINTER
```

### A = 01 (YOU)

```
01 10 10   YOU / EAST  / SPRING
01 10 11   YOU / EAST  / SUMMER
01 10 01   YOU / EAST  / AUTUMN
01 10 00   YOU / EAST  / WINTER

01 11 10   YOU / SOUTH / SPRING
01 11 11   YOU / SOUTH / SUMMER
01 11 01   YOU / SOUTH / AUTUMN
01 11 00   YOU / SOUTH / WINTER

01 01 10   YOU / WEST  / SPRING
01 01 11   YOU / WEST  / SUMMER
01 01 01   YOU / WEST  / AUTUMN
01 01 00   YOU / WEST  / WINTER

01 00 10   YOU / NORTH / SPRING
01 00 11   YOU / NORTH / SUMMER
01 00 01   YOU / NORTH / AUTUMN
01 00 00   YOU / NORTH / WINTER
```

### A = 00 (THEY)

```
00 10 10   THEY / EAST  / SPRING
00 10 11   THEY / EAST  / SUMMER
00 10 01   THEY / EAST  / AUTUMN
00 10 00   THEY / EAST  / WINTER

00 11 10   THEY / SOUTH / SPRING
00 11 11   THEY / SOUTH / SUMMER
00 11 01   THEY / SOUTH / AUTUMN
00 11 00   THEY / SOUTH / WINTER

00 01 10   THEY / WEST  / SPRING
00 01 11   THEY / WEST  / SUMMER
00 01 01   THEY / WEST  / AUTUMN
00 01 00   THEY / WEST  / WINTER

00 00 10   THEY / NORTH / SPRING
00 00 11   THEY / NORTH / SUMMER
00 00 01   THEY / NORTH / AUTUMN
00 00 00   THEY / NORTH / WINTER
```

---

## 5. Structural Summary

```
SUBIT-64 = 4 persons × 4 directions × 4 seasons
         = 64 subjective–spatial–temporal states
```

Each state is a unique coordinate in the SUBIT semantic space.

---

## 6. Status

This document defines the canonical SUBIT‑64 mapping rules for SUBIT‑TETRAKSIS v1.0.
