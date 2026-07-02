# Lesson 1.4 — Linear Inequalities

## Concepts

### One variable — solve like an equation, with ONE extra rule

**Multiplying or dividing both sides by a negative number flips the inequality sign.** This single rule is behind a huge share of inequality errors.

**Worked example 1.** 5 − 2x > 11 → −2x > 6 → x **<** −3 (sign flipped on divide by −2).

### Compound inequalities

5 < 2x + 1 ≤ 13: operate on **all three parts** → 4 < 2x ≤ 12 → 2 < x ≤ 6.
"How many integers satisfy this?" → 3, 4, 5, 6 → **4 integers**. (Careful with which endpoints are included.)

### Two variables — half-planes

y > mx + b shades **above** the line; y < mx + b shades **below**. (Only reliable once y is isolated with a *positive* coefficient!)
- ≤ or ≥ → solid boundary line (line included)
- < or > → dashed boundary (line excluded)

**The universal tool: test the point.** "Is (a, b) in the solution set?" → plug it in. Both inequalities true → yes. This is faster and safer than reasoning about shading.

### Systems of inequalities

The solution set is the **overlap** of the half-planes. Typical SAT asks:
- "Which point is a solution?" → test each choice (or graph both in Desmos — it shades automatically; type them exactly as written).
- "Which quadrant contains no solutions?" → graph in Desmos, look.
- Vertex of the region = intersection of the boundary *lines*.

### Word problem translation

| Phrase | Symbol |
|--------|--------|
| at least, no less than, minimum | ≥ |
| at most, no more than, maximum | ≤ |
| more than, exceeds | > |
| less than, under | < |

**Worked example 2.** You have $50. Each shirt costs $8 and shipping is a flat $6. How many shirts at most?
8n + 6 ≤ 50 → n ≤ 5.5 → **5 shirts** (round *down* — you can't buy half a shirt, and 6 shirts would exceed the budget).

## Desmos angle

Desmos shades inequality regions directly: type `y > 2x + 1` and `y < -x + 7` and the double-shaded overlap is the solution set — then check which answer-choice point lies in it by plotting the points. For "maximum/minimum value in a region" questions, the extremes occur at region vertices: click the boundary intersections.

## Traps

1. **The flip.** Every time you multiply/divide by a negative, flip. Also beware the disguised version: rewriting 3 − x > 5 as x > ... (it's x < −2).
2. **Round the correct direction** in context: max items under a budget → round down; minimum trips to carry everything → round up.
3. **Strict vs inclusive:** "at least 5" includes 5; "more than 5" doesn't. Endpoint errors are the classic inequality miss.
4. If y's coefficient is negative (e.g., x − y > 2), isolate y and flip: y < x − 2 — *now* "below the line" is correct.

## Practice Set

1. Solve: 3x − 5 < 7
2. Solve: −4x + 2 ≤ 18
3. Which point satisfies both y > 2x + 1 and y < −x + 7? A) (1, 4) B) (3, 2) C) (0, 8) D) (2, 1)
4. How many integers x satisfy 5 < 2x + 1 ≤ 13?
5. Tickets cost $8 each plus a one-time $6 fee. With $50, what is the maximum number of tickets you can buy?
6. If −2 ≤ x ≤ 4, what is the maximum value of 5 − 3x?
7. Is (4, −1) in the solution set of y ≤ ½x − 3?
8. The solution region of y ≥ x and y ≤ 2x − 2 contains points with x-values no smaller than what value?
9. A truck can carry at most 3000 pounds. It already holds 10 pallets at 120 pounds each. At 45 pounds per box, what is the maximum number of boxes that can be added?
10. Solve: 3(x − 2) > 4x + 1

### Answers

1. **x < 4** — 3x < 12.
2. **x ≥ −4** — −4x ≤ 16, flip on dividing by −4.
3. **A** — for (1, 4): 4 > 3 ✓ and 4 < 6 ✓. (B: 2 > 7 ✗. C: 8 > 1 ✓ but 8 < 7 ✗. D: 1 > 5 ✗.)
4. **4** — 2 < x ≤ 6 → x ∈ {3, 4, 5, 6}.
5. **5** — 8n + 6 ≤ 50 → n ≤ 5.5, round down.
6. **11** — 5 − 3x is largest when x is smallest: x = −2 → 5 + 6 = 11.
7. **Yes** — ½(4) − 3 = −1 and −1 ≤ −1 is true (inclusive).
8. **2** — boundaries meet where x = 2x − 2 → x = 2; for x < 2, x > 2x − 2 means no y can satisfy both.
9. **40** — 45b + 1200 ≤ 3000 → b ≤ 40.
10. **x < −7** — 3x − 6 > 4x + 1 → −7 > x.
