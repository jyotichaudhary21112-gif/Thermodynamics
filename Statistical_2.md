# 📘 Statistical Thermodynamics - Part 3
# Multiplicity (Ω) and Combinatorial Analysis


In the previous section, we learned that a single macrostate can correspond to many different microstates.

The next question is:

> **How many microstates correspond to a given macrostate?**

The answer is given by a quantity called **Multiplicity (Ω)**.

---

# 📑 Table of Contents

1. Introduction
2. What is Multiplicity?
3. Why Do We Need Multiplicity?
4. Counting Microstates
5. Derivation of the Multiplicity Equation
6. Understanding the Formula
7. Worked Example
8. Probability of a Macrostate
9. Physical Meaning of Ω
10. Key Concepts
11. Formula Sheet
12. Exam Questions

---

# 1. Introduction

In Part 2, we learned that

```text
One Macrostate

↓

Many Microstates
```

However,

different macrostates do **not** contain the same number of microstates.

Some macrostates correspond to only **one** microstate,

whereas others correspond to **thousands, millions, or even trillions** of microstates.

Therefore,

we need a method to determine

> **How many microstates belong to a particular macrostate?**

This number is called the **Multiplicity**.

---

# 2. What is Multiplicity (Ω)?

## Definition

Multiplicity (Ω) is defined as

> **The total number of possible microstates corresponding to a particular macrostate.**

Simply,

```text
Ω = Number of Microstates
```

For example,

Suppose a macrostate has

```text
6 microstates.
```

Then,

```text
Ω = 6
```

If another macrostate has

```text
20 microstates,
```

then

```text
Ω = 20
```

A larger value of Ω means

- More possible microscopic arrangements.
- Higher probability.
- Greater entropy.

---

# 3. Why Do We Need Multiplicity?

Suppose we have

```text
4 particles
```

distributed among

```text
2 energy levels.
```

The macrostate

```text
(2,2)
```

contains

```text
6 microstates.
```

The macrostate

```text
(4,0)
```

contains only

```text
1 microstate.
```

Clearly,

the macrostate

```text
(2,2)
```

is much more likely to occur.

Therefore,

instead of studying every microstate individually,

we simply calculate

```text
Ω
```

for each macrostate.

---

# 4. Counting Microstates

Suppose

there are

```text
N particles
```

distributed among

```text
r energy levels.
```

Let

```text
n₁ particles occupy ε₁

n₂ particles occupy ε₂

n₃ particles occupy ε₃

...

nᵣ particles occupy εᵣ
```

Obviously,

the total number of particles is

```text
N = n₁ + n₂ + n₃ + ... + nᵣ
```

Our objective is

> **Find the total number of different microscopic arrangements corresponding to this distribution.**

---

# 5. Derivation of the Multiplicity Equation

Suppose there are

```text
N particles.
```

If every particle were distinguishable,

the total number of ways of arranging them would be

```text
N!
```

where

```text
N! = N × (N−1) × (N−2) × ... × 2 × 1
```

However,

particles occupying the same energy level are **indistinguishable**.

Exchanging two particles within the same energy level does **not** produce a new microstate.

Therefore,

we divide by

```text
n₁!
```

Similarly,

particles in

```text
ε₂
```

can also be exchanged,

so divide by

```text
n₂!
```

Continuing this argument,

we obtain

```text
Ω = N! / (n₁! n₂! n₃! ... nᵣ!)
```

This is called the

> **Multiplicity Equation**

or

> **Combinatorial Formula**

---

# 6. Understanding the Formula

```text
Ω = N! / (n₁! n₂! ... nᵣ!)
```

where

| Symbol | Meaning |
|---------|---------|
| Ω | Number of microstates |
| N | Total number of particles |
| n₁ | Particles in energy level ε₁ |
| n₂ | Particles in energy level ε₂ |
| nᵣ | Particles in energy level εᵣ |

Remember,

```text
N = n₁ + n₂ + ... + nᵣ
```

---

# 7. Worked Example

Suppose

```text
N = 4
```

and the macrostate is

```text
(2,2)
```

Therefore,

