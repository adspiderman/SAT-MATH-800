# Lesson 2.1 — Exponents & Radicals

## Concepts

### The exponent rules (memorize cold)

| Rule | Statement | Example |
|------|-----------|---------|
| Product | xᵃ · xᵇ = xᵃ⁺ᵇ | x⁵ · x³ = x⁸ |
| Quotient | xᵃ / xᵇ = xᵃ⁻ᵇ | x⁵ / x² = x³ |
| Power | (xᵃ)ᵇ = xᵃᵇ | (x³)⁴ = x¹² |
| Distributed power | (xy)ᵃ = xᵃyᵃ | (2x³)⁴ = 16x¹² |
| Zero | x⁰ = 1 (x ≠ 0) | 7⁰ = 1 |
| Negative | x⁻ᵃ = 1/xᵃ | x⁻² = 1/x² |
| Fractional | x^(a/b) = (ᵇ√x)ᵃ | 8^(2/3) = (³√8)² = 4 |

**Fractional exponents: denominator = root, numerator = power.** "Power over root."

### Solving exponential equations — match the bases

If bᵘ = bᵛ (same base b), then u = v.

**Worked example 1.** Solve 2ˣ · 4ˣ = 512.
- 4ˣ = 2²ˣ, so left side = 2³ˣ. 512 = 2⁹. So 3x = 9 → **x = 3**.

**Worked example 2.** Solve 9ˣ = 27.
- Both are powers of 3: 3²ˣ = 3³ → **x = 3/2**.

### Radical equations — isolate, square, CHECK

Squaring both sides can create **extraneous solutions**. Always test candidates in the original.

**Worked example 3.** Solve √(2x − 3) = x − 3.
- Square: 2x − 3 = x² − 6x + 9 → x² − 8x + 12 = 0 → (x − 2)(x − 6) = 0 → x ∈ {2, 6}
- Check x = 2: LHS = √1 = 1, RHS = −1 ✗ extraneous.
- Check x = 6: LHS = √9 = 3, RHS = 3 ✓. **x = 6 only.**

### Simplifying radicals

√75 = √(25·3) = 5√3. Pull out the largest perfect square. Also: √a · √b = √(ab), and √(a²) = |a|.

## Desmos angle

- Numeric checks: type `8^(2/3)` directly → 4.
- Radical equations: graph `y = sqrt(2x-3)` and `y = x-3`; the intersections are the *true* solutions — Desmos never shows extraneous ones. This makes it the perfect checker for this topic.
- "Which expression is equivalent" with exponents: graph both expressions; identical curves = equivalent.

## Traps

1. **(x + y)² ≠ x² + y²** and **√(x² + y²) ≠ x + y**. The single most tempting wrong move in algebra.
2. Extraneous solutions after squaring — the SAT *designs* radical questions around this. An answer choice will be the extraneous root.
3. Negative exponents make **reciprocals**, not negatives: 2⁻³ = 1/8, not −8.
4. x⁻² + y is NOT 1/(x² + y) — the negative exponent applies only to its own base.
5. (3x)² = 9x², but 3x² is just 3x² — parentheses matter.

## Practice Set

1. Simplify: x⁵ · x³ / x²
2. Simplify: (2x³)⁴
3. Evaluate: 8^(2/3)
4. Solve: √(3x + 1) = 5
5. Solve: x^(1/2) = 9
6. Simplify: √75
7. Solve: 3^(x+2) = 81
8. If (xᵃ)³ = x¹², what is a?
9. Solve: √(2x − 3) = x − 3
10. Solve: 2ˣ · 4ˣ = 512
11. Write with positive exponents: (x²y⁻³)⁻²
12. Solve: 9ˣ = 27

### Answers

1. **x⁶** — x⁸/x² .
2. **16x¹²**.
3. **4** — cube root of 8 is 2; 2² = 4.
4. **x = 8** — 3x + 1 = 25. (Check: √25 = 5 ✓)
5. **x = 81** — square both sides.
6. **5√3**.
7. **x = 2** — 81 = 3⁴ → x + 2 = 4.
8. **a = 4** — 3a = 12.
9. **x = 6** — worked example 3; x = 2 is extraneous.
10. **x = 3** — worked example 1.
11. **y⁶/x⁴** — x⁻⁴y⁶.
12. **x = 3/2** — 3²ˣ = 3³.
