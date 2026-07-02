# Lesson 4.3 — Right Triangles & Trigonometry

## Concepts

### Pythagorean theorem

a² + b² = c² (c = hypotenuse). **Memorize the triples** — they appear constantly, often scaled:
3-4-5 (6-8-10, 9-12-15, 12-16-20), 5-12-13 (10-24-26), 7-24-25, 8-15-17.
Seeing legs 9 and 12? That's 3-4-5 scaled by 3 → hypotenuse 15, no squaring needed.

### Special right triangles (on the reference sheet)

| Triangle | Sides |
|----------|-------|
| 45°-45°-90° | x : x : x√2 |
| 30°-60°-90° | x : x√3 : 2x (short leg : long leg : hypotenuse) |

The short leg is opposite 30°; the hypotenuse is twice the **short** leg.

### SOHCAHTOA

For acute angle θ in a right triangle:

```
sin θ = opposite/hypotenuse    cos θ = adjacent/hypotenuse    tan θ = opposite/adjacent
```

**Worked example 1.** sin θ = 3/5. Find cos θ and tan θ.
- 3-4-5 triangle: opposite 3, hypotenuse 5, adjacent 4 → cos θ = **4/5**, tan θ = **3/4**.

### The complementary identity (guaranteed SAT material)

The two acute angles of a right triangle are complementary, and:

```
sin θ = cos(90° − θ)
```

"If sin 3a = cos 57° ..." → 3a + 57 = 90 → a = 11. Any sin-equals-cos question is this identity.

### Similar right triangles share trig ratios

If two right triangles are similar, corresponding trig ratios are **equal** — so "triangle DEF is similar to ABC; sin A = 0.6; what is sin D?" → **0.6**, no work needed.

### Radians & the unit circle (light coverage on SAT)

- Convert: multiply degrees by **π/180** (or radians by 180/π). 240° = 4π/3.
- Know the anchor values: sin 30° = 1/2, cos 60° = 1/2, sin 45° = cos 45° = √2/2, tan 45° = 1, sin 60° = cos 30° = √3/2, sin 90° = 1, cos 90° = 0.

## Desmos angle

Desmos evaluates trig (toggle DEGREES mode in settings — a wrong mode is a wrong answer). `sin⁻¹(0.6)` finds angles. For "find the side" problems, arithmetic like `18*tan(35°)` is instant. Check the mode *every time*.

## Traps

1. **Opposite/adjacent are relative to the angle in question.** The side adjacent to A is opposite B. Re-label per angle.
2. The hypotenuse is always opposite the right angle — never a leg, even if drawn long.
3. 30-60-90: hypotenuse = 2 × **short** leg (the one opposite 30°), and √3 goes on the **long leg**.
4. sin θ = cos(90 − θ), not cos(θ) − 90 or similar mangling. Set (angle₁) + (angle₂) = 90.
5. Desmos in radian mode while you work in degrees.

## Practice Set

1. A right triangle has legs 6 and 8. Find the hypotenuse.
2. A right triangle has hypotenuse 26 and one leg 10. Find the other leg.
3. The hypotenuse of a 45-45-90 triangle is 10. Find a leg.
4. The shorter leg of a 30-60-90 triangle is 7. Find the hypotenuse and longer leg.
5. In right triangle ABC (right angle at C), sin A = 5/13. Find cos A and tan A.
6. If sin(2x)° = cos(38)°, and 0 < 2x < 90, find x.
7. A 24-ft ladder leans against a wall making a 60° angle with the ground. How high up the wall does it reach?
8. Convert 240° to radians.
9. Triangle DEF ~ triangle ABC, both right triangles, and tan A = 3/4. If angle D corresponds to angle A, what is tan D?
10. From a point 50 m from a building's base, the angle of elevation to the top is 32°. To the nearest meter, how tall is the building? (Desmos allowed.)

### Answers

1. **10** — 3-4-5 × 2.
2. **24** — 5-12-13 × 2.
3. **5√2** — leg = 10/√2.
4. **Hypotenuse 14, longer leg 7√3**.
5. **cos A = 12/13, tan A = 5/12** — 5-12-13.
6. **x = 26** — 2x + 38 = 90.
7. **12√3 ≈ 20.8 ft** — height = 24 sin 60°.
8. **4π/3**.
9. **3/4** — similarity preserves trig ratios.
10. **≈31 m** — 50 tan 32° ≈ 31.2.
