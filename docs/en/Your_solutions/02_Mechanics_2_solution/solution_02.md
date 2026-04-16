## Spring-Mass System Analysis

### Given Information
- Mass: *m* = 10 kg
- Position equation: *x(t)* = 0.2 cos(10πt) meters

---

### Step 1: Identify Parameters from x(t)

Comparing *x(t) = A cos(ωt)* with the given equation:

- **Amplitude:** A = 0.2 m
- **Angular frequency:** ω = 10π rad/s

---

### Step 2: Find the Spring Constant *k*

For a spring-mass system, the angular frequency is:

$$\omega = \sqrt{\frac{k}{m}} \implies k = m\omega^2$$

$$k = 10 \times (10\pi)^2 = 10 \times 100\pi^2$$

$$\boxed{k = 1000\pi^2 \approx 9{,}870 \text{ N/m}}$$

---

### Step 3: Find the Total Mechanical Energy *E*

Total mechanical energy in SHM is stored entirely as potential energy at maximum displacement (where velocity = 0):

$$E = \frac{1}{2}kA^2$$

$$E = \frac{1}{2} \times 1000\pi^2 \times (0.2)^2 = \frac{1}{2} \times 1000\pi^2 \times 0.04$$

$$\boxed{E = 20\pi^2 \approx 197.4 \text{ J}}$$

---

### Summary

| Quantity | Value |
|---|---|
| Angular frequency ω | 10π ≈ 31.42 rad/s |
| Spring constant *k* | 1000π² ≈ **9,870 N/m** |
| Total mechanical energy *E* | 20π² ≈ **197.4 J** |

> **Key insight:** In SHM, total energy is constant and equal to ½kA² — it continuously converts between kinetic (max at equilibrium) and potential (max at amplitude peaks), but the sum never changes.
