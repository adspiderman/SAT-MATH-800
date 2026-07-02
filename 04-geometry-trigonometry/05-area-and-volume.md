# Lesson 4.5 — Area & Volume

## Concepts

### Area formulas

| Shape | Area |
|-------|------|
| Rectangle | ℓw |
| Triangle | ½bh (h ⊥ b) |
| Parallelogram | bh |
| Trapezoid | ½(b₁ + b₂)h |
| Circle | πr² |

Composite figures: split into pieces or subtract a hole (e.g., square minus circle for a "shaded region").

### Volume formulas (all on the reference sheet)

| Solid | Volume |
|-------|--------|
| Box | ℓwh |
| Cylinder | πr²h |
| Sphere | (4/3)πr³ |
| Cone | (1/3)πr²h |
| Pyramid | (1/3)ℓwh |

Pattern: cones and pyramids are **1/3 of** their "full-height" counterparts.

**Worked example 1.** Cylinder r = 3, h = 5 → V = π·9·5 = **45π**.

**Worked example 2 (solve backwards).** A sphere has volume 36π. Radius?
- (4/3)πr³ = 36π → r³ = 27 → **r = 3**.

### Scaling (a favorite hard question)

If every length scales by k: perimeter ×k, **area ×k², volume ×k³**.
- Double a cube's edges → volume ×8.
- A model at 1:20 scale has (1/20)³ = 1/8000 of the real volume.

### Density / packing problems

mass = density × volume; "how many boxes fit" = big volume ÷ small volume (when the problem says they pack perfectly). Units matter — [Lesson 3.3](../03-problem-solving-data-analysis/03-units-and-conversion.md) squared/cubed rules apply.

## Desmos angle

Pure arithmetic — let Desmos crunch: `(4/3)*pi*3^3`. Keep π symbolic until the end when the answer is "in terms of π"; use decimals when the SPR wants a decimal. For backwards problems (given V, find r), type the equation `(4/3)*pi*r^3 = 36*pi` with an x for r... simpler: solve the cube root numerically: `(27)^(1/3)`.

## Traps

1. **Radius vs diameter** — the #1 volume error. Given "a cylinder 10 cm across," r = 5.
2. Height must be perpendicular — in slanted figures, the slant is NOT the height (use Pythagorean theorem to find the true height of a cone from slant height).
3. "In terms of π" answers: don't multiply π out; SPR decimal answers: don't leave π in.
4. Scaling: doubling lengths quadruples area — students who answer "×2" fund the College Board.
5. Composite solids: don't double-count the shared face/region.

## Practice Set

1. Volume of a cylinder with radius 3 and height 5 (in terms of π)?
2. A sphere has volume 36π. Find its radius.
3. A cone has radius 6 and height 4. Find its volume in terms of π.
4. A rectangular box is 4 × 5 × 10. A cube has the same volume. What is the cube's edge length (to the nearest tenth)?
5. Trapezoid with parallel sides 8 and 14 and height 6: area?
6. A square of side 10 has a circle of radius 3 cut from it. What is the remaining area (nearest tenth)?
7. Every edge of a cube is tripled. The volume becomes how many times larger?
8. A cone has slant height 13 and radius 5. Find its volume in terms of π.
9. A cylindrical tank (r = 2 ft, h = 6 ft) is filled with a liquid of density 50 lb/ft³. What is the liquid's weight to the nearest pound?
10. A 6 in × 6 in × 12 in box is packed with 2-inch cubes. How many cubes fit?

### Answers

1. **45π**.
2. **3** — r³ = 27.
3. **48π** — (1/3)(36)(4)π.
4. **5.8** — V = 200; 200^(1/3) ≈ 5.85.
5. **66** — ½(22)(6).
6. **71.7** — 100 − 9π ≈ 100 − 28.27.
7. **27** — 3³.
8. **100π** — height = 12 (5-12-13); (1/3)(25)(12)π.
9. **3770 lb** — V = 24π ≈ 75.40 ft³ × 50 ≈ 3769.9.
10. **54** — (6/2)(6/2)(12/2) = 3·3·6.
