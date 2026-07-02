# Lesson 3.5 — Data Interpretation & Scatterplots

## Concepts

### Reading any data display (tables, bar charts, line graphs, histograms)

1. Read the **title, axis labels, and units** before the question. Most misses here are misreads, not math errors.
2. Note the axis scale — does it start at 0? What does one gridline equal?
3. Histograms show *counts in intervals*: the bar for 10–19 with height 7 means seven values somewhere in [10, 19] — you know the count, not the exact values.

### Scatterplots & association

- **Positive association:** y tends to rise with x. **Negative:** falls. **None:** cloud.
- **Linear vs nonlinear:** does a line or a curve fit the trend? (Exponential-looking = "increasing at an increasing rate.")

### The line of best fit — three question types

1. **Interpret the slope:** "for each additional x-unit, y is predicted to change by m." The word **predicted/expected** belongs in the answer.
2. **Predict:** plug an x into the line's equation, read off ŷ.
3. **Actual vs predicted (the big one):** for a data point above the line, actual > predicted; below the line, actual < predicted.
   - The **difference (residual)** = actual − predicted = vertical distance to the line.
   - "Which point's actual value most exceeds its predicted value?" = point farthest **above** the line.

**Worked example.** Best-fit line ŷ = 12 + 3x. A data point at x = 5 has y = 31. By how much does the actual exceed the predicted?
- Predicted: 12 + 15 = 27. Actual 31. Exceeds by **4**.

### Interpolation vs extrapolation

Predictions inside the data's x-range are reliable; far outside (extrapolation) are not — the SAT phrases correct answers with hedges ("predicted," "approximately," valid "for the domain shown").

## Desmos angle

Given actual data points and asked for the best-fit equation: table + `y₁ ~ mx₁ + b` gives the regression instantly ([Lesson 0.6](../00-orientation/06-desmos-mastery.md)). Also works to check "which equation best fits the data shown" — try the candidates against 2–3 points from the plot.

## Traps

1. **Predicted ≠ actual.** The line gives predictions; the dots are reality. Questions deliberately mix the two.
2. Axis scales that don't start at zero exaggerate differences — read gridline values.
3. Slope interpretation must match units *per one unit* of x (if x is in hundreds, adjust).
4. "How many data points have y > 40" — count **dots**, not gridlines, and only in the stated range.
5. A strong association is not causation ([Lesson 3.7](07-study-design-and-inference.md)).

## Practice Set

1. A best-fit line is ŷ = 12 + 3x. What does the 3 represent?
2. Using ŷ = 12 + 3x, what is the predicted y when x = 5?
3. A data point at (5, 31) lies on the scatterplot with the line from #1–2. What is its residual (actual − predicted)?
4. A scatterplot shows points trending downward left to right. What kind of association is this?
5. A point lies below the best-fit line. Is its actual y-value greater or less than predicted?
6. Best-fit line: ŷ = 80 − 2.5x (x = hours of TV, y = quiz score). Interpret the slope.
7. A histogram has bars: [0–9]: 3, [10–19]: 7, [20–29]: 5. How many data values are below 20?
8. From the histogram in #7, what is the largest possible median? Smallest?
9. The line of best fit for data with x between 2 and 14 is used to predict y at x = 40. What is the concern called?
10. In a table of monthly sales, March = 240 units and April = 300. What is the percent increase?

### Answers

1. **For each 1-unit increase in x, y is predicted to increase by 3.**
2. **27**.
3. **+4** — 31 − 27.
4. **Negative (linear) association**.
5. **Less than predicted**.
6. **Each additional hour of TV predicts a 2.5-point lower quiz score.**
7. **10** — 3 + 7.
8. **15 data values → median is the 8th sorted value, which is in [10–19]: largest possible 19, smallest possible 10.**
9. **Extrapolation** — prediction outside the observed range is unreliable.
10. **25%** — 60/240.
