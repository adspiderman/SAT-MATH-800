# Lesson 0.6 — Desmos Mastery (Mandatory)

The Digital SAT embeds the Desmos graphing calculator in every math question. Used well, it solves or verifies a third of the test faster and more reliably than algebra. **This is the highest ROI lesson in the course.**

Practice everything below in the exact test-day version: [Desmos SAT Testing Calculator](https://www.desmos.com/testing/cb-digital-sat/graphing).

## Core skill 1 — Solve any equation by graphing

To solve `f(x) = g(x)`, type both sides as separate expressions and click the intersection point(s).

**Example:** Solve `2x² - 3x - 5 = x + 1`.
- Line 1: `y = 2x² - 3x - 5`
- Line 2: `y = x + 1`
- Click the gray intersection dots → x = -1 and x = 3. Done in 15 seconds.

Even faster for "= 0" problems: type the whole equation `2x² - 4x - 6 = 0` directly — Desmos draws vertical lines at the solutions. Or type `y = 2x² - 4x - 6` and click the x-intercepts.

## Core skill 2 — Systems of equations

Type both equations **exactly as given** — no rearranging needed. Desmos accepts `3x + 4y = 12` directly. The intersection point is the solution.

- Parallel lines (no intersection) → no solution.
- Same line → infinitely many solutions.
- This works for nonlinear systems too (line + parabola, circle + line).

## Core skill 3 — Sliders for unknown constants

The killer feature for "for what value of k..." questions.

**Example:** "For what value of k does `kx + 3y = 12` have no solution with `2x + 6y = 9`?"
- Type both equations, using `k` — Desmos offers "add slider: k". Click it.
- Drag k until the lines are parallel → k = 1... then verify precisely (see Unit 1.3 for the algebra: k/2 = 3/6 → k = 1).
- Use the slider to *find* the neighborhood, then confirm with algebra or by setting the slider step size.

Sliders also crush: "the system has exactly one solution", "the parabola is tangent to the line", "f(x) has no real zeros".

## Core skill 4 — Function evaluation and tables

- Define `f(x) = 3x² - 7x + 2`, then type `f(5)` → instant value.
- Type `f(a) = 40` won't solve, but graphing `y = f(x)` and `y = 40` will.
- Click the wrench/table icon or type `x = 5` as a vertical line to read points.

## Core skill 5 — Statistics one-liners

With a list `A = [4, 7, 7, 9, 12]`:
- `mean(A)`, `median(A)`, `stdev(A)` (sample), `stdevp(A)` (population), `min(A)`, `max(A)`
- For frequency tables, build the full list or use, e.g., `mean([3,3,3,5,5,8])`.

## Core skill 6 — Regression (line/curve of best fit)

Given data points:
1. Make a table (`+` → table), enter x₁, y₁ values.
2. Type `y₁ ~ mx₁ + b` → Desmos computes the best-fit slope and intercept.
3. Works for quadratics too: `y₁ ~ ax₁² + bx₁ + c`, and exponentials: `y₁ ~ a·b^x₁`.

This turns "which equation best models the data" questions into 30-second wins.

## Core skill 7 — Verify algebra instantly

Did you factor/simplify correctly? Graph your original expression and your simplified one. **If the graphs coincide, your algebra is right.** This near-eliminates algebra-slip errors on equivalent-expression questions — check every one this way when time allows.

## When NOT to use Desmos

- Simple arithmetic/one-step algebra — typing costs more than thinking.
- Problems with *only* variables and no numbers (pure symbolic manipulation) — though plugging in numbers + Desmos can still verify.
- When you have < 2 minutes left and 3 questions — triage first ([Lesson 5.5](../05-strategies/05-time-management.md)).

## Drill (do these now, in the testing calculator)

1. Solve `x² + 2x - 8 = 0` by graphing. *(x = -4, 2)*
2. Solve the system `3x - y = 7`, `x + 2y = 0`. *((2, -1))*
3. Find the minimum value of `f(x) = 2x² - 12x + 5`. *(-13, at x = 3)*
4. For what k is `y = 2x + k` tangent to `y = x²`? (Use a slider.) *(k = -1)*
5. `mean([88, 92, 79, 95, 91])` and `median` of the same. *(89, 91)*
6. Fit a line to (1, 3.1), (2, 4.9), (3, 7.2), (4, 8.8) — slope ≈ ? *(≈1.96)*
7. Verify that `(x+3)² - (x-3)²` simplifies to `12x` by graphing both.

Target: all 7 in under 10 minutes. Re-run this drill weekly until it's under 6.
