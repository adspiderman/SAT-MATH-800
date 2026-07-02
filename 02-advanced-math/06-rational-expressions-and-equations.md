# Lesson 2.6 — Rational Expressions & Equations

## Concepts

A rational expression is a fraction with polynomials. Two golden rules:
1. **The denominator can never be 0** — values that zero a denominator are excluded (and are where extraneous solutions hide).
2. Factor first — everything simplifies through factoring.

### Simplifying

(x² − 4)/(x² + 5x + 6) = (x − 2)(x + 2) / [(x + 2)(x + 3)] = **(x − 2)/(x + 3)**, for x ≠ −2, −3.
Cancel **factors**, never terms: (x + 4)/4 does NOT simplify to x.

### Adding/subtracting — common denominator

1/(x − 1) + 2/(x + 1) = [(x + 1) + 2(x − 1)] / [(x − 1)(x + 1)] = **(3x − 1)/(x² − 1)**.

### Splitting (the SAT's favorite "equivalent form")

(4x² + 6x)/(2x) = 2x + 3. Also the reverse: rewriting (ax + b)/(cx + d) as q + r/(cx + d) — do polynomial division or match forms.

### Solving rational equations

Multiply through by the LCD, solve, then **check candidates against original denominators**.

**Worked example 1.** Solve x/(x − 4) = 4/(x − 4) + 2.
- ×(x − 4): x = 4 + 2(x − 4) → x = 2x − 4 → x = 4.
- But x = 4 zeroes the original denominators → extraneous. **No solution.**

**Worked example 2.** Solve 2/(x + 3) = 5/(x − 1).
- Cross-multiply: 2(x − 1) = 5(x + 3) → 2x − 2 = 5x + 15 → **x = −17/3** (doesn't zero anything ✓).

### Work/rate problems (classic rational application)

Rates add. A pipe filling a pool in 6 hours works at rate 1/6 pool per hour.

**Worked example 3.** Pipes fill a tank in 4 h and 12 h. Together?
- 1/4 + 1/12 = 3/12 + 1/12 = 4/12 = 1/3 → **3 hours**.

### Inverse variation

"y varies inversely with x" ⇔ xy = k (constant). If y = 9 when x = 4, then k = 36; at x = 6, y = **6**.

## Desmos angle

- Solve rational equations by graphing each side; intersections are true solutions and extraneous ones never appear. This is the safest method for this topic.
- Equivalence checks: graph the original and simplified forms — identical except possibly a hole at excluded values.
- The graph of a rational function shows vertical asymptotes at excluded x-values — useful for "for what x is f undefined?"

## Traps

1. **Extraneous solutions.** Any solution that zeroes an original denominator is invalid; "no solution" is a real SAT answer.
2. **Canceling terms instead of factors** — (x² + 3)/x² is not 3... and (x + 4)/4 ≠ x + 1.
3. When multiplying by the LCD, hit **every** term, including constants.
4. Work problems: times don't add — **rates** add. Two 6-hour pipes together take 3 hours, not 12.
5. "Varies inversely" (xy = k) vs "varies directly" (y = kx) — opposite behavior.

## Practice Set

1. Simplify: (x² − 4)/(x² + 5x + 6)
2. Solve: 3/x + 1/2 = 2
3. Solve: x/(x − 2) = 3
4. Combine into one fraction: 1/(x − 1) + 2/(x + 1)
5. Solve: 2/(x + 3) = 5/(x − 1)
6. One pipe fills a pool in 6 hours; a second fills it in 3 hours. How long together?
7. Solve: x/(x − 4) = 4/(x − 4) + 2
8. For x ≠ 0, simplify: (4x² + 6x)/(2x)
9. y varies inversely with x, and y = 9 when x = 4. What is y when x = 6?
10. Machines A and B together finish a job in 3 hours. Alone, A takes 4 hours. How long does B take alone?

### Answers

1. **(x − 2)/(x + 3)** — factor and cancel (x + 2).
2. **x = 2** — 3/x = 3/2.
3. **x = 3** — x = 3x − 6.
4. **(3x − 1)/(x² − 1)**.
5. **x = −17/3**.
6. **2 hours** — 1/6 + 1/3 = 1/2.
7. **No solution** — the candidate x = 4 is extraneous.
8. **2x + 3**.
9. **6** — k = 36.
10. **12 hours** — 1/4 + 1/B = 1/3 → 1/B = 1/12.
