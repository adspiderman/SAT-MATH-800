# Lesson 2.5 — Exponential Functions

## Concepts

### The model

```
f(x) = a · bˣ      a = initial value (f(0)),  b = ratio per step
```

- b > 1: **growth**. 0 < b < 1: **decay**.
- Percent language: growing r% per period → b = 1 + r/100; decaying r% → b = 1 − r/100.
  - "increases 4% per year, starts at 300" → P(t) = 300(1.04)ᵗ
  - "decreases 20% per year" → b = 0.80
- Doubling every k periods: f(t) = a · 2^(t/k). Half-life k: f(t) = a · (1/2)^(t/k).

**Worked example 1.** 50 bacteria double every 6 hours. Population after 24 hours?
- 24/6 = 4 doublings → 50 · 2⁴ = **800**.

**Worked example 2.** A 320 g sample has half-life 8 days. Amount after 24 days?
- 3 half-lives → 320 · (1/2)³ = **40 g**.

### Linear vs exponential (table recognition)

| x | 0 | 1 | 2 | 3 |
|---|---|---|---|---|
| linear | 5 | 8 | 11 | 14 | ← constant **difference** (+3)
| exponential | 5 | 10 | 20 | 40 | ← constant **ratio** (×2)

"Which function models the table?" → check differences, then ratios.

### Building a·bˣ from two points

Through (0, 4) and (2, 36): a = 4 (the y-intercept); 4b² = 36 → b² = 9 → b = 3 → **f(x) = 4 · 3ˣ**.
If x = 0 isn't given, divide the two equations so a cancels.

### Compound interest

Value = P(1 + r)ᵗ for annual compounding. $1000 at 6%: 1000(1.06)ᵗ; after 2 years, $1123.60. (The SAT rarely goes beyond annual/periodic compounding; the formula is just the growth model.)

## Desmos angle

- Evaluate ugly powers instantly: `12000 * 0.95^7`.
- "Which equation models the data?" → table + regression `y₁ ~ a*b^x₁`.
- Compare growth claims: graph both models; e.g., "after how many years does A exceed B?" → intersection.
- Solve 2ˣ = 8^(x−2) style equations by graphing both sides if base-matching feels risky.

## Traps

1. **Growth factor vs growth rate:** 4% growth means b = 1.04, NOT b = 4 or 0.04. And "increases by 100%" means ×2.
2. **Decay:** decreasing 20% → multiply by 0.80 (not by 0.20 — that would keep 20%).
3. **Per-period mismatch:** doubles every 6 hours ≠ ×2 per hour. Exponent must be t/6.
4. Percent change applies to the *current* amount (that's what makes it exponential, not linear). "+$30 each year" is linear; "+3% each year" is exponential.
5. f(x) = a·bˣ has y-intercept a — and never touches the x-axis (no x-intercept).

## Practice Set

1. Write the model: a population starts at 300 and grows 4% per year.
2. What multiplier corresponds to a 20% decrease per year?
3. 50 bacteria double every 6 hours. How many after 24 hours?
4. A 320 g sample has a half-life of 8 days. How much remains after 24 days?
5. If f(x) = 5 · 3ˣ, what is f(2)/f(0)?
6. A table shows g(0) = 7, g(1) = 21, g(2) = 63. Is g linear or exponential, and what is its equation?
7. $1000 is invested at 6% annual interest, compounded annually. What is the value after 2 years?
8. Solve: 2ˣ = 8^(x−2)
9. A town of 12,000 shrinks 5% per year. Write the model and find the population after 3 years (nearest whole).
10. An exponential function passes through (0, 4) and (2, 36) with b > 0. Find f(x).

### Answers

1. **P(t) = 300(1.04)ᵗ**.
2. **0.80**.
3. **800** — 4 doublings.
4. **40 g** — 3 half-lives.
5. **9** — 3²; a cancels.
6. **Exponential; g(x) = 7 · 3ˣ** — ratio 3 each step.
7. **$1123.60** — 1000(1.06)².
8. **x = 3** — 2ˣ = 2^(3x−6) → x = 3x − 6.
9. **P(t) = 12000(0.95)ᵗ; ≈ 10,289** — 12000(0.857375).
10. **f(x) = 4 · 3ˣ** — a = 4; b² = 9.
