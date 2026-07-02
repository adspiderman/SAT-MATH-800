# Lesson 3.6 — Probability & Two-Way Tables

## Concepts

### The one formula

```
P(event) = favorable outcomes / total outcomes
```

Bag with 4 red, 6 blue: P(red) = 4/10 = **2/5**. P(not red) = 1 − 2/5 = 3/5 (complement).

### Two-way tables — where nearly all SAT probability lives

|  | Juniors | Seniors | Total |
|--|---------|---------|-------|
| **Yes** | 24 | 36 | 60 |
| **No** | 16 | 24 | 40 |
| **Total** | 40 | 60 | 100 |

- P(randomly chosen student said Yes) = 60/100.
- P(Yes **given** the student is a junior) = 24/**40** ← the "given" shrinks the denominator to the junior column.
- P(junior **given** Yes) = 24/**60** ← different question, different denominator!

**The rule: "given that X" (or "of the students who X") makes X's total the denominator.** Find the denominator first, then the cell.

### Filling in missing table cells

Rows and columns must sum to their totals — treat it as a puzzle; fill what's forced. Many "hard" table problems are just this.

### Expected counts from probabilities

"20% of 350 trees are oaks; a tree is picked at random" → 70 oaks. Conversely, expected number = probability × group size — used for "based on the survey, approximately how many of the 3000 townspeople..." questions: sample proportion × population.

## Desmos angle

Plain fraction arithmetic — the calculator prevents simplification slips (`24/40`). For SPR answers, a fraction like `3/5` is enterable directly; no need to convert to decimals.

## Traps

1. **The denominator.** Every conditional-probability miss is a denominator miss. Circle the "given/of those who" group; its total is your denominator.
2. P(A given B) ≠ P(B given A) — 24/40 vs 24/60 above.
3. "Or" includes both (union): P(junior or Yes) = (40 + 60 − 24)/100 = 76/100 — subtract the overlap once.
4. Read whether the question asks for a probability (fraction) or a **count** (number of people).
5. Answers as fractions of the RIGHT whole: "what fraction of Yes-voters were seniors" = 36/60, not 36/100.

## Practice Set

Use this table for 3–7:

|  | Club A | Club B | Total |
|--|--------|--------|-------|
| **10th grade** | 18 | 12 | 30 |
| **11th grade** | 14 | 26 | 40 |
| **Total** | 32 | 38 | 70 |

1. A bag has 4 red and 6 blue marbles. What is P(red)?
2. A die is rolled once. What is P(rolling at least a 5)?
3. A student is chosen at random from the 70. What is P(Club A)?
4. What is P(Club A, given the student is in 10th grade)?
5. What is P(10th grade, given the student is in Club A)?
6. What is P(11th grade or Club B)? *(union)*
7. If a school of 2100 students mirrors this table, how many would be in Club B?
8. A spinner has 8 equal sectors: 3 red, 2 blue, 3 green. What is P(not green)?
9. P(rain) = 0.3 each day. Of 20 days, about how many rainy days are expected?
10. Two-way fill-in: a table of 120 people has 70 adults; 45 adults and 25 children said Yes. How many people said No?

### Answers

1. **2/5**.
2. **1/3** — {5, 6} out of 6.
3. **32/70 = 16/35**.
4. **18/30 = 3/5** — denominator: 10th-grade row.
5. **18/32 = 9/16** — denominator: Club A column.
6. **52/70 = 26/35** — 40 + 38 − 26 = 52.
7. **1140** — (38/70) × 2100.
8. **5/8**.
9. **6**.
10. **50** — total Yes = 70, so No = 120 − 70.
