# Lesson 1.5 — Linear Word Problems & Models

## Concepts

Every linear model on the SAT is the same sentence wearing different clothes:

```
total = starting amount + (rate) × (number of units)
  y   =       b         +   m   ×      x
```

### The translation drill

| English | Math |
|---------|------|
| "a flat fee of $20 plus $5 per hour" | C = 20 + 5h |
| "starts at 240 gallons and drains 15 per hour" | g = 240 − 15h |
| "worth $24,000, loses $1,500 in value each year" | V = 24000 − 1500t |
| "5 fewer than twice a number" | 2n − 5 |
| "the total of 12-dollar items and 8-dollar items" | 12a + 8c |

Read the problem once for the story, once for the numbers. Identify: What is the starting value? What changes, and by how much per unit?

### The three question types

**Type 1 — Build the model.** "Which equation represents…?" → find b and m in the story; check by plugging in an easy value (does h = 0 give the flat fee?).

**Type 2 — Use the model.** "After how many hours…?" → set up and solve.
Example: V = 24000 − 1500t; when is V = 15000? → 1500t = 9000 → **t = 6 years**.

**Type 3 — Interpret the model.** "What does 15 represent?" → slope = per-unit rate; intercept = starting amount ([Lesson 1.2](02-linear-functions-and-graphs.md)).

### Worked example (full pipeline)

A salesperson earns a $400 weekly base salary plus $50 per sale. How many sales are needed to earn at least $900 in a week?
- Model: E = 400 + 50s. Condition: 400 + 50s ≥ 900.
- 50s ≥ 500 → s ≥ 10. **10 sales.**

### Worked example (two rates meeting)

Gym A costs $30/month with a $60 joining fee. Gym B costs $45/month, no fee. After how many months is total cost equal?
- 60 + 30m = 45m → 60 = 15m → **m = 4.**
- (This is a system in disguise; Desmos: graph both, click the intersection.)

## Desmos angle

Word problems become graph problems: define the model(s), then intersect with the target value. For "after how many hours is the tank empty," graph `y = 240 - 15x` and click the x-intercept. It also catches setup errors — if your line starts at the wrong place or slopes the wrong way, you'll see it.

## Traps

1. **Units.** Rate in *minutes* but question in *hours* (or price in cents vs dollars). Convert before modeling. This trap appears constantly.
2. **Which quantity is x?** "$5 per ride with $2 fee": if the question asks for cost of r rides, it's 5r + 2, not 2r + 5.
3. **"At least" ≠ "more than"** — carry inequality language precisely ([Lesson 1.4](04-linear-inequalities.md)).
4. **Answer the actual question** — after solving t = 6, the question might ask for the *value at* t = 6, or for 2t.
5. Check plausibility: negative time, 4000 tickets in a 200-seat theater → your setup is wrong.

## Practice Set

1. A rental costs a $25 flat fee plus $0.08 per mile. Write the cost C of driving m miles, and find the cost of a 150-mile trip.
2. A machine worth $24,000 depreciates $1,500 per year. After how many years is it worth $15,000?
3. A pool holds 10,800 gallons and fills at 12 gallons per minute from empty. How many **hours** to fill?
4. Gym A: $60 fee + $30/month. Gym B: $45/month. After how many months are total costs equal?
5. A tutor charges $40 for the first hour and $28 for each additional hour. What is the cost of an n-hour session (n ≥ 1)? Find the cost for 5 hours.
6. The temperature was 8°F at 6 a.m. and rose 2.5°F per hour. Write T(h) (h = hours after 6 a.m.). When was it 28°F?
7. Printer ink costs $34 per cartridge. A club has a $500 budget and must spend $92 on paper. What is the maximum number of cartridges it can buy?
8. C(x) = 350 + 12x gives production cost for x units. Revenue is 26x. What is the minimum whole number of units for revenue to exceed cost?
9. A plant is 14 cm tall and grows 3.5 cm/week. Another is 35 cm tall and grows 1.4 cm/week. After how many weeks are they the same height?
10. A phone battery drains from 100% at 1.25% per minute of video. Write the model and find how many minutes until 40%.

### Answers

1. **C = 25 + 0.08m; $37** — 25 + 0.08(150) = 25 + 12.
2. **6** — 24000 − 1500t = 15000 → t = 6.
3. **15 hours** — 10800/12 = 900 minutes = 15 hours. (Unit trap!)
4. **4 months** — 60 + 30m = 45m.
5. **C = 40 + 28(n − 1); $152** — 40 + 28·4. (Trap: the first hour isn't $28.)
6. **T(h) = 8 + 2.5h; h = 8 → 2 p.m.** — 2.5h = 20 → h = 8 hours after 6 a.m.
7. **12** — 34c + 92 ≤ 500 → c ≤ 12 (exactly 12: 34·12 = 408; 408 + 92 = 500 ✓).
8. **26** — 26x > 350 + 12x → 14x > 350 → x > 25, so 26.
9. **10 weeks** — 14 + 3.5w = 35 + 1.4w → 2.1w = 21.
10. **B = 100 − 1.25m; 48 minutes** — 1.25m = 60 → m = 48.
