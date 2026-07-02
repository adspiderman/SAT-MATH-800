# Lesson 1.1 — Linear Equations in One Variable

## Concepts

A linear equation in one variable has the form `ax + b = c` (possibly disguised). Solving = isolating x with inverse operations, applied to **both sides**.

### The standard playbook
1. Clear parentheses (distribute).
2. Clear fractions (multiply everything by the least common denominator).
3. Collect variable terms on one side, constants on the other.
4. Divide by the coefficient.

**Worked example 1.** Solve 4(2x − 3) + 5 = 3x + 13.
- Distribute: 8x − 12 + 5 = 3x + 13 → 8x − 7 = 3x + 13
- Collect: 5x = 20 → **x = 4**

**Worked example 2 (fractions).** Solve x/3 + (x−1)/2 = 5.
- LCD is 6, multiply every term: 2x + 3(x − 1) = 30
- 5x − 3 = 30 → x = 33/5. **x = 33/5** (leave it as a fraction — SAT answers are often non-integers).

### Special cases — a favorite SAT theme

Reduce the equation; watch what happens to x:

| Result | Meaning |
|--------|---------|
| x = number | Exactly one solution |
| true statement, x gone (e.g., 5 = 5) | **Infinitely many** solutions |
| false statement, x gone (e.g., 5 = 7) | **No** solution |

**Worked example 3.** For what value of a does a(x + 2) = 3x + 6 + x have no solution?
- Left: ax + 2a. Right: 4x + 6.
- No solution requires equal x-coefficients but unequal constants: a = 4 gives constants 8 vs 6 ✓ (unequal). **a = 4.**
- (If the question asked for infinitely many: impossible here, since a = 4 forces 2a = 8 ≠ 6.)

**The rule:** `px + q = rx + s` has no solution iff p = r and q ≠ s; infinitely many iff p = r and q = s.

## Desmos angle

Type the full equation exactly as written (e.g., `4(2x-3)+5 = 3x+13`) — Desmos draws a vertical line at the solution. For special-case questions, graph each side as `y = left` and `y = right`: parallel lines → no solution; identical lines → infinitely many.

## Traps

1. **Answering the wrong thing.** The SAT loves solving for x but asking for `3x − 2` or `x + 5`. Circle what's asked before answering. Often you can get the asked-for quantity *without* finding x (e.g., given 5x = 20, asked for 10x: just double → 40).
2. **Distributing negatives:** −3(x − 4) = −3x **+ 12**, not −12.
3. **Fraction-clearing misses a term** — multiply *every* term by the LCD, including lone constants.

## Practice Set (no calculator except #9–10; answers below)

1. Solve: 7x − 9 = 4x + 12
2. Solve: 3(2x + 1) − 4 = 5(x − 2) + 16
3. If 5(x − 2) = 5x + k has infinitely many solutions, what is k?
4. Solve: (2x + 1)/5 = (x − 3)/2
5. If 3x + 7 = 22, what is the value of 6x + 7?
6. Solve: 0.2x + 1.4 = 0.5x − 0.1
7. For what value of c does cx + 6 = 3(x + 2) + 2x have infinitely many solutions?
8. Solve: (x/4) − (x/6) = 2
9. The equation 4(3x − 5) = 2(6x + k) has no solution. Which of the following CANNOT be the value of k? A) −10 B) 10 C) 0 D) 5
10. The equation 2(hx − 4) = 14x − 8 has infinitely many solutions. What is h?

### Answers

1. **x = 7** — 3x = 21.
2. **x = 7** — left: 6x + 3 − 4 = 6x − 1; right: 5x − 10 + 16 = 5x + 6; so x = 7. Verify: 3(15) − 4 = 41 and 5(5) + 16 = 41 ✓.
3. **k = −10** — left is 5x − 10; infinitely many solutions requires identical sides.
4. **x = 17** — cross-multiply: 2(2x + 1) = 5(x − 3) → 4x + 2 = 5x − 15 → x = 17. Verify: 35/5 = 7 and 14/2 = 7 ✓.
5. **37** — from 3x = 15, double to get 6x = 30, then add 7. (Faster than solving for x first.)
6. **x = 5** — 1.5 = 0.3x.
7. **c = 5** — right side simplifies to 5x + 6; sides are identical when c = 5.
8. **x = 24** — multiply by LCD 12: 3x − 2x = 24.
9. **A (−10)** — left: 12x − 20; right: 12x + 2k. Equal x-coefficients always; no solution requires 2k ≠ −20, so k can be anything **except** −10.
10. **h = 7** — 2hx − 8 = 14x − 8 → 2h = 14.
