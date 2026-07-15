# 📘 Statistical Thermodynamics - Part 2
# Microstates and Macrostates

> **Chapter 6 – Statistical Thermodynamics**

This section introduces the two most fundamental concepts in Statistical Thermodynamics:

- **Microstate**
- **Macrostate**

Understanding these concepts is essential because **entropy is directly related to the number of possible microstates corresponding to a macrostate.**

---

# 📑 Table of Contents

1. Why Microstates and Macrostates?
2. What is a Microstate?
3. What is a Macrostate?
4. Difference Between Microstate and Macrostate
5. Example: Four Particles in Two Energy Levels
6. Distribution Function
7. Probability of a Macrostate
8. Important Observations
9. Key Takeaways
10. Exam Questions

---

# 1. Why Do We Need Microstates and Macrostates?

A real thermodynamic system contains

```text
10²² – 10²³ atoms
```

It is impossible to describe the exact condition of every atom.

Instead of recording the position and energy of every particle, we classify the system using **microstates** and **macrostates**.

This dramatically reduces the complexity of the problem.

---

# 2. What is a Microstate?

## Definition

A **microstate** is the complete microscopic description of a system.

It specifies the condition of **every individual particle**.

For each particle, we specify quantities such as:

- Position
- Velocity
- Energy
- Momentum

If even **one particle changes its state**, the system is said to be in a **different microstate**.

---

## Example

Suppose there are four particles

```text
a, b, c, d
```

and only two possible energy levels

```text
ε₁

ε₂
```

One possible arrangement is

```text
ε₁ : a b c d

ε₂ :
```

This is one microstate.

Another arrangement is

```text
ε₁ : a b c

ε₂ : d
```

This is another microstate.

Another one is

```text
ε₁ : a c d

ε₂ : b
```

Again,

a completely different microstate.

Notice that

only one particle moved,

yet the microstate changed.

---

## Important Property

A microstate tells us

> **Exactly where every particle is located (or which energy level every particle occupies).**

---

# 3. What is a Macrostate?

## Definition

A **macrostate** describes the system using only macroscopic information.

Instead of identifying individual particles,

it only specifies

> **How many particles occupy each energy level.**

---

## Example

Suppose

```text
ε₁ : a b c

ε₂ : d
```

Another arrangement

```text
ε₁ : a b d

ε₂ : c
```

Another

```text
ε₁ : a c d

ε₂ : b
```

Another

```text
ε₁ : b c d

ε₂ : a
```

Although these are **four different microstates**,

they all have

```text
3 particles in ε₁

1 particle in ε₂
```

Therefore,

all belong to the **same macrostate**.

---

## Key Idea

A macrostate does **not care**

which particle occupies a level.

It only counts

```text
Number of particles in each energy level.
```

---

# 4. Microstate vs Macrostate

| Microstate | Macrostate |
|------------|------------|
| Complete microscopic description | Macroscopic description |
| Specifies every particle | Specifies only particle counts |
| Very large in number | Comparatively few |
| Changes if one particle moves | Remains same unless particle counts change |
| Used in statistical mechanics | Used in thermodynamics |

---

# 5. Example: Four Particles in Two Energy Levels

Consider

```text
Particles

a
b
c
d
```

Available energy levels

```text
ε₁

ε₂
```

Total number of possible arrangements

```text
2⁴ = 16
```

because

each particle has

```text
2 choices
```

---

## Microstates

Some possible microstates are

```text
1)

ε₁ : a b c d

ε₂ :

------------------

2)

ε₁ : a b c

ε₂ : d

------------------

3)

ε₁ : a b d

ε₂ : c

------------------

4)

ε₁ : a c d

ε₂ : b

------------------

5)

ε₁ : b c d

ε₂ : a

...

Total = 16
```

---

## Macrostates

Now classify them only according to

the number of particles in each level.

