# Lesson 2.9 — Nonlinear Systems

## Concepts

A nonlinear system mixes a line with a parabola/circle, or two curves. Geometrically: where do the graphs meet?

### The method: substitute, then solve the quadratic

**Worked example 1.** y = x² and y = 2x + 3.
- x² = 2x + 3 → x² − 2x − 3 = 0 → (x − 3)(x + 1) = 0 → x = 3, −1.
- Points: **(3, 9) and (−1, 1)**. (Get y from either equation.)

### Counting intersections — the discriminant again

Set the expressions equal, move to one side, compute D = b² − 4ac:

| D | Intersections |
|---|--------------|
| > 0 | 2 |
| = 0 | 1 (tangent!) |
| < 0 | 0 |

**Worked example 2.** How many times does y = 2x meet y = x² + 5?
- x² − 2x + 5 = 0 → D = 4 − 20 < 0 → **never**.

**Worked example 3 (tangency).** For what m > 0 is y = mx tangent to y = x² + 4?
- x² − mx + 4 = 0 → D = m² − 16 = 0 → **m = 4**.

**Horizontal line trick:** y = k meets a parabola exactly once ⇔ k is the vertex's y-value. "For what k does y = x² − 2x − 3 = k have exactly one solution?" → vertex y = −4 → **k = −4**.

### Line and circle

x² + y² = 25 with y = x + 1:
- x² + (x + 1)² = 25 → 2x² + 2x − 24 = 0 → x² + x − 12 = 0 → x = 3, −4.
- Points: **(3, 4) and (−4, −3)**.

## Desmos angle

This topic is where Desmos shines brightest:
- Type both equations, click intersections — done. "Solve the system" = 20 seconds.
- "How many solutions" = count visible intersections (zoom out to be sure).
- Tangency with a parameter: slider on m, drag until the line just touches. Then confirm the exact value with the discriminant if needed.

**Default to Desmos here.** Do the algebra only when the answer must be exact and the numbers are irrational, or to double-check.

## Traps

1. **A point of intersection must satisfy BOTH equations.** Fastest MC check: plug the choices in.
2. "Sum of the x-coordinates of the solutions" — use Vieta on the combined quadratic: for x² − 2x − 3 = 0, sum = 2. No solving needed.
3. Tangent means exactly one intersection — D = 0, a favorite hard-question setup.
4. After finding x, the question may want y, or x + y, or the product — reread.
5. When substituting y = x + 1 into a circle, expand (x + 1)² carefully — middle term!

## Practice Set

1. Solve the system: y = x², y = 2x + 3.
2. In how many points do y = x² − 4x + 7 and y = 3 intersect?
3. How many solutions: y = x² + 5 and y = 2x?
4. For what value of k does y = x² − 2x − 3 intersect y = k exactly once?
5. For what positive m is y = mx tangent to y = x² + 4?
6. Solve: x² + y² = 25 and y = x + 1.
7. The graphs of y = x² and y = 4x − x² intersect at two points. What is the sum of the y-coordinates of these points?
8. The system y = (x − 2)² + k, y = 5 has exactly one solution. What is k?
9. Line y = 2x + b passes through the intersection of y = x² and y = 3x... at the intersection point with larger x-coordinate. What is b? (Intersections of y = x² and y = 3x first.)
10. What is the sum of the x-coordinates of the solutions of y = x² − 3x and y = x?

### Answers

1. **(3, 9), (−1, 1)**.
2. **One** — x² − 4x + 4 = 0 → (x − 2)² = 0, tangent at (2, 3).
3. **None** — D = −16 < 0.
4. **k = −4** — the vertex y-value: vertex (1, −4).
5. **m = 4** — D = m² − 16 = 0.
6. **(3, 4) and (−4, −3)**.
7. **4** — x² = 4x − x² → 2x²−4x = 0 → x = 0, 2 → y = 0, 4.
8. **k = 5** — one solution means the line hits the vertex: (x−2)² = 5 − k has one solution when 5 − k = 0.
9. **b = 3** — y = x² meets y = 3x at x = 0 and x = 3; larger point is (3, 9); 9 = 2(3) + b → b = 3.
10. **4** — x² − 3x = x → x² − 4x = 0 → x = 0, 4.
