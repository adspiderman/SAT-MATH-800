# Lesson 4.4 — Circles

## Concepts

### The equation of a circle

```
(x − h)² + (y − k)² = r²        center (h, k), radius r
```

- x² + y² = 25 → center (0, 0), radius **5** (not 25!).
- (x − 3)² + (y + 2)² = 16 → center (3, **−2**), radius 4. Signs flip, like vertex form.

### General form → complete the square (a hard-question staple)

x² + y² − 6x + 4y − 12 = 0
- Group: (x² − 6x) + (y² + 4y) = 12
- Complete each square: (x − 3)² − 9 + (y + 2)² − 4 = 12
- **(x − 3)² + (y + 2)² = 25** → center (3, −2), radius 5.

Point on/inside/outside the circle: compare its distance-squared from the center to r².

### Circumference, area, arcs, sectors

C = 2πr, A = πr². A central angle of θ degrees cuts off a **fraction θ/360** of the circle:

```
arc length = (θ/360) · 2πr        sector area = (θ/360) · πr²
```

**Worked example.** Radius 6, central angle 60°: arc = (60/360)(12π) = **2π**; sector = (1/6)(36π) = **6π**.

In radians the fraction is θ/2π, so arc length = rθ — radian questions are usually *easier*.

### Angles in circles

- Central angle = its arc measure.
- **Inscribed angle = half** the central angle on the same arc.
- An angle inscribed in a semicircle is 90°.
- A tangent line is perpendicular to the radius at the point of tangency.

## Desmos angle

Graph the circle equation directly (any form — Desmos accepts x² + y² − 6x + 4y − 12 = 0 as-is!) and read the center/radius from the graph; intersect with lines for system questions. This makes completing the square checkable in seconds. Slider on r for tangency questions.

## Traps

1. **r² vs r.** The equation shows r-squared. Radius of x² + y² = 12 is 2√3, not 12 or 6.
2. **Sign flips in the center:** (y + 2)² means k = −2.
3. Arc length vs sector area vs arc *degree* measure — three different quantities; read which is asked.
4. Diameter vs radius in C and A formulas — given a diameter of 10, r = 5.
5. When completing the square, whatever you add inside must be added to the other side too.

## Practice Set

1. Find the center and radius: (x − 3)² + (y + 2)² = 16
2. Find the radius of x² + y² = 12.
3. Rewrite x² + y² − 6x + 4y − 12 = 0 in standard form; give center and radius.
4. A circle has center (2, −1) and passes through (5, 3). What is its radius?
5. Radius 6, central angle 60°. Find the arc length and sector area.
6. A circle has circumference 16π. What is its area?
7. Is the point (4, 4) inside, on, or outside the circle (x − 1)² + (y − 2)² = 25?
8. An inscribed angle subtends the same arc as an 88° central angle. What is its measure?
9. Write the equation of the circle with center (−4, 0) tangent to the y-axis.
10. A central angle of 3π/4 radians in a circle of radius 8: what is the arc length?

### Answers

1. **Center (3, −2), r = 4**.
2. **2√3**.
3. **(x − 3)² + (y + 2)² = 25; center (3, −2), r = 5**.
4. **5** — √(3² + 4²).
5. **Arc 2π, sector 6π**.
6. **64π** — r = 8.
7. **Inside** — distance² = 9 + 4 = 13 < 25.
8. **44°** — half the central angle.
9. **(x + 4)² + y² = 16** — tangent to the y-axis means r = |−4| = 4.
10. **6π** — s = rθ = 8 · 3π/4.
