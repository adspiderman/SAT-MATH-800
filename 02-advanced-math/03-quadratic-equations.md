# Lesson 2.3 — Quadratic Equations

## Concepts

A quadratic equation ax² + bx + c = 0 has up to two real solutions. Four solving tools, in speed order:

### 1. Factoring (fastest when it works)
x² − 5x − 14 = 0 → (x − 7)(x + 2) = 0 → x = 7 or x = −2.
**Zero-product principle:** a product is 0 iff a factor is 0 — this requires one side to BE zero first.

### 2. Square-root method (when there's no x term, or it's a perfect square)
(x − 4)² = 25 → x − 4 = ±5 → x = 9 or x = −1. **Don't forget the ±.**

### 3. Quadratic formula (always works)

```
x = (−b ± √(b² − 4ac)) / (2a)
```

x² − 4x − 3 = 0 → x = (4 ± √(16 + 12))/2 = (4 ± √28)/2 = **2 ± √7**.

### 4. Desmos (always works, zero algebra)
Graph `y = x² - 4x - 3`, click the x-intercepts. For exact radical answers, the formula is safer; for checking or for decimal/SPR answers, Desmos wins.

### The discriminant — counts solutions (heavily tested)

D = b² − 4ac

| D | Real solutions | Graph |
|---|----------------|-------|
| D > 0 | 2 | crosses x-axis twice |
| D = 0 | 1 (double root) | touches x-axis (tangent) |
| D < 0 | 0 | never reaches x-axis |

**Worked example.** For what k does kx² + 12x + 9 = 0 have exactly one solution?
- D = 144 − 36k = 0 → **k = 4**.

### Vieta's shortcuts (sum & product of roots)

For ax² + bx + c = 0: **sum of roots = −b/a**, **product of roots = c/a**.
"What is the sum of the solutions of 2x² − 8x + 5 = 0?" → 8/2 = **4**. Ten seconds, no solving. The SAT asks for sums/products of solutions specifically to reward this.

### Quadratics in context

h(t) = −16t² + 64t (projectile height): hits the ground when h = 0 → −16t(t − 4) = 0 → **t = 4** (t = 0 is launch). Max height at the vertex, t = −b/2a = 2 → h(2) = 64.

## Traps

1. **Move everything to one side before factoring.** x² = 6x − 9 must become x² − 6x + 9 = 0 first. Factoring "x(x − 6) = −9 so x = −9 or..." is invalid.
2. **± after square roots.** (x − 4)² = 25 has TWO solutions; the SAT will offer the one-solution answer.
3. "Sum of solutions" → use −b/a; don't burn a minute solving.
4. A "quadratic" with D < 0 has no real solutions — that IS a legitimate answer choice.
5. In word problems, reject solutions that don't fit context (negative time, negative length) — but only after checking the question isn't asking for the other root.

## Practice Set

1. Solve: x² − 5x − 14 = 0
2. Solve: 2x² + 7x − 4 = 0
3. Solve: x² = 6x − 9
4. Solve (exact form): x² − 4x − 3 = 0
5. How many real solutions does 3x² − 5x + 4 = 0 have?
6. For what value of k does kx² + 12x + 9 = 0 have exactly one real solution?
7. What is the sum of the solutions of 2x² − 8x + 5 = 0? The product?
8. x² + bx + 16 = 0 has exactly one real solution and b > 0. What is b?
9. Solve: (x − 4)² = 25
10. A ball's height is h(t) = −16t² + 64t. When does it return to the ground, and what is its maximum height?

### Answers

1. **x = 7, −2**.
2. **x = 1/2, −4** — (2x − 1)(x + 4) = 0.
3. **x = 3** — (x − 3)² = 0, a double root.
4. **x = 2 ± √7**.
5. **None** — D = 25 − 48 = −23 < 0.
6. **k = 4** — D = 144 − 36k = 0.
7. **Sum 4, product 5/2** — −b/a = 8/2, c/a = 5/2.
8. **b = 8** — D = b² − 64 = 0 → b = ±8; positive one.
9. **x = 9 and x = −1**.
10. **t = 4 s; max 64 ft** — roots 0 and 4; vertex at t = 2, h(2) = 64.
