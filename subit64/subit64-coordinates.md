# SUBIT‑64 Coordinates  
Canonical Subjective–Spatial–Temporal Coordinate System

SUBIT‑64 defines a complete 64‑state coordinate space derived from the four TETRAKSIS bigrams.  
Each SUBIT state is a **6‑bit coordinate** composed of three semantic axes:

- **Person axis** (subjectivity)  
- **Direction axis** (spatial vector)  
- **Season axis** (temporal phase)

This document defines the canonical coordinate interpretation for all SUBIT‑64 states.

---

## 1. Coordinate Structure

A SUBIT‑64 coordinate is written as:

```
A B C
```

Where:

- **A** = Person bigram  
- **B** = Direction bigram  
- **C** = Season bigram  

Each bigram ∈ {10, 11, 01, 00}.

Thus:

```
4 persons × 4 directions × 4 seasons = 64 coordinates
```

---

## 2. Axes and Their Meanings

### Person Axis (A)
Represents the mode of subjectivity.

| Bigram | Person |
|--------|--------|
| 10 | ME |
| 11 | WE |
| 01 | YOU |
| 00 | THEY |

### Direction Axis (B)
Represents spatial orientation and energetic flow.

| Bigram | Direction |
|--------|-----------|
| 10 | EAST |
| 11 | SOUTH |
| 01 | WEST |
| 00 | NORTH |

### Season Axis (C)
Represents temporal phase and developmental cycle.

| Bigram | Season |
|--------|--------|
| 10 | SPRING |
| 11 | SUMMER |
| 01 | AUTUMN |
| 00 | WINTER |

---

## 3. Coordinate Interpretation Formula

Each SUBIT‑64 coordinate expands into a semantic triple:

```
(A, B, C) = (Person, Direction, Season)
```

Example:

```
10 01 00
= ME / WEST / WINTER
```

This triple defines a **subjective–spatial–temporal state**.

---

## 4. Coordinate Cube (4 × 4 × 4)

SUBIT‑64 forms a perfect semantic cube:

```
Person:   ME, WE, YOU, THEY
Direction: EAST, SOUTH, WEST, NORTH
Season:    SPRING, SUMMER, AUTUMN, WINTER
```

Each axis has four discrete values.  
Each coordinate is a unique point in this 3‑dimensional semantic space.

---

## 5. Coordinate Ordering

Coordinates are ordered lexicographically:

1. Person (A)  
2. Direction (B)  
3. Season (C)  

This produces the canonical sequence used in:

- subit64-table.md  
- human-evolution-genome.md  
- all SUBIT‑based models  

---

## 6. Coordinate Examples

### Example 1
```
11 11 10
= WE / SOUTH / SPRING
```

### Example 2
```
01 00 01
= YOU / NORTH / AUTUMN
```

### Example 3
```
00 10 11
= THEY / EAST / SUMMER
```

Each coordinate is a complete semantic state.

---

## 7. Coordinate Space Summary

```
SUBIT-64 = {
  (ME,   EAST,  SPRING), (ME,   EAST,  SUMMER), ...
  (WE,   SOUTH, AUTUMN), (WE,   SOUTH, WINTER), ...
  (YOU,  WEST,  SPRING), (YOU,  WEST,  SUMMER), ...
  (THEY, NORTH, AUTUMN), (THEY, NORTH, WINTER)
}
```

All 64 states are enumerated in the full table.

---

## 8. Status

This document defines the canonical coordinate system for SUBIT‑TETRAKSIS v1.0.
