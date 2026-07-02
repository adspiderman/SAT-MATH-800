# Lesson 3.3 — Units & Conversion

## Concepts

### Dimensional analysis — multiply by "1" until the units are right

Write conversions as fractions and cancel units like factors:

**Worked example 1.** 90 km/h in m/s:
```
90 km/h × (1000 m / 1 km) × (1 h / 3600 s) = 90000/3600 = 25 m/s
```
The units *tell you* whether the conversion factor goes on top or bottom: put the unit you want to kill on the opposite side.

**Worked example 2.** A car uses 5 gallons per 150 miles. How many gallons for 720 miles?
- 5/150 gal per mile × 720 = **24 gallons**.

**Worked example 3 (two-step).** A machine fills 40 bottles per minute. How many bottles in 3 hours?
- 40 × 60 × 3 = **7200**.

### The conversions the SAT gives you vs expects

The problem will **state** unusual conversions (liters↔gallons, etc.). You're expected to know: 60 s/min, 60 min/h, 24 h/day, 12 in/ft, 3 ft/yd, 100 cm/m, 1000 m/km, 1000 g/kg, 16 oz/lb (given when needed), cents/dollars.

### Density-style rates

Any "A per B" quantity works the same: price per pound, people per square mile, dollars per euro. Currency exchange problems are pure dimensional analysis with the rate the problem supplies.

## Desmos angle

Chain arithmetic in one line: `90 * 1000 / 3600`. Type the whole conversion at once rather than in rounds — intermediate rounding is a classic source of wrong SPR answers. **Never round until the final step.**

## Traps

1. **Squared/cubed units:** 1 ft = 12 in, but 1 ft² = **144 in²** and 1 ft³ = 1728 in³. The SAT loves area/volume conversions.
2. **Per-minute vs per-hour** mismatch between the given rate and the asked-for time. Underline both units before computing.
3. **Intermediate rounding.** Keep exact values until the end.
4. Flipping the rate: at 25 m/s, "seconds per meter" is 1/25 — check which direction is asked.

## Practice Set

1. Convert 90 km/h to m/s.
2. A car uses 5 gallons of fuel per 150 miles. How many gallons for a 720-mile trip?
3. A machine fills 40 bottles per minute. How many bottles in 3 hours?
4. A recipe needs 2.5 kg of flour. Flour is sold in 500 g bags. How many bags?
5. Carpet costs $4 per square foot. How much for a 4 yd × 5 yd room? (1 yd = 3 ft)
6. Light travels ~186,000 miles per second. About how many miles in one minute?
7. 1 gallon ≈ 3.8 liters. A 19-liter tank holds how many gallons?
8. A runner's pace is 8 minutes per mile. How many miles in 2 hours at this pace?
9. A rectangle is 2 ft by 18 in. What is its area in square inches?
10. Exchange rate: 1 dollar = 0.92 euros. How many dollars is 460 euros? (Nearest dollar.)

### Answers

1. **25 m/s**.
2. **24 gallons**.
3. **7200**.
4. **5 bags** — 2500 g / 500 g.
5. **$720** — 12 ft × 15 ft = 180 ft² × $4.
6. **11,160,000 miles** — ×60.
7. **5 gallons** — 19/3.8.
8. **15 miles** — 120 min ÷ 8 min/mile.
9. **432 in²** — 24 in × 18 in. (Convert *before* multiplying.)
10. **$500** — 460/0.92.
