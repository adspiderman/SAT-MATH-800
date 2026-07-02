# Lesson 2.10 — Isolating Variables (Literal Equations)

## Concepts

"Solve for h in terms of A and b" — same algebra as solving for x, but the answer is an expression. These are free points *if* you stay organized.

### The playbook

1. Locate every instance of the target variable.
2. Clear fractions (multiply by denominators).
3. Move all target-variable terms to one side, everything else to the other.
4. If the target appears in multiple terms, **factor it out**.
5. Divide by its coefficient (which may be a whole expression).

**Worked example 1.** A = ½bh, solve for h → 2A = bh → **h = 2A/b**.

**Worked example 2.** F = (9/5)C + 32, solve for C.
- F − 32 = (9/5)C → **C = (5/9)(F − 32)**.

**Worked example 3 (target in two places).** Solve 1/f = 1/p + 1/q for p.
- 1/p = 1/f − 1/q = (q − f)/(fq) → **p = fq/(q − f)**.

**Worked example 4 (factor out).** Solve xab = a + b for a.
- xab − a = b → a(xb − 1) = b → **a = b/(xb − 1)**.

### Roots and squares

E = mc², solve for c: c² = E/m → **c = √(E/m)** (physical quantities: take the positive root; pure algebra: ±).

## Desmos angle

Limited direct help (the answer is symbolic), but you can **verify**: pick easy numbers (b = 2, h = 3 → A = 3), then check that your rearranged formula returns h = 3 from A = 3, b = 2. For MC versions, plug the same numbers into each answer choice — only the right one matches. This "plug in numbers" verification is the standard defense on these questions ([Lesson 5.2](../05-strategies/02-plugging-in-and-backsolving.md)).

## Traps

1. **Dividing only part of a side.** From 2A = bh + c, h = (2A − c)/b — the whole side gets divided, so subtract c *first*.
2. When the target is in a denominator, multiply it out first; don't try to "flip" pieces casually. 1/p = k → p = 1/k only when the *entire* side is 1/p.
3. Distribute-then-isolate beats clever shortcuts. Slow is smooth, smooth is fast.
4. Answer choices often differ only in sign or in what's inside a parenthesis — after solving, re-derive one step rather than eyeballing.

## Practice Set

Solve each for the indicated variable.

1. A = ½bh, for h
2. F = (9/5)C + 32, for C
3. V = πr²h, for h
4. y = mx + b, for x
5. P = 2ℓ + 2w, for w
6. a = (v − u)/t, for v
7. S = 2πrh + 2πr², for h
8. 1/f = 1/p + 1/q, for p
9. E = mc², for c (c > 0)
10. x = (a + b)/(ab), for a

### Answers

1. **h = 2A/b**
2. **C = (5/9)(F − 32)**
3. **h = V/(πr²)**
4. **x = (y − b)/m**
5. **w = (P − 2ℓ)/2**
6. **v = u + at**
7. **h = (S − 2πr²)/(2πr)**
8. **p = fq/(q − f)**
9. **c = √(E/m)**
10. **a = b/(xb − 1)** — xab = a + b → a(xb − 1) = b.
