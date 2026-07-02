# The Hard Problem Gauntlet

**20 problems at the difficulty of the hardest Module 2 questions.** These are the questions that decide 750 vs 800. Untimed on your first pass — the goal is to *finish* every one. Second pass (a week later): 40 minutes total.

All are SPR-style: produce the value. Full solutions below — attempt all 20 before reading any.

---

**1.** The line y = mx + 4 intersects the parabola y = x² + 2x + 7 at exactly one point. What is the sum of all possible values of m?

**2.** The equation x² − 12x + k = 0 has two solutions that differ by 2. What is k?

**3.** The function f(x) = x² + bx + c has minimum value −9, occurring at x = 2. What is the value of b · c?

**4.** The system 3x − 5y = 13, ax + by = 26 has infinitely many solutions. What is a − b?

**5.** For the function p(t) = a · 2^(t/5), p(20) = 48. What is p(10)?

**6.** A circle has a diameter with endpoints (−3, 4) and (5, −2). What is the square of its radius?

**7.** In a right triangle, tan A = 4/3 for acute angle A, and the hypotenuse is 35. What is the triangle's perimeter?

**8.** How many integers satisfy |2x + 7| ≤ 11?

**9.** How many solutions does x/(x − 3) + 2 = 3/(x − 3) have?

**10.** Given that p(x) = x³ + 2x² − 5x − 6 and p(2) = 0, what is the smallest zero of p?

**11.** A right triangle has legs 6 and 8. The altitude to the hypotenuse divides it into two segments. What is the length of the shorter segment?

**12.** The mean of 7 numbers is 15. When one number is removed, the mean of the remaining 6 is 13. What number was removed?

**13.** A population increases 20% each year for two years, then decreases 25% in the third year. What is the net percent change over the three years?

**14.** The solution region of y ≤ −2x + 10 and y ≤ x + 1 has a maximum possible y-value. What is it?

**15.** If f(x) = x² − 1 and g(x) = 2x + 3, what is the sum of all solutions of f(g(x)) = 0?

**16.** The line y = 2x + b, with b > 0, is tangent to the circle x² + y² = 20. What is b?

**17.** If sin 40° = cos k° and 0 < k < 90, what is k?

**18.** A random sample finds 62% of a city's 24,000 households recycle, with a 5-percentage-point margin of error. Based on this, what is the *minimum* plausible number of recycling households?

**19.** If x² + y² = 41 and xy = 20, what is the positive value of x + y?

**20.** A cone's radius is doubled and its height is halved. The new volume is how many times the original?

---

## Solutions

**1. Answer: 4.** One intersection ⇔ x² + 2x + 7 = mx + 4 has one solution ⇔ x² + (2 − m)x + 3 = 0 has D = 0: (2 − m)² = 12 → m = 2 ± 2√3. Sum = (2 + 2√3) + (2 − 2√3) = 4. *(Insight: "sum of all possible values" often survives even when each value is irrational.)*

**2. Answer: 35.** Roots p, q: p + q = 12 (Vieta), p − q = 2 → p = 7, q = 5 → k = pq = 35.

**3. Answer: 20.** Vertex form: f(x) = (x − 2)² − 9 = x² − 4x − 5 → b = −4, c = −5 → bc = 20.

**4. Answer: 16.** Infinitely many ⇔ second equation is a multiple of the first. 26 = 2 × 13, so a = 6, b = −10 → a − b = 16.

**5. Answer: 12.** p(20) = a · 2⁴ = 16a = 48 → a = 3. p(10) = 3 · 2² = 12.

**6. Answer: 25.** Diameter length = √(8² + 6²) = 10 → r = 5 → r² = 25. (Center (1, 1) isn't even needed.)

**7. Answer: 84.** tan A = 4/3 → a 3-4-5 triangle scaled: hypotenuse 35 = 5 × 7 → legs 21 and 28. Perimeter 21 + 28 + 35 = 84.

**8. Answer: 12.** −11 ≤ 2x + 7 ≤ 11 → −18 ≤ 2x ≤ 4 → −9 ≤ x ≤ 2. Integers −9 through 2: 12 of them. *(Count: 2 − (−9) + 1.)*

**9. Answer: 0.** Multiply by (x − 3): x + 2(x − 3) = 3 → 3x = 9 → x = 3 — which zeroes the original denominators. Extraneous → no solutions. *(Desmos: the two sides' graphs never intersect.)*

**10. Answer: −3.** Factor out (x − 2): x³ + 2x² − 5x − 6 = (x − 2)(x² + 4x + 3) = (x − 2)(x + 1)(x + 3). Zeros: 2, −1, −3.

**11. Answer: 3.6.** Hypotenuse = 10. The altitude creates similar triangles: each leg is the geometric mean, so the segment adjacent to the leg of 6 satisfies 6² = 10p → p = 3.6 (and 8² = 10q → q = 6.4 ✓ sums to 10).

**12. Answer: 27.** Totals: 7 × 15 = 105; remaining 6 × 13 = 78; removed = 105 − 78 = 27.

**13. Answer: +8%.** Multiplier: 1.2 × 1.2 × 0.75 = 1.08.

**14. Answer: 4.** The region lies below both lines; the highest point is their intersection: −2x + 10 = x + 1 → x = 3, y = 4.

**15. Answer: −3.** (2x + 3)² − 1 = 0 → 2x + 3 = ±1 → x = −1 or x = −2. Sum −3. *(Or Vieta on 4x² + 12x + 8 = 0: sum = −3.)*

**16. Answer: 10.** Substitute: x² + (2x + b)² = 20 → 5x² + 4bx + b² − 20 = 0. Tangency: D = 16b² − 20(b² − 20) = 0 → −4b² + 400 = 0 → b = 10. *(Or distance from center to line = radius: b/√5 = √20.)*

**17. Answer: 50.** sin θ = cos(90 − θ): k = 90 − 40.

**18. Answer: 13,680.** Minimum plausible proportion = 62% − 5% = 57% → 0.57 × 24,000 = 13,680.

**19. Answer: 9.** (x + y)² = x² + 2xy + y² = 41 + 40 = 81 → x + y = 9. *(Recognize the expansion; never solve for x and y.)*

**20. Answer: 2.** V = (1/3)πr²h → new V = (1/3)π(2r)²(h/2) = (1/3)πr²h × (4 × ½) = 2V.

---

## Scoring

- **18–20:** 800-ready on content. Your remaining risk is pacing and carelessness — drill [5.5](../05-strategies/05-time-management.md) and keep the [error log](../05-strategies/06-error-log.md) hot.
- **14–17:** Strong. Each miss maps to a lesson — re-do that lesson's practice set this week.
- **≤13:** You're not far off — most gauntlet misses are one insight away. Study each solution until the *first move* (the insight) feels findable, then retry from scratch in 3 days.