```text
n₁ = 2

n₂ = 2
```

Using

```text
Ω = N! / (n₁! n₂!)
```

Substitute the values

```text
Ω = 4! / (2! 2!)
```

Calculate

```text
4! = 24

2! = 2
```

Hence,

```text
Ω = 24 / (2×2)

Ω = 6
```

Therefore,

there are

```text
6 microstates
```

corresponding to the macrostate

```text
(2,2).
```

---

## Another Example

Macrostate

```text
(3,1)
```

Calculate

```text
Ω = 4! / (3!1!)
```

Since

```text
4! = 24

3! = 6
```

Therefore,

```text
Ω = 24/6

Ω = 4
```

Thus,

there are

```text
4 microstates.
```

---

## Extreme Cases

### Macrostate

```text
(4,0)
```

```text
Ω = 4!/(4!0!)

Ω = 1
```

Only one possible arrangement exists.

---

### Macrostate

```text
(0,4)
```

Similarly,

```text
Ω = 1
```

---

# 8. Probability of a Macrostate

Suppose

all microstates are equally probable.

Then,

```text
Probability

=

(Number of microstates in macrostate)

/

(Total number of microstates)
```

or

```text
P = Ω / Ωtotal
```

Thus,

larger Ω

↓

larger probability.

---

# 9. Physical Meaning of Ω

Multiplicity tells us

> **How many different microscopic arrangements can produce the same macroscopic state.**

A large Ω means

- Many microscopic arrangements.
- Higher probability.
- Greater randomness.
- Greater entropy.

A small Ω means

- Fewer microscopic arrangements.
- Lower probability.
- Lower entropy.

---

# 10. Why Does Nature Prefer Large Ω?

Nature always evolves toward

the **most probable macrostate.**

The most probable macrostate is

the one with

```text
Maximum Ω
```

because

there are simply

more ways

for the system

to exist in that state.

This idea forms the foundation of

Statistical Thermodynamics.

---

# 11. Key Concepts

✔ Ω is called **Multiplicity**.

✔ Ω represents the **number of microstates**.

✔ Large Ω means high probability.

✔ Large Ω means higher entropy.

✔ Nature prefers macrostates having maximum Ω.

✔ The multiplicity equation comes from combinatorial analysis.

---

# 📋 Formula Sheet

Factorial

```text
n! = n × (n−1) × (n−2) × ... × 2 × 1
```

Multiplicity

```text
Ω = N! / (n₁! n₂! ... nᵣ!)
```

Particle Conservation

```text
N = n₁ + n₂ + ... + nᵣ
```

Probability

```text
P = Ω / Ωtotal
```

---

# ⚠️ Common Mistakes

❌ Ω is **not** the number of particles.

✔ Ω is the number of **microstates**.

---

❌ A macrostate contains only one microstate.

✔ A macrostate may contain many microstates.

---

❌ Every macrostate is equally probable.

✔ The probability depends on Ω.

---

# 📝 Exam Questions

### Q1. Define multiplicity.

Multiplicity (Ω) is the total number of microstates corresponding to a given macrostate.

---

### Q2. Derive the multiplicity equation.

Using combinatorial analysis, the number of distinguishable arrangements of N particles is N!. Since particles within the same energy level are indistinguishable, we divide by n₁!, n₂!, ..., nᵣ!, giving

```text
Ω = N! / (n₁! n₂! ... nᵣ!)
```

---

### Q3. Why is the multiplicity equation divided by factorials?

Because exchanging particles within the same energy level does not produce a new microstate, and these repeated arrangements must be removed.

---

### Q4. Why is the macrostate having maximum Ω the most probable?

Because it can be realized by the largest number of microscopic arrangements, making it statistically the most likely state.

---

# ➡️ Next Part

In **Part 4**, we will derive the most famous equation in Statistical Thermodynamics:

```text
S = k ln Ω
```

We'll answer:

- Why is entropy related to Ω?
- Why does Boltzmann use the logarithm?
- Why is the Boltzmann constant (k) needed?
- How does **Maximum Ω ⇒ Maximum Entropy ⇒ Equilibrium**?
