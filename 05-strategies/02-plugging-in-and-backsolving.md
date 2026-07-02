# Lesson 5.2 — Plugging In & Backsolving

Two techniques that convert hard algebra into easy arithmetic. Combined with Desmos, they form the "test-taker's toolkit" that separates trained students from smart-but-untrained ones.

## Technique 1 — Plugging in numbers (for variable-heavy problems)

When the question and answers are all in variables, **invent concrete numbers**, compute the target, and test which answer choice matches.

**Worked example.** "If x apples cost d dollars, how many dollars do y apples cost?"
A) dy/x  B) dx/y  C) xy/d  D) d/(xy)

- Pick easy numbers: x = 2 apples, d = 6 dollars, y = 4 apples.
- Reality: 2 apples per $6 → $3/apple → 4 apples cost $12.
- Test choices: A) 6·4/2 = 12 ✓. B) 6·2/4 = 3 ✗. C) 8/6 ✗. D) tiny ✗. **A.**

**Rules for choosing numbers:**
- Small, distinct, and ≠ 0 or 1 (they hide differences between choices).
- Avoid numbers already in the problem.
- Percent problems: start with 100. "Fraction of a fraction": use the denominators' product.
- If two choices both match, keep your numbers... pick new numbers and re-test only the survivors.

**Also use for:** "which expression is equivalent," "which must be true," literal equations ([Lesson 2.10](../02-advanced-math/10-isolating-variables.md)), and inequality-property questions ("if a < b < 0, which is greatest?").

## Technique 2 — Backsolving (plug in the ANSWERS)

When choices are concrete numbers and the setup is convoluted, test the choices instead of building equations.

**Worked example.** "Ana has twice as many stamps as Ben. After giving Ben 12 stamps, she has half as many as Ben. How many did Ana start with?"
A) 16  B) 24  C) 32  D) 48

- Try B) 24: Ana 24, Ben 12. After transfer: Ana 12, Ben 24. Is 12 half of 24? ✓ **B.** Done — no variables.

**Rules:**
- Choices are typically sorted — **start with B or C**: if it's too small, only larger remain (one more test at most).
- Backsolve when the *question's condition is easy to check* but the equation is annoying to build: age problems, "how many at the start," integer-condition problems, radical equations (test the choices in the original — extraneous roots are automatically caught!).

## Technique 3 — Desmos as the third leg

- Answers are numbers + equation given → graph and click ([Lesson 0.6](../00-orientation/06-desmos-mastery.md)).
- Answers are expressions → graph the original and each choice; match the curves.
- Plugging-in verification: once you've picked numbers, Desmos does the arithmetic flawlessly.

## When NOT to use these

- When the direct algebra is one step (backsolving 4 choices is slower than solving 2x = 14).
- "Must be true for ALL x" questions — one plugged number can only *eliminate* choices, not confirm the survivor. Use two different numbers, or algebra.
- SPR questions have no choices to backsolve — plugging in still works for building intuition, but you need the actual answer.

## Practice Set

Solve each WITHOUT direct algebra (plug in / backsolve / Desmos), then verify however you like.

1. If a machine makes m toys in h hours, how many toys does it make in k hours? A) mk/h B) mh/k C) hk/m D) m/(hk)
2. A number n is tripled and then decreased by 4, giving 23. What is n? A) 7 B) 9 C) 11 D) 13
3. If x > 0 and x² + x = 42, what is x? A) 5 B) 6 C) 7 D) 8
4. The sum of three consecutive even integers is 78. What is the largest? A) 24 B) 26 C) 28 D) 30
5. If 0 < a < 1, which is largest? A) a B) a² C) √a D) a³
6. √(x + 20) = x. What is x? A) −4 B) 4 C) 5 D) 20
7. Which is equivalent to (x + 2)² − (x − 2)²? A) 8x B) 4x C) 2x² D) 0
8. A shirt's price is reduced by p% from $40 to $30. What is p? A) 20 B) 25 C) 30 D) 33
9. Karen is 3 times as old as Liam. In 8 years she'll be twice as old. How old is Liam now? A) 6 B) 8 C) 10 D) 12
10. If f(x) = 2x + 3 and f(g(1)) = 13, which could be g(x)? A) x + 4 B) 2x + 3 C) 3x + 1 D) 5x

### Answers

1. **A** — m=4, h=2, k=3: rate 2/hr → 6 toys; A gives 12/2 = 6 ✓.
2. **B** — 3(9) − 4 = 23 ✓.
3. **B** — 36 + 6 = 42 ✓.
4. **C** — 24 + 26 + 28 = 78; largest 28.
5. **C** — try a = 0.25: √a = 0.5 beats 0.25, 0.0625, 0.0156.
6. **C (5)** — test in the original: √(5+20) = 5 ✓. (A: square roots aren't negative; B: √24 ≈ 4.9 ≠ 4; D: √40 ≈ 6.3 ≠ 20. Backsolving catches extraneous roots automatically — the algebra route produces x = −4 as a fake solution.)
7. **A** — x = 3: 25 − 1 = 24 = 8(3) ✓ (others give 12, 18, 0).
8. **B** — drop of $10 from $40 = 25%.
9. **B** — Liam 8, Karen 24; in 8 yrs: 16 and 32 ✓.
10. **A** — need g(1) = 5 since f(5) = 13; A: 1 + 4 = 5 ✓.
