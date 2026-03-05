# Solving a System of Linear Equations

This guide explains how to solve a system of two linear equations with two variables using the **Substitution Method**.

---

## 1. Necessary Definitions and Formulas

### System of Linear Equations
A **system of linear equations** is a collection of two or more linear equations involving the same set of variables. The **solution** to the system is the set of values for the variables that makes every equation in the system true simultaneously.

### The Substitution Method
This method involves three primary steps:
1.  Solve one of the equations for one variable (e.g., isolate $x$).
2.  Substitute this expression into the other equation to create an equation with only one variable.
3.  Solve for that variable, then back-substitute to find the second variable.

### General Form
A linear equation in two variables is typically expressed as:

$$
ax + by = c
$$

---

## 2. Problem Solving: Step-by-Step

**Problem:** Find the values of $x$ and $y$ that satisfy both equations:
1. $2x + 3y = 12$
2. $x - y = 1$

### Step 1: Identify the Equations
We start with our system:

$$
\begin{cases} 
2x + 3y = 12 & \text{(Eq. 1)} \\ 
x - y = 1 & \text{(Eq. 2)} 
\end{cases}
$$

### Step 2: Isolate a Variable
It is easiest to isolate $x$ in **Equation 2** by adding $y$ to both sides:

$$
x = y + 1
$$

### Step 3: Substitute into the First Equation
Now, we replace $x$ in **Equation 1** with the expression $(y + 1)$:

$$
2(y + 1) + 3y = 12
$$

### Step 4: Solve for $y$
First, distribute the $2$:

$$
2y + 2 + 3y = 12
$$

Combine the like terms ($2y$ and $3y$):

$$
5y + 2 = 12
$$

Subtract $2$ from both sides:

$$
5y = 10
$$

Divide by $5$:

$$
y = 2
$$

### Step 5: Solve for $x$
Now that we know $y = 2$, plug it back into our simplified version of Equation 2:

$$
x = 2 + 1
$$

$$
x = 3
$$

### Step 6: Verification
To ensure the answer is correct, we check the values $(3, 2)$ in the original equations:
* $2(3) + 3(2) = 6 + 6 = 12$ (Correct)
* $3 - 2 = 1$ (Correct)

---

## 3. Final Solution

The values that satisfy the system are:

$$
x = 3, \quad y = 2
$$



In coordinate form, the solution is represented as the point $(3, 2)$, where the two lines intersect on a graph.
