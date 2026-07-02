# Lesson 2.4 — Quadratic Functions & Parabolas

## Concepts

### The three forms — each "displays" different information

| Form | Equation | Shows as constants |
|------|----------|--------------------|
| Standard | y = ax² + bx + c | y-intercept (0, c) |
| Vertex | y = a(x − h)² + k | vertex (h, k) |
| Factored | y = a(x − p)(x − q) | x-intercepts p and q |

All three share **a**: a > 0 opens up (vertex = minimum); a < 0 opens down (vertex = maximum). |a| controls width.

The SAT loves: *"Which form displays the vertex/x-intercepts/y-intercept as constants or coefficients?"* Answer directly from this table — signs must match the form exactly (vertex of y = (x + 1)² − 4 is (−1, −4)).

### Finding the vertex

- **From vertex form:** read it: y = 2(x − 3)² + 5 → vertex (3, 5).
- **From standard form:** x = −b/(2a), then plug in. y = x² − 6x + 11 → x = 3 → y = 9 − 18 + 11 = 2 → vertex (3, 2).
- **From factored form / two x-intercepts:** the axis of symmetry is midway: y = a(x − 2)(x − 8) → axis x = 5. **Symmetry is a superpower:** any two points with equal y-values are centered on the axis.

### Completing the square (standard → vertex)

y = x² + 4x + 1 → y = (x² + 4x + 4) − 4 + 1 = **(x + 2)² − 3**.
Take half of b, square it, add & subtract. With a leading coefficient, factor it out of the x-terms first.

### Max/min word problems

h(t) = −16t² + 96t + 20: maximum height at t = −96/(2·−16) = 3 → h(3) = −144 + 288 + 20 = **164**.
"Maximum/minimum value of f" = the **y** of the vertex; "where it occurs" = the **x**. Read which is asked.

### Intercepts

- y-intercept: set x = 0 (it's just c).
- x-intercepts: set y = 0, solve the quadratic ([Lesson 2.3](03-quadratic-equations.md)). y = x² − 2x − 8 → (x − 4)(x + 2) → (4, 0) and (−2, 0); axis x = 1 (midpoint).

## Desmos angle

Graph it and click: the vertex, intercepts, and any intersection are clickable points. For a parameter question ("for what c does the vertex lie on the x-axis?"), add a slider for c and watch. Desmos converts *all* "parabola geometry" questions into observation. Use algebra only when the answer must be exact/symbolic.

## Traps

1. **Vertex form sign flip:** y = (x + 3)² − 4 has vertex (−3, −4). The h in (x − h) takes the opposite sign of what's printed.
2. **Maximum value vs location:** "the maximum of f is..." wants k (the y-value), not h.
3. −b/(2a) sign errors when b is negative: y = x² − 6x → x = +3.
4. A parabola's y-intercept is c only in **standard** form — expand first if given another form.
5. Two points with the same y-value ⇒ vertex x is their midpoint — often the fastest route on table problems.

## Practice Set

1. What is the vertex of y = 2(x − 3)² + 5?
2. What is the vertex of y = x² − 6x + 11?
3. What is the maximum value of f(x) = −(x + 1)² + 9?
4. Find the x-intercepts and axis of symmetry of y = x² − 2x − 8.
5. The parabola y = a(x − 2)(x − 8) has axis of symmetry x = ?
6. h(t) = −16t² + 96t + 20. What is the projectile's maximum height?
7. Rewrite y = x² + 4x + 1 in vertex form.
8. For what value of c does f(x) = x² + 6x + c have its vertex on the x-axis?
9. f(x) = x² − 4x + 7 and f(1) = f(k) for k ≠ 1. What is k?
10. The graph of y = 2x² − 4x − 6 has y-intercept b and larger x-intercept p. What is b + p?

### Answers

1. **(3, 5)**.
2. **(3, 2)** — x = 6/2 = 3.
3. **9** — opens down; vertex (−1, 9); max value is the y.
4. **(4, 0), (−2, 0); axis x = 1**.
5. **x = 5** — midpoint of 2 and 8.
6. **164 ft** — vertex at t = 3.
7. **y = (x + 2)² − 3**.
8. **c = 9** — vertex on x-axis ⇔ one root ⇔ D = 36 − 4c = 0.
9. **k = 3** — axis is x = 2; the mirror of 1 across 2 is 3.
10. **−3** — y-intercept −6; x-intercepts: 2x² − 4x − 6 = 2(x − 3)(x + 1) → larger is 3; −6 + 3 = −3.
