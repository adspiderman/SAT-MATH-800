# Lesson 1.3 — Systems of Linear Equations

## Concepts

A system of two linear equations asks: where do two lines meet?

| Geometry | Algebra outcome | Solutions |
|----------|-----------------|-----------|
| Lines cross | x = a, y = b | Exactly one |
| Parallel, distinct | contradiction (0 = 5) | None |
| Same line | identity (0 = 0) | Infinitely many |

### Method 1 — Substitution (best when a variable is already isolated)

y = 2x + 1 and 3x + y = 16 → 3x + (2x + 1) = 16 → 5x = 15 → x = 3, y = 7.

### Method 2 — Elimination (best for standard form)

2x + 3y = 12
4x − 3y = 6

Add the equations (the y's cancel): 6x = 18 → x = 3, then y = 2.

If nothing cancels immediately, multiply one or both equations first. To solve
3x + 2y = 22
x + 4y = 24
multiply the first by 2 → 6x + 4y = 44, subtract the second → 5x = 20 → x = 4, y = 5.

### Method 3 — Desmos (best almost always on the Digital SAT)

Type both equations exactly as printed; click the intersection. **For a pure "solve the system" question this should be your default** — 20 seconds, no algebra risk. Save the algebra for questions where the system has parameters (k, a, c) — and even those often yield to a slider.

### Number-of-solutions conditions (memorize)

For a₁x + b₁y = c₁ and a₂x + b₂y = c₂:

- **One solution:** a₁/a₂ ≠ b₁/b₂ (different slopes)
- **No solution:** a₁/a₂ = b₁/b₂ ≠ c₁/c₂ (same slope, different lines)
- **Infinitely many:** a₁/a₂ = b₁/b₂ = c₁/c₂ (same line)

**Worked example.** For what value of k does kx + 2y = 10, 3x + y = 4 have no solution?
- Same slope: k/3 = 2/1 → k = 6. Check constants: 10/4 ≠ 2 ✓ (different lines). **k = 6.**

**Worked example (infinitely many).** 6x − 9y = 15 and ax − 6y = 10.
- Scale second to match: multiply by 3/2 → (3a/2)x − 9y = 15. Identical requires 3a/2 = 6 → **a = 4.**

### Systems from word problems

Assign a variable to each unknown quantity; one equation per fact.

**Worked example.** Adult tickets cost $12, child tickets $8. 20 tickets sold for $208 total. How many adult tickets?
- a + c = 20 and 12a + 8c = 208.
- Substitute c = 20 − a: 12a + 160 − 8a = 208 → 4a = 48 → **a = 12.**

## Traps

1. **Answering x when the question asks for y** — or for x + y, or xy. The Digital SAT does this constantly. The intersection point in Desmos gives you both coordinates; then read the question again.
2. **Shortcut alert:** asked for x + y or x − y? Try adding/subtracting the equations as-is first — it frequently gives the target combination immediately.
3. In no/infinite-solution problems, **check the constants** — matching slopes alone doesn't distinguish "no solution" from "infinitely many."
4. Word problems: keep units straight — one equation usually counts *items*, the other counts *money/weight/points*.

## Practice Set

1. Solve: y = 2x + 1 and 3x + y = 16.
2. Solve: 2x + 3y = 12 and 4x − 3y = 6.
3. The system 3x − 6y = 9 and x − 2y = k has infinitely many solutions. What is k?
4. For what value of k does kx + 2y = 10, 3x + y = 4 have no solution?
5. x + y = 14 and x − y = 6. What is the value of xy?
6. 3x + 2y = 22 and x + 4y = 24. What is x + y?
7. A drawer has dimes and quarters: 20 coins worth $3.50 total. How many quarters? (Dime = $0.10, quarter = $0.25.)
8. 6x − 9y = 15 and ax − 6y = 10 has infinitely many solutions. What is a?
9. The system y = 2x + b and 2x − y = 7 has at least one solution. What is b?
10. At a bakery, 3 croissants and 2 muffins cost $14.50; 1 croissant and 4 muffins cost $11.50. What is the cost of one croissant?

### Answers

1. **(3, 7)** — substitution above.
2. **(3, 2)** — add to eliminate y.
3. **k = 3** — first equation ÷3 is x − 2y = 3.
4. **k = 6** — slopes match (k/3 = 2), constants differ (10 ≠ 8).
5. **40** — x = 10, y = 4 (add, then subtract the equations).
6. **9** — x = 4, y = 5 (elimination shown above).
7. **10** — d + q = 20, 0.10d + 0.25q = 3.50 → 0.10(20 − q) + 0.25q = 3.5 → 2 + 0.15q = 3.5 → q = 10.
8. **a = 4** — scale to match coefficients.
9. **b = −7** — rewrite second: y = 2x − 7. Same slope as first, so a solution exists only if the lines are identical: b = −7 (then infinitely many).
10. **$3.50** — 3c + 2m = 14.5 and c + 4m = 11.5. Multiply the first by 2: 6c + 4m = 29; subtract the second: 5c = 17.5 → c = 3.5. Check: m = 2, and 3(3.5) + 2(2) = 14.5 ✓.
