# Thermodynamics – Lecture 1: Concept of Entropy

> **Course:** Thermodynamics & Phase Diagrams  
> **Lecture:** Concept of Entropy (Introduction)  
> **Topics Covered:** Equilibrium, Spontaneous Processes, Irreversibility, Lost Work, Entropy

---

# 1. Thermodynamic Equilibrium

A system is said to be in **thermodynamic equilibrium** when:

- It is left undisturbed.
- All state variables remain constant.
- No spontaneous change occurs with time.
- The system remains in a state of rest.

For an ideal gas,

\[
PV = RT
\]

Therefore, if **Pressure (P)** and **Temperature (T)** are fixed, **Volume (V)** is also fixed.

Hence, the thermodynamic state of the system is completely defined.

---

# 2. First Law of Thermodynamics

The First Law is

\[
dU=$\delta Q$-$\delta W$
\]

where

- \(dU\) = Change in internal energy
- \(\delta Q\) = Heat supplied to the system
- \(\delta W\) = Work done by the system

---

# 3. Important Special Cases

## (a) Isothermal Reversible Process

For an isothermal process,

\[
dU=0
\]

Therefore,

\[
\delta Q=\delta W
\]

For **1 mole of an ideal gas**,

\[
W_{rev}=Q_{rev}
=
RT\ln\left(\frac{V_2}{V_1}\right)
\]

### Key Points

- Temperature remains constant.
- Internal energy does not change.
- Heat supplied is completely converted into work.

---

## (b) Adiabatic Reversible Process

Since

\[
\delta Q=0
\]

the First Law becomes

\[
dU=-\delta W
\]

### Key Points

- No heat enters or leaves the system.
- Work is done using the internal energy of the system.
- Internal energy decreases when the system performs work.

---

# 4. Spontaneous (Natural) Process

## Definition

A **spontaneous (natural) process** is a process that occurs **without any external assistance**.

The system is initially in a **non-equilibrium state** and naturally moves towards **equilibrium**.

---

## Characteristics

- Occurs naturally.
- Requires no external work.
- Has a preferred direction.
- Always moves toward equilibrium.
- Is irreversible.

---

# 5. Why is a Spontaneous Process Irreversible?

A spontaneous process can occur naturally only in one direction.

The reverse process **cannot occur by itself**.

### Example

If

\[
T_1>T_2
\]

then

Heat flows as

\[
T_1 \rightarrow T_2
\]

However,

\[
T_2 \rightarrow T_1
\]

cannot happen spontaneously.

To transfer heat from cold to hot, an external device (e.g., refrigerator or heat pump) is required.

> **Conclusion:** Every spontaneous process is irreversible.

---

# 6. Examples of Spontaneous Processes

## Example 1: Heat Transfer

If two bodies are placed in thermal contact,

\[
T_1>T_2
\]

then

\[
Q:T_1\rightarrow T_2
\]

Heat always flows from **high temperature** to **low temperature**.

Eventually,

\[
T_1=T_2
\]

and the system reaches equilibrium.

---

## Example 2: Mixing of Ideal Gases

Initially,

```
Gas A | Gas B
```

After removing the partition,

```
Gas A + Gas B
```

The gases mix completely and randomly.

### Important Observations

- Mixing is spontaneous.
- Mixing is random.
- Separation never occurs spontaneously.

Therefore,

> Mixing of ideal gases is an irreversible process.

---

# 7. Spontaneous Process Always Ends at Equilibrium

The sequence is

```
Non-equilibrium
        ↓
Spontaneous Process
        ↓
Equilibrium
```

As the system approaches equilibrium,

- the driving force decreases,
- spontaneity decreases,
- the ability to perform useful work decreases.

---

# 8. Useful Work During a Spontaneous Process

Consider an isolated system.

Since

\[
\delta Q=0
\]

\[
dU=-\delta W
\]

Initially,

the system possesses internal energy capable of producing useful work.

During spontaneous change,

this available work continuously decreases.

Finally,

at equilibrium,

\[
\delta W=0
\]

No more useful work can be extracted.

---

# 9. Lost Work

During a spontaneous process,

a part of the maximum possible work is permanently lost.

This unavailable work is called **Lost Work**.

```
Maximum Work
      │
      ├── Useful Work
      │
      └── Lost Work
```

The lost work cannot be recovered without external intervention.

---

# 10. Entropy

The central idea of this lecture is

> **Lost work is converted into entropy.**

Entropy is therefore related to the energy that is **no longer available for doing useful work**.

---

# 11. Free Expansion of an Ideal Gas

## Experimental Setup

- One chamber contains an ideal gas.
- The second chamber is evacuated.
- The entire system is isolated.
- The partition is removed.