| Macrostate | Particles in ε₁ | Particles in ε₂ | Number of Microstates |
|------------|-----------------|-----------------|------------------------|
| I | 4 | 0 | 1 |
| II | 3 | 1 | 4 |
| III | 2 | 2 | 6 |
| IV | 1 | 3 | 4 |
| V | 0 | 4 | 1 |

Notice something remarkable.

Although there are

```text
16 microstates
```

there are only

```text
5 macrostates.
```

---

# 6. Distribution Function

A macrostate is represented by

```text
(n₁, n₂, n₃, ..., nᵣ)
```

where

```text
n₁
```

is the number of particles occupying

```text
ε₁
```

Similarly,

```text
n₂
```

is the number of particles occupying

```text
ε₂
```

and so on.

This list is called the

> **Distribution Function**

---

## Example

```text
(3,1)
```

means

```text
3 particles occupy ε₁

1 particle occupies ε₂
```

It does **not** specify

which particle is where.

---

# 7. Why Does One Macrostate Have Many Microstates?

This is the central idea of Statistical Thermodynamics.

Example

Macrostate

```text
(3,1)
```

can be realized as

```text
abcd

abc|d

abd|c

acd|b

bcd|a
```

Many different microscopic arrangements

produce

the same macroscopic appearance.

Hence

```text
One Macrostate

↓

Many Microstates
```

This idea leads directly to

Boltzmann's entropy equation.

---

# 8. Probability of a Macrostate

Suppose

all microstates are equally likely.

Then

Probability

is simply

```text
(Number of microstates in the macrostate)

/

(Total number of microstates)
```

For our example

| Macrostate | Microstates | Probability |
|------------|------------:|------------:|
| I | 1 | 1/16 |
| II | 4 | 4/16 |
| III | 6 | 6/16 |
| IV | 4 | 4/16 |
| V | 1 | 1/16 |

Clearly,

Macrostate III

has the highest probability.

---

# 9. Important Observation

Notice

```text
Macrostate III

↓

Has the largest number of microstates

↓

Has the highest probability

↓

Most likely to occur
```

This is one of the most important ideas in Statistical Thermodynamics.

Later we shall prove

```text
Maximum Probability

↓

Maximum Number of Microstates

↓

Maximum Entropy

↓

Thermodynamic Equilibrium
```

---

# 10. Visual Representation

```text
Microstates

A
B
C
D
E
F
G
H
I
J
K
L
M
N
O
P

        │
        │
        ▼

Macrostates

I

II

III

IV

V
```

Many microstates combine into a single macrostate.

---

# 11. Key Concepts

✔ Microstate = Exact microscopic arrangement.

✔ Macrostate = Number of particles occupying each energy level.

✔ One macrostate can contain many microstates.

✔ The macrostate with the maximum number of microstates is the most probable.

✔ Statistical Thermodynamics studies macrostates rather than individual particles.

---

# 📌 Important Definitions

## Microstate

The complete microscopic specification of every particle in a thermodynamic system.

---

## Macrostate

The thermodynamic state specified only by the number of particles occupying each energy level.

---

## Distribution Function

A list

```text
(n₁,n₂,n₃,...,nᵣ)
```

that specifies the number of particles in each energy level.

---

# 📝 Exam Questions

### Q1. Define a microstate.

A microstate is the complete microscopic description of a thermodynamic system in which the state of every individual particle is specified.

---

### Q2. Define a macrostate.

A macrostate is a thermodynamic state specified only by the number of particles occupying each energy level.

---

### Q3. Why are there many microstates corresponding to one macrostate?

Because exchanging identical particles between the same occupied energy levels changes the microscopic arrangement without changing the total number of particles in each energy level.

---

### Q4. Which macrostate is the most probable?

The macrostate having the **largest number of corresponding microstates** is the most probable.

---

# ➡️ Next Part

In **Part 3**, we will derive

```text
Ω = N! / (n₁! n₂! ... nᵣ!)
```

using combinatorial analysis and explain the concept of **Multiplicity (Ω)**, which forms the basis of **Boltzmann's Entropy Equation**

```text
S = k ln Ω
```
