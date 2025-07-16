# Types of Functions Used in Calculus

## Key Ideas

Calculus problems use many function types — and each behaves differently.

Knowing their:

* **Domain and range**
* **Graph and continuity**
* **Growth, decay, and oscillation**

...is essential before applying limits, derivatives, or integrals.

You’ll most commonly encounter:

- Polynomial
- Rational
- Radical (root)
- Exponential
- Logarithmic
- Trigonometric and inverse trig
- Piecewise-defined
- Absolute value

---

## Polynomial Functions

A **polynomial function** is of the form:

$$
f(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0
$$

- Domain: all real numbers
- Graph: smooth and continuous (no breaks or sharp turns)
- Degree determines shape and end behavior

---

<details>
<summary><strong><u>Example 1:</u></strong> Analyze $f(x) = x^3 - 3x + 2$</summary>

- This is a degree 3 polynomial
- Domain: all real numbers ($\mathbb{R}$)
- Graph is continuous and smooth
- End behavior:
  - As $x \to \infty$, $f(x) \to \infty$
  - As $x \to -\infty$, $f(x) \to -\infty$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Determine the degree and domain of $f(x) = 4x^5 - x^3 + 7$</summary>

- Highest power: $x^5$ ⇒ degree = 5
- Domain: all real numbers
- Graph has smooth turns and no discontinuities

So:

- Degree: $\boxed{5}$
- Domain: $\boxed{(-\infty, \infty)}$

</details>

---

## Rational Functions

A **rational function** is the ratio of two polynomials:

$$
f(x) = \frac{P(x)}{Q(x)}
$$

- Domain: all real numbers **except** where $Q(x) = 0$
- May have **vertical asymptotes** (where denominator = 0)
- May have **horizontal or oblique asymptotes** (based on degrees)

---

<details>
<summary><strong><u>Example 1:</u></strong> Analyze $f(x) = \frac{x^2 - 1}{x - 3}$</summary>

- Domain: exclude where denominator = 0 ⇒ $x \ne 3$
- Vertical asymptote at $x = 3$
- Simplify numerator: $x^2 - 1 = (x - 1)(x + 1)$
- No cancellation with denominator ⇒ $x = 3$ is a true asymptote

So:

- Domain: $\boxed{(-\infty, 3) \cup (3, \infty)}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Determine asymptotes of $f(x) = \frac{x^2 + 2x + 1}{x^2 - 4}$</summary>

- Domain: exclude $x = \pm 2$
- Vertical asymptotes: $x = -2$, $x = 2$
- Degrees of numerator and denominator are equal (both degree 2)

Horizontal asymptote:

- Ratio of leading coefficients: $\frac{1}{1} = \boxed{1}$

</details>

---

## Root (Radical) Functions

A **radical function** involves roots such as:

$$
f(x) = \sqrt[n]{x}, \quad \text{or} \quad f(x) = \sqrt{x - a}
$$

- The **domain depends on the index**:
  - Even root (e.g. square root): input must be $\geq 0$
  - Odd root (e.g. cube root): all real numbers allowed
- Often used in geometry and physics (distance, area, etc.)

---

<details>
<summary><strong><u>Example 1:</u></strong> Find the domain of $f(x) = \sqrt{4 - x^2}$</summary>

The expression inside the square root must be $\geq 0$:

$4 - x^2 \geq 0 \Rightarrow -2 \leq x \leq 2$

So:

- **Domain**: $\boxed{[-2, 2]}$
- **Range**: Since max value is $\sqrt{4} = 2$, and lowest is $0$:
  - $\boxed{[0, 2]}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Find the domain of $f(x) = \sqrt[3]{x - 5}$</summary>

This is a cube root (odd index), so all real values are allowed.

- **Domain**: $\boxed{(-\infty, \infty)}$

</details>

---

## Exponential Functions

An **exponential function** has a constant base raised to a variable exponent:

$$
f(x) = a^x, \quad \text{where } a > 0,\ a \ne 1
$$

- Domain: all real numbers
- Range: $(0, \infty)$
- Graph increases (if $a > 1$) or decreases (if $0 < a < 1$)
- The function $f(x) = e^x$ is especially important in calculus

---

<details>
<summary><strong><u>Example 1:</u></strong> Analyze $f(x) = 2^x$</summary>

- Base $a = 2 > 1$ → increasing function
- Domain: all real numbers $\boxed{(-\infty, \infty)}$
- Range: always positive → $\boxed{(0, \infty)}$
- Horizontal asymptote at $y = 0$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Compare $f(x) = e^x$ and $g(x) = e^{-x}$</summary>

- $f(x) = e^x$ is increasing  
- $g(x) = e^{-x} = \frac{1}{e^x}$ is decreasing
- Both have range $(0, \infty)$ and horizontal asymptote at $y = 0$
- Reflections of each other over the $y$-axis

</details>

---

## Logarithmic Functions

A **logarithmic function** is the inverse of an exponential function:

$$
f(x) = \log_b x, \quad \text{or} \quad f(x) = \ln x
$$

- Domain: $x > 0$
- Range: all real numbers
- Logarithmic functions grow slowly and are undefined for $x \leq 0$
- Useful for solving equations where the variable is in the exponent

---

<details>
<summary><strong><u>Example 1:</u></strong> Analyze $f(x) = \ln x$</summary>

- **Domain**: $x > 0 \Rightarrow \boxed{(0, \infty)}$
- **Range**: all real numbers ⇒ $\boxed{(-\infty, \infty)}$
- Vertical asymptote at $x = 0$
- Passes through $(1, 0)$ since $\ln(1) = 0$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Find the domain of $f(x) = \log_3(x - 2)$</summary>

Inside the log must be positive:

$x - 2 > 0 \Rightarrow x > 2$

- **Domain**: $\boxed{(2, \infty)}$
- **Range**: $\boxed{(-\infty, \infty)}$

</details>

---


## Trigonometric Functions

Trigonometric functions are **periodic** and based on angle input (usually in radians).

Common trig functions:

- $f(x) = \sin x$
- $f(x) = \cos x$
- $f(x) = \tan x$

Key characteristics:

- $\sin x$ and $\cos x$ are **bounded** between $-1$ and $1$
- $\tan x$ has **vertical asymptotes** at odd multiples of $\frac{\pi}{2}$
- All are periodic and appear frequently in oscillation and wave modeling

---

<details>
<summary><strong><u>Example 1:</u></strong> Analyze $f(x) = \cos x$</summary>

- **Domain**: all real numbers ⇒ $\boxed{(-\infty, \infty)}$
- **Range**: $\boxed{[-1, 1]}$
- Period: $2\pi$
- Even function: $\cos(-x) = \cos x$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Analyze $f(x) = \tan x$</summary>

- **Domain**: all real numbers except odd multiples of $\frac{\pi}{2}$
- **Vertical asymptotes** at $x = \frac{\pi}{2} + n\pi$
- **Range**: all real numbers ⇒ $\boxed{(-\infty, \infty)}$
- Period: $\pi$

</details>

--- 

## Inverse Trigonometric Functions

Inverse trig functions “undo” the original trig functions.

Common notation:

- $\sin^{-1} x = \arcsin x$
- $\cos^{-1} x = \arccos x$
- $\tan^{-1} x = \arctan x$

Since trig functions are not one-to-one, their **domains are restricted** to make them invertible.

---

<details>
<summary><strong><u>Example 1:</u></strong> Analyze $f(x) = \arcsin x$</summary>

- **Domain**: $\boxed{[-1, 1]}$
- **Range**: $\boxed{\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]}$
- Passes through $(0, 0)$
- Increasing on its entire domain

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Analyze $f(x) = \arctan x$</summary>

