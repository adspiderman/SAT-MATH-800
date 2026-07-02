# Lesson 3.4 — Statistics: Center & Spread

## Concepts

### The measures

| Measure | Definition | Sensitive to outliers? |
|---------|-----------|------------------------|
| Mean | sum ÷ count | **Yes** — dragged toward outliers |
| Median | middle value when sorted (average the middle two if even count) | Barely |
| Mode | most frequent value | No |
| Range | max − min | **Yes** (extremely) |
| Standard deviation | typical distance from the mean | Yes |

### Mean problems = total problems

Work with **totals**, not averages.

**Worked example 1.** The mean of five numbers is 12; four of them are 10, 11, 13, 14. Fifth?
- Total = 60. Known four sum to 48. Fifth = **12**.

**Worked example 2 (weighted mean).** 20 students average 80; another 30 average 90. Combined mean?
- Total = 20(80) + 30(90) = 1600 + 2700 = 4300; ÷50 = **86**. (NOT 85 — you can't average averages with different group sizes.)

### Median — position, not value

Sort first. For n values, the median is at position (n+1)/2. In a frequency table, count up cumulative frequencies to find which value holds the middle position.

### Standard deviation — conceptual only

The SAT never asks you to compute SD by hand. It asks you to **compare**: data clustered near the mean → small SD; spread out → large SD. {5,5,6,6} has smaller SD than {1,4,8,11}.

### Transformations of data (know these effects)

| Change to every value | Mean | Median | Range/SD |
|----------------------|------|--------|----------|
| add constant c | +c | +c | **unchanged** |
| multiply by k | ×k | ×k | ×k |
| remove a high outlier | decreases | ~same | decreases |

**Outlier asymmetry:** a right (high) outlier makes mean > median; a left outlier makes mean < median. "Which is greater, mean or median?" on a skewed histogram = this fact.

## Desmos angle

`mean([10,11,13,14,x])` won't solve for x — but graph `y = mean([10,11,13,14,x])` with x-axis as the unknown, intersect with `y = 12`. Faster: totals by hand. For raw lists: `mean(A)`, `median(A)`, `stdev(A)` after `A = [...]`. For frequency tables, expand the list (`[3,3,3,5,5]`) or compute the weighted total manually.

## Traps

1. **Sort before taking the median.** Data in tables is often unsorted.
2. **Weighted means:** never average two group means unless groups are equal-sized.
3. Frequency tables: the data set {value 2 with frequency 3} is {2,2,2} — n is the **sum of frequencies**, not the number of rows.
4. Adding a value *equal to the mean* leaves the mean unchanged (and typically lowers the SD).
5. "Average speed" over a round trip = total distance / total time — NOT the mean of the two speeds.

## Practice Set

1. Find the mean, median, mode, and range of: 4, 7, 7, 9, 12, 15.
2. The mean of five numbers is 12; four are 10, 11, 13, 14. Find the fifth.
3. 20 students average 80 on a test; 30 other students average 90. Combined average?
4. A data set has mean 50. Every value is increased by 5. What are the new mean and standard deviation behavior?
5. Which has the larger standard deviation: A = {48, 49, 50, 51, 52} or B = {30, 40, 50, 60, 70}?
6. In the sorted set 3, 8, x, 14, 20 with median 11, what is x?
7. A frequency table: value 1 (freq 4), value 2 (freq 3), value 5 (freq 3). What is the median?
8. A data set of 9 salaries has one huge outlier at the top. Which is larger, the mean or the median?
9. Tom drives 60 mph for 2 hours, then 30 mph for 1 hour. What is his average speed?
10. The mean of 7 numbers is 15. After adding an 8th number the mean is 16. What number was added?

### Answers

1. **Mean 9, median 8, mode 7, range 11** — sum 54/6 = 9; middle two are 7 and 9.
2. **12**.
3. **86** — 4300/50.
4. **New mean 55; SD unchanged** — shifting doesn't change spread.
5. **B** — same mean (50), far more spread.
6. **x = 11** — the middle of five sorted values is the third.
7. **2** — 10 data points; positions 5 and 6 are both 2 (cumulative: 1's fill 1–4, 2's fill 5–7).
8. **Mean** — pulled up by the outlier.
9. **50 mph** — total 150 miles / 3 hours. (Not 45!)
10. **23** — totals: 8(16) − 7(15) = 128 − 105.
