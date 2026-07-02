# Lesson 2.2 — Polynomials & Factoring

## Concepts

### Multiplying — FOIL and the special products

(3x − 2)(2x + 5) = 6x² + 15x − 4x − 10 = 6x² + 11x − 10.

**Special products (memorize; the SAT uses them both directions):**

| Pattern | Expansion |
|---------|-----------|
| (a + b)² | a² + 2ab + b² |
| (a − b)² | a² − 2ab + b² |
| (a + b)(a − b) | a² − b² |

The **difference of squares** a² − b² = (a + b)(a − b) is the single most-tested factoring pattern. Recognize it in disguise: x⁴ − 16 = (x² − 4)(x² + 4) = (x − 2)(x + 2)(x² + 4).

**Slick use:** if a² − b² = 40 and a − b = 4, then (a + b)(a − b) = 40 → a + b = **10** — no need to find a or b.

### Factoring playbook (in order)

1. **GCF first**: 6x³ + 9x² = 3x²(2x + 3).
2. **Difference of squares**: x² − 49 = (x − 7)(x + 7).
3. **Simple trinomial** x² + bx + c: find two numbers that multiply to c, add to b. x² − 7x + 12 = (x − 3)(x − 4).
4. **Hard trinomial** ax² + bx + c: find two numbers multiplying to a·c, adding to b, then split & group. 6x² + x − 15: a·c = −90; numbers 10, −9 → 6x² + 10x − 9x − 15 = 2x(3x + 5) − 3(3x + 5) = (3x + 5)(2x − 3).

### Zeros ↔ factors ↔ graph (the big theorem)

For a polynomial p:

```
(x − a) is a factor  ⇔  p(a) = 0  ⇔  the graph crosses the x-axis at x = a
```

And the **remainder theorem**: dividing p(x) by (x − a) leaves remainder **p(a)**. No long division needed — just evaluate.

**Worked example.** What is the remainder when p(x) = x³ − 4x² + x + 6 is divided by x − 2?
- p(2) = 8 − 16 + 2 + 6 = **0**. (So x − 2 is in fact a factor.)

**Worked example.** (x + 3) is a factor of p(x) = x³ + 2x² + kx + 6. Find k.
- p(−3) = 0: −27 + 18 − 3k + 6 = 0 → −3 − 3k = 0 → **k = −1**.

## Desmos angle

- Factoring check: graph the original and your factored form — identical graphs = correct.
- "Which is a factor of p(x)?" → graph p and read the x-intercepts. Intercept at x = 3 ⇒ factor (x − 3).
- Remainder theorem: define `p(x) = ...`, then type `p(2)` for an instant remainder.

## Traps

1. **(a + b)² has a middle term.** Writing a² + b² for (a + b)² is the classic. Related: a² + b² does **not** factor (over the reals); a² − b² does.
2. **Sign of the root vs the factor:** factor (x + 3) ⇒ zero at x = **−3**, not +3.
3. GCF first — trying to factor 2x² + 8x + 6 as a hard trinomial wastes time; it's 2(x + 1)(x + 3).
4. In sum/difference-of-cubes disguise: (x³ − 8)/(x − 2) = x² + 2x + 4 (do polynomial division or recognize a³ − b³ = (a − b)(a² + ab + b²)).

## Practice Set

1. Expand: (3x − 2)(2x + 5)
2. Factor: x² − 7x + 12
3. Factor: 6x² + x − 15
4. Factor: x² − 49
5. (x + 3) is a factor of p(x) = x³ + 2x² + kx + 6. What is k?
6. What is the remainder when x³ − 4x² + x + 6 is divided by x − 2?
7. What is the sum of the zeros of f(x) = (x + 2)(x − 5)?
8. Expand: (2x − 3)²
9. Factor completely: x⁴ − 16
10. If p(3) = 0 for polynomial p, which of these MUST be a factor of p(x)? A) x + 3 B) x − 3 C) 3x D) x² − 3
11. For x ≠ 2, simplify: (x³ − 8)/(x − 2)
12. If a² − b² = 40 and a − b = 4, what is a + b?

### Answers

1. **6x² + 11x − 10**.
2. **(x − 3)(x − 4)**.
3. **(3x + 5)(2x − 3)** — verify middle term: −9x + 10x = x ✓.
4. **(x − 7)(x + 7)**.
5. **k = −1** — worked example.
6. **0** — p(2) = 0.
7. **3** — zeros −2 and 5.
8. **4x² − 12x + 9** — don't forget the middle term.
9. **(x − 2)(x + 2)(x² + 4)** — x² + 4 has no real factors.
10. **B** — zero at 3 ⇔ factor (x − 3).
11. **x² + 2x + 4** — difference of cubes.
12. **10** — (a+b)(a−b) = 40 with a − b = 4.