- **Domain**: all real numbers ⇒ $\boxed{(-\infty, \infty)}$
- **Range**: $\boxed{\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)}$
- Horizontal asymptotes at $y = \pm \frac{\pi}{2}$
- Odd function: $\arctan(-x) = -\arctan x$

</details>

--- 

## Hyperbolic Functions

Hyperbolic functions are analogs of trigonometric functions, defined using exponentials.

The basic hyperbolic functions are:

- $\sinh x = \frac{e^x - e^{-x}}{2}$
- $\cosh x = \frac{e^x + e^{-x}}{2}$
- $\tanh x = \frac{\sinh x}{\cosh x}$

Key properties:

- $\cosh x \ge 1$ for all $x$
- $\sinh x$ and $\cosh x$ are smooth and continuous
- $\cosh x$ is even; $\sinh x$ is odd

---

<details>
<summary><strong><u>Example 1:</u></strong> Compute $\sinh(0)$ and $\cosh(0)$</summary>

Use definitions:

- $\sinh(0) = \frac{e^0 - e^{-0}}{2} = \frac{1 - 1}{2} = \boxed{0}$
- $\cosh(0) = \frac{e^0 + e^{-0}}{2} = \frac{1 + 1}{2} = \boxed{1}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Show that $\cosh^2 x - \sinh^2 x = 1$</summary>

Use definitions:

- $\cosh x = \frac{e^x + e^{-x}}{2}$
- $\sinh x = \frac{e^x - e^{-x}}{2}$

Compute:

- $\cosh^2 x = \left(\frac{e^x + e^{-x}}{2}\right)^2 = \frac{e^{2x} + 2 + e^{-2x}}{4}$
- $\sinh^2 x = \left(\frac{e^x - e^{-x}}{2}\right)^2 = \frac{e^{2x} - 2 + e^{-2x}}{4}$

Subtract:

- $\cosh^2 x - \sinh^2 x = \frac{e^{2x} + 2 + e^{-2x} - (e^{2x} - 2 + e^{-2x})}{4} = \frac{4}{4} = \boxed{1}$

</details>


---

## Josh’s Tip

> Don’t just memorize function names — **get to know their behavior**.
>
> Ask yourself:
> 
> - What’s the **domain**?
> - What does the **graph** look like?
> - Are there **asymptotes**, **corners**, or **discontinuities**?
>
> Before you try limits, derivatives, or integrals, know **what kind of function** you're working with.
>
> If you can recognize the type, you’ll know what rules to apply and where the pitfalls are. That’s how you think like a calculus student.