The gas expands freely into the vacuum.

---

## Applying the First Law

Since the system is isolated,

\[
\delta Q=0
\]

Expansion occurs against vacuum,

\[
P_{ext}=0
\]

Therefore,

\[
\delta W=P_{ext}dV=0
\]

Hence,

\[
dU=0
\]

For an ideal gas,

\[
U=f(T)
\]

Therefore,

\[
\Delta T=0
\]

---

### Free Expansion is

- Isothermal
- Spontaneous
- Irreversible
- No heat transfer
- No work done

---

# 12. Compare with Reversible Expansion

Suppose the same expansion occurs reversibly.

Then,

\[
W_{rev}
=
RT\ln\left(\frac{V_f}{V_i}\right)
\]

where

\[
V_f=V_1+V_2
\]

Hence,

\[
W_{rev}
=
RT\ln\left(\frac{V_1+V_2}{V_1}\right)
\]

---

For free expansion,

\[
W=0
\]

Therefore,

the entire reversible work is lost.

\[
W_{lost}
=
RT\ln\left(\frac{V_1+V_2}{V_1}\right)
\]

---

# 13. Definition of Entropy

Entropy is defined using a **reversible process**.

\[
\boxed{
dS=\frac{\delta Q_{rev}}{T}
}
\]

For a finite change,

\[
\boxed{
\Delta S
=
\frac{Q_{rev}}{T}
}
\]

> **Important:** Even if the actual process is irreversible, entropy change is always calculated using an equivalent reversible path.

---

# 14. Entropy Change During Free Expansion

Since

\[
Q_{rev}
=
RT\ln\left(\frac{V_1+V_2}{V_1}\right)
\]

Therefore,

\[
\boxed{
\Delta S_{system}
=
R\ln\left(\frac{V_1+V_2}{V_1}\right)
}
\]

Thus,

although

- \(Q=0\)
- \(W=0\)

the entropy of the system **increases**.

---

# 15. Entropy of the Universe

The total entropy change is

\[
\boxed{
\Delta S_{universe}
=
\Delta S_{system}
+
\Delta S_{surroundings}
}
\]

For an isolated system,

\[
\Delta S_{surroundings}=0
\]

Hence,

\[
\boxed{
\Delta S_{universe}
=
R\ln\left(\frac{V_1+V_2}{V_1}\right)>0
}
\]

---

# 16. Second Law of Thermodynamics

For every spontaneous (irreversible) process,

\[
\boxed{
\Delta S_{universe}>0
}
\]

At equilibrium,

\[
\boxed{
\Delta S_{universe}=0
}
\]

---

# Summary

## Important Definitions

### Thermodynamic Equilibrium

No spontaneous change occurs; all state variables remain constant.

### Spontaneous Process

Occurs naturally without external assistance.

### Irreversible Process

Cannot be reversed without external work.

### Lost Work

The portion of useful work that becomes unavailable during a spontaneous process.

### Entropy

A thermodynamic property that measures the unavailable energy (lost work per unit temperature).

---

# Important Equations

### First Law

\[
dU=\delta Q-\delta W
\]

---

### Isothermal Reversible Expansion

\[
W_{rev}
=
RT\ln\left(\frac{V_2}{V_1}\right)
\]

---

### Adiabatic Reversible Process

\[
dU=-\delta W
\]

---

### Entropy Definition

\[
dS=\frac{\delta Q_{rev}}{T}
\]

---

### Entropy Change of Free Expansion

\[
\Delta S_{system}
=
R\ln\left(\frac{V_1+V_2}{V_1}\right)
\]

---

### Entropy of Universe

\[
\Delta S_{universe}
=
\Delta S_{system}
+
\Delta S_{surroundings}
\]

---

### Second Law

For a spontaneous process,

\[
\boxed{\Delta S_{universe}>0}
\]

---

# Key Takeaways

- Thermodynamic equilibrium means no spontaneous change occurs.
- Spontaneous processes always proceed toward equilibrium.
- Every spontaneous process is irreversible.
- Heat flows naturally from hot to cold.
- Ideal gases mix spontaneously.
- The ability to perform useful work decreases during spontaneous processes.
- The unavailable part of work is called **lost work**.
- Lost work is converted into **entropy**.
- Entropy is defined as

\[
dS=\frac{\delta Q_{rev}}{T}
\]

- During free expansion of an ideal gas:
  - \(Q=0\)
  - \(W=0\)
  - \(dU=0\)
  - Temperature remains constant.
  - Entropy increases.
- For every spontaneous process,

\[
\boxed{\Delta S_{universe}>0}
\]

This is the mathematical statement of the **Second Law of Thermodynamics**.
