# Lesson 1.2 — Linear Functions & Graphs

## Concepts

### Slope — the heart of everything linear

Between points (x₁, y₁) and (x₂, y₂):

```
slope m = (y₂ − y₁) / (x₂ − x₁) = rise / run = change in output per unit of input
```

- Positive slope: rises left→right. Negative: falls. Zero: horizontal (y = c). Undefined: vertical (x = c — not a function).
- **Slope is a rate.** On the SAT, slope is "dollars per mile," "gallons per hour," etc. The y-intercept is the starting value.

### The three forms of a line

| Form | Equation | Instantly gives you |
|------|----------|---------------------|
| Slope-intercept | y = mx + b | slope m, y-intercept (0, b) |
| Point-slope | y − y₁ = m(x − x₁) | slope m, point (x₁, y₁) |
| Standard | Ax + By = C | x-int (C/A, 0), y-int (0, C/B), slope **−A/B** |

Memorize slope = −A/B for standard form — it saves 20 seconds every time. Example: 5x − 2y = 10 has slope −5/(−2) = 5/2.

### Parallel & perpendicular

- Parallel: **same slope**, different intercepts.
- Perpendicular: slopes are **negative reciprocals** (m and −1/m; product = −1). Perp. to slope ½ → slope −2.

### Building a line from data

**Worked example 1.** A linear function f satisfies f(2) = 7 and f(5) = 16. Find f(0).
- Slope = (16 − 7)/(5 − 2) = 3.
- Through (2, 7): y = 3(x − 2) + 7 = 3x + 1. So **f(0) = 1**.

**Worked example 2 (table).**

| x | 1 | 3 | 5 |
|---|---|---|---|
| f(x) | 7 | 13 | 19 |

Slope = (13 − 7)/(3 − 1) = 3; extend backward from (1, 7): f(0) = 4, so f(x) = 3x + 4 and f(10) = **34**.

### Interpreting linear models

For C(m) = 3.5 + 2.4m (taxi cost, m miles):
- **2.4** = cost per additional mile (slope/rate).
- **3.5** = base fare, the cost when m = 0 (y-intercept).
- SAT interpretation questions hinge on exactly this: *slope = per-unit change; intercept = starting amount.* The correct answer choice almost always contains the phrase "for each" or "per" (slope) or "initial/at zero" (intercept).

## Desmos angle

- Given two points: enter a table with both, then `y₁ ~ mx₁ + b` — Desmos reports m and b.
- "Which line passes through (a, b)?": graph all four choices; only one hits the point.
- Perpendicularity check: graph both lines and zoom to a square window (they should meet at a right angle) — but algebra (product of slopes = −1) is faster and exact.

## Traps

1. **Slope from standard form:** the sign. 3x + 4y = 12 has slope −3/4, not 3/4.
2. **x-intercept vs y-intercept.** The x-intercept is where **y = 0**. Read which one is asked.
3. **"f(3) = 5" means the point (3, 5)** — input is x, output is y. Reversing this kills table problems.
4. **Rate interpretation:** the slope is the change *per one unit*, not the total change.
5. Points must satisfy the equation — when in doubt, plug the point in. Fastest possible check.

## Practice Set

1. What is the slope of the line through (2, −3) and (6, 5)?
2. What are the x- and y-intercepts of 3x + 4y = 24?
3. Write the equation of the line with slope −2 through (3, 1).
4. A line is parallel to y = 3x − 2 and passes through (1, 4). What is its y-intercept?
5. What is the slope of any line perpendicular to 2x + 3y = 6?
6. If f(x) = 5x − 3 and f(a) = 12, what is a?
7. A linear function has f(2) = 7 and f(5) = 16. What is f(8)?
8. What is the equation of the line through (−2, 5) and (4, 5)?
9. Line ℓ has equation y = −(3/4)x + 6. Line k is perpendicular to ℓ and passes through the origin. Where do ℓ and k intersect?
10. The total cost C, in dollars, of renting a scooter for m minutes is C = 1.00 + 0.15m. Which is the best interpretation of 0.15? A) Total cost of the rental B) Cost per minute of use C) Cost of unlocking the scooter D) Number of minutes per dollar
11. The graph of 7x − 2y = 14 crosses the x-axis at what point?
12. If the line through (1, k) and (3, 7) has slope 2, what is k?

### Answers

1. **2** — 8/4.
2. **x-int (8, 0), y-int (0, 6).**
3. **y = −2x + 7** — 1 = −2(3) + b → b = 7.
4. **1** — y = 3x + b through (1, 4): b = 1.
5. **3/2** — given slope is −2/3; negative reciprocal.
6. **3** — 5a − 3 = 12 → a = 3.
7. **25** — slope 3, so f(8) = f(5) + 3·3 = 16 + 9.
8. **y = 5** — both points have y = 5: horizontal line.
9. **(72/25, 96/25)** — k has slope 4/3 (negative reciprocal of −3/4), so k: y = (4/3)x. Set −(3/4)x + 6 = (4/3)x → 6 = (25/12)x → x = 72/25, then y = (4/3)(72/25) = 96/25. Desmos gets this in 10 seconds — exactly the kind of ugly-number problem you should graph instead of grinding.
10. **B** — slope = cost per additional minute.
11. **(2, 0)** — set y = 0: 7x = 14.
12. **3** — (7 − k)/(3 − 1) = 2 → 7 − k = 4.
