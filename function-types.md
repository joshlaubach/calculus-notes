# Types of Functions Used in Calculus

## Key Ideas

- Calculus problems involve many function types: polynomial, rational, exponential, logarithmic, trigonometric, and piecewise-defined.
- Understanding the **domain**, **range**, **behavior**, and **graph** of these functions is essential before applying limits, derivatives, or integrals.

---

## Definitions and Core Examples

### 1. Polynomial Functions

A **polynomial function** is of the form:

$$
f(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0
$$

- Domain: all real numbers
- Smooth and continuous
- Examples:
  - $f(x) = x^2 - 3x + 2$
  - $g(x) = 4x^5 - x^3 + 7$

---

### 2. Rational Functions

A **rational function** is a ratio of two polynomials:

$$
f(x) = \frac{P(x)}{Q(x)}
$$

- Domain: all real numbers **except** where $Q(x) = 0$
- May have vertical or horizontal asymptotes
- Example: $f(x) = \frac{x^2 - 1}{x - 3}$

---

### 3. Root (Radical) Functions

A **radical function** involves square roots or other roots:

$$
f(x) = \sqrt[n]{x}, \quad f(x) = \sqrt{x - a}
$$

- Domain depends on the **even/odd** root:
  - Even root: input must be non-negative
  - Odd root: all real numbers allowed
- Example: $f(x) = \sqrt{4 - x^2}$

---

### 4. Exponential Functions

An **exponential function** has a constant base raised to a variable exponent:

$$
f(x) = a^x, \quad a > 0,\ a \ne 1
$$

- Always positive: $f(x) > 0$
- Domain: all real numbers
- Example: $f(x) = 2^x,\quad f(x) = e^x$

---

### 5. Logarithmic Functions

The **inverse** of exponential functions:

$$
f(x) = \log_b x, \quad f(x) = \ln x
$$

- Domain: $x > 0$
- Range: all real numbers
- Useful for solving equations with variables in exponents

---

### 6. Trigonometric Functions

**Periodic functions** based on angle input (in radians):

- $f(x) = \sin x,\quad \cos x,\quad \tan x$
- Periodic, bounded, and often used to model waves
- Domain of sine/cosine: all real numbers  
- Domain of tangent: all real numbers except odd multiples of $\frac{\pi}{2}$

---

### 7. Inverse Trigonometric Functions

Used to reverse trig operations:

- $\sin^{-1} x = \arcsin x$
- $\cos^{-1} x = \arccos x$
- $\tan^{-1} x = \arctan x$

Restricted domains ensure these are functions.

---

### 8. Piecewise-Defined Functions

Defined by **different rules** on different intervals:

$$
f(x) = 
\begin{cases}
x^2 & x < 0 \\\\
x + 1 & x \ge 0
\end{cases}
$$

- Important for modeling abrupt changes (e.g., taxes, cost brackets)
- Always examine **endpoints** for continuity and differentiability

---

### 9. Absolute Value Function

Defined as:

$$
f(x) = |x| =
\begin{cases}
x & x \ge 0 \\\\
-x & x < 0
\end{cases}
$$

- V-shaped graph
- Domain: all real numbers
- Not differentiable at $x = 0$

---

## Tutor's Tip

Many mistakes in calculus come from misidentifying the function type. Before you:

- Take a limit
- Compute a derivative
- Set up an integral

**Know what you're dealing with.** Ask:
- Is this rational? Exponential? Trig?
- Does it have asymptotes or discontinuities?
- What’s the domain?

Recognizing function types leads to better intuition and cleaner problem-solving.
