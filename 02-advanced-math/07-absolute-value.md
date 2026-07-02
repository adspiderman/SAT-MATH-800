# Lesson 2.7 — Absolute Value

## Concepts

|x| = distance from 0. |x − a| = distance from a. Distance thinking solves most SAT absolute-value questions faster than case-splitting.

### Equations — split into two cases

|2x + 1| = 9 → 2x + 1 = 9 **or** 2x + 1 = −9 → x = 4 or x = −5.

Special cases:
- |expr| = 0 → exactly one solution (expr = 0).
- |expr| = negative → **no solution** (absolute value is never negative). SAT tests this.

### Inequalities — "less-AND, greater-OR"

| Inequality | Rewrite | Read as |
|-----------|---------|---------|
| \|x − a\| < d | a − d < x < a + d | within d of a (a "band") |
| \|x − a\| > d | x < a − d or x > a + d | farther than d from a (two rays) |

- |x − 5| < 2 → 3 < x < 7.
- |x + 2| ≥ 4 → distance from −2 is at least 4 → x ≤ −6 or x ≥ 2.

### Tolerance word problems (the SAT's favorite application)

"A bag's weight w must be within 0.5 lb of 20 lb" → **|w − 20| ≤ 0.5**.
Template: |quantity − target| ≤ tolerance. Center = average of the endpoints, tolerance = half the range.

### Graphs

y = |x − h| + k is a **V** with vertex (h, k); y = −|x − h| + k is an upside-down V (vertex = maximum). Same shift logic as parabolas: y = |x + 1| − 4 has vertex (−1, −4). Minimum value of f(x) = |x − 7| + 3 is **3** (at x = 7) — the absolute value part is ≥ 0, smallest when 0.

## Desmos angle

Type `abs(...)` or the |x| button. Absolute-value equations/inequalities are ideal Desmos problems: graph both sides, click intersections; for "how many solutions" just count them. For tolerance problems, the band is visible.

## Traps

1. |x| = 7 has **two** solutions; |x| = −7 has **none**; |x| = 0 has one. Count carefully on "how many solutions" questions.
2. Case-split applies to the whole expression: |2x + 1| = 9 gives 2x + 1 = ±9, not 2x ± 1 = 9.
3. Inequality direction: < gives a single interval (AND); > gives two pieces (OR). Mixing these up flips the answer set entirely.
4. |a − b| = |b − a| — distance is symmetric; the SAT uses both orderings.

## Practice Set

1. Solve: |x − 3| = 7
2. Solve: |2x + 1| = 9
3. Solve: |x − 5| < 2
4. Solve: |x + 2| ≥ 4
5. How many solutions does |3x − 6| = 0 have?
6. How many solutions does |x − 4| = −2 have?
7. What is the minimum value of f(x) = |x − 7| + 3?
8. What is the sum of the solutions of |2x − 5| = 11?
9. A machine part's length ℓ must be within 0.5 mm of 20 mm. Write this as an absolute-value inequality.
10. What is the vertex of y = |x + 1| − 4?

### Answers

1. **x = 10 or −4**.
2. **x = 4 or −5**.
3. **3 < x < 7**.
4. **x ≤ −6 or x ≥ 2**.
5. **One** — 3x − 6 = 0 → x = 2.
6. **None** — absolute value can't be negative.
7. **3** — at x = 7.
8. **5** — x = 8 and x = −3.
9. **|ℓ − 20| ≤ 0.5**.
10. **(−1, −4)**.
