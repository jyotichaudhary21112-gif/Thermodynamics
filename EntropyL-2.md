# Thermodynamics – Lecture 2: Entropy Generation and Equilibrium

> **Course:** Thermodynamics & Phase Diagrams
> **Lecture:** Entropy Generation During Reversible and Irreversible Processes

## 📑 Table of Contents
1. Objective
2. Review
3. Reversible vs Irreversible Cycle
4. Assumptions
5. First Law
6. Lost Work
7. Reversible Evaporation
8. Irreversible Evaporation
9. Entropy as a State Function
10. Condensation
11. Entropy Generation
12. Equilibrium
13. Formula Sheet
14. Key Takeaways

# 1. Objective
This lecture quantifies entropy using the evaporation–condensation experiment and explains entropy generation due to irreversibility.

# 2. Review
A cyclic evaporation–condensation experiment is considered. One mole of liquid evaporates to vapor and then condenses back to liquid, returning the system to its initial state.

Two cases are analyzed:
- Reversible cycle
- Irreversible cycle

# 3. Reversible vs Irreversible Cycle

## Reversible
- Pressure changes infinitesimally.
- System remains in equilibrium.
- Maximum work during evaporation.
- Minimum work required during condensation.
- No permanent change in surroundings.

```text
Change in external agency = 0
```

## Irreversible
- Finite pressure difference.
- Permanent effect on surroundings.

```text
Change in external agency = 2ΔP·Vm
```

# 4. Assumptions

- Closed system
- Fixed composition
- Only P–V work
- Isothermal process

# 5. First Law

```text
dU = δQ − δW
```

Since the process is isothermal,

```text
dU = 0
```

Therefore,

```text
Q = W
```

Comparing reversible and irreversible processes,

```text
Qrev − Q = Wmax − W
```

The quantity `Wmax − W` is the lost work.

# 6. Lost Work

Lost work is converted into heat stored within the system and appears as entropy generation.

```text
Lost Work → Heat → Entropy Generation
```

# 7. Reversible Evaporation

```text
ΔSsystem = Qrev / T
ΔSreservoir = −Qrev / T
ΔStotal = 0
```

No entropy is generated.

# 8. Irreversible Evaporation

Apparent entropy:

```text
ΔSsystem = Q / T
```

Actual entropy:

```text
ΔSsystem = Q/T + (Wmax − W)/T
```

Since

```text
Wmax − W = Qrev − Q
```

we obtain

```text
ΔSsystem = Qrev / T
```

Thus entropy depends only on state.

# 9. Entropy is a State Function

For the same initial and final states,

```text
ΔSsystem = Qrev / T
```

irrespective of whether the path is reversible or irreversible.

# 10. Condensation

## Reversible

```text
ΔSsystem = −Qrev/T
ΔSreservoir = +Qrev/T
ΔStotal = 0
```

## Irreversible

```text
ΔSsystem = −Q/T + (Q − Qrev)/T
ΔSreservoir = +Q/T
ΔStotal = (Q − Qrev)/T
```

Again,

```text
ΔSirr > 0
```

# 11. Entropy Generation

General relation:

```text
ΔSsystem = Q/T + ΔSirr
```

where

```text
ΔSirr = (Qrev − Q)/T
```

Properties:
- Always positive.
- Measures irreversibility.
- Increases with lost work.

# 12. Equilibrium

At equilibrium,

```text
ΔSirr = 0
```

Thus a reversible process has zero entropy generation.

# Formula Sheet

```text
dU = δQ − δW
Qrev − Q = Wmax − W
Lost Work = Wmax − W
ΔSsystem = Qrev/T
ΔSreservoir = −Qrev/T
ΔStotal(reversible) = 0
ΔSirr = (Qrev − Q)/T
ΔSsystem = Q/T + ΔSirr
ΔSirr > 0
```

# Key Takeaways

- Lost work produces entropy.
- Reversible processes generate no entropy.
- Irreversible processes always generate entropy.
- Entropy is a state function.
- Greater entropy generation means greater irreversibility.
- At equilibrium:

```text
ΔSirr = 0
```
