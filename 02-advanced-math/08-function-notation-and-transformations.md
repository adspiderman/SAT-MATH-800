# Lesson 2.8 — Function Notation & Transformations

## Concepts

### Notation — f(x) is a machine

f(x) = 3x² − 2x means: whatever is in the parentheses replaces **every** x.
- f(−2) = 3(−2)² − 2(−2) = 12 + 4 = **16**
- f(a + 1) = 3(a + 1)² − 2(a + 1) — substitute the whole thing, with parentheses.
- "f(2) = 5" is the point (2, 5) on the graph. Tables, graphs, and equations are the same information.

### Composition — inside first

f(x) = 2x + 1, g(x) = x²:
- f(g(3)) = f(9) = **19**
- g(f(3)) = g(7) = **49** ← order matters!

With tables: to find f(g(2)), read g(2) from g's table, then look that value up in f's table.

### Domain quick rules

- Division: denominator ≠ 0. f(x) = (x + 2)/(x − 3) is undefined at **x = 3**.
- Even roots: inside ≥ 0. f(x) = √(x − 4) needs **x ≥ 4**.

### Transformations (memorize this table)

Starting from y = f(x):

| New function | Effect |
|--------------|--------|
| f(x) + k | shift **up** k (down if k < 0) |
| f(x + k) | shift **left** k (right if k < 0) ← counterintuitive! |
| −f(x) | reflect over **x-axis** |
| f(−x) | reflect over **y-axis** |
| a·f(x), a > 1 | vertical stretch |

**Outside the parentheses → vertical, acts as expected. Inside → horizontal, acts opposite.**

- y = x² shifted left 3, down 1 → y = (x + 3)² − 1.
- g(x) = f(x − 2): every point moves right 2. If f has a zero at x = 5, g has one at x = 7.
- If f(2) = 5, then y = f(x) − 3 contains (2, **2**), and y = f(x − 1) contains (**3**, 5).

### Reading graphs (heavily tested)

From a graph: f(3) = the y-value at x = 3. "For what x is f(x) = 0?" = x-intercepts. "f(x) > 0" = where the graph is above the x-axis. "Maximum of f" = highest point's y-value.

## Desmos angle

Define `f(x) = ...` then type `f(-2)`, `f(g(3))` (after defining g) — instant. For transformation questions, plot `f(x)` and the transformed version and watch what moved. On graph-reading questions Desmos can't see the printed graph, but you can often re-type the pictured function from its description.

## Traps

1. **f(x + 2) shifts LEFT**, not right. The single most-missed transformation fact.
2. f(g(x)) ≠ g(f(x)) in general. Work inside-out.
3. f(x)² vs f(x²) vs [f(x)]² — read the notation precisely.
4. f(a + b) ≠ f(a) + f(b). A function is not distributive.
5. On tables: f(g(2)) — a common error is reading f(2) instead of evaluating g first.

## Practice Set

1. f(x) = 3x² − 2x. Find f(−2).
2. f(x) = 2x + 1, g(x) = x². Find f(g(3)) and g(f(3)).
3. The graph of g is the graph of f shifted up 3. Write g in terms of f.
4. If f has a zero at x = 5, where does g(x) = f(x − 2) have a zero?
5. Write the equation of y = x² shifted left 3 and down 1.
6. If f(2) = 5, which point lies on y = f(x) − 3?
7. The graph of y = −f(x) is the reflection of f over which axis?
8. Tables: g(2) = 6, g(6) = 1, f(6) = 4, f(2) = 9. Find f(g(2)).
9. What is the domain of f(x) = √(x − 4)?
10. For what value of x is f(x) = (x + 2)/(x − 3) undefined?

### Answers

1. **16**.
2. **19 and 49**.
3. **g(x) = f(x) + 3**.
4. **x = 7** — right shift by 2.
5. **y = (x + 3)² − 1**.
6. **(2, 2)**.
7. **The x-axis**.
8. **4** — g(2) = 6, then f(6) = 4.
9. **x ≥ 4**.
10. **x = 3**.
