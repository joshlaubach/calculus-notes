# Derivatives

## Key Ideas

Derivatives describe how a function changes. They measure the **instantaneous rate of change** or **slope of the tangent line** at a point.

Applications of derivatives include:

* Finding **slopes** and **rates of change**
* Constructing **linear approximations**
* Analyzing **motion**, **growth**, and **optimization**
* Interpreting behavior in **graphs**, **models**, and **data**

---

### Limit Definition of the Derivative

The derivative of a function is defined using a **limit**.

**At a point** $x = a$:

$$
f'(a) = \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}
$$

**As a function**:

$$
f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}
$$

---

<details>
<summary><strong><u>Example 1:</u></strong> Use the definition to find $f'(2)$ for $f(x) = 3x + 1$</summary>

Use:

$f'(2) = \lim_{h \to 0} \frac{f(2 + h) - f(2)}{h}$

Compute:

- $f(2 + h) = 3(2 + h) + 1 = 6 + 3h + 1 = 7 + 3h$
- $f(2) = 3(2) + 1 = 7$

So:

$f'(2) = \lim_{h \to 0} \frac{7 + 3h - 7}{h}
= \lim_{h \to 0} \frac{3h}{h}
= \lim_{h \to 0} 3 = \boxed{3}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Find $f'(x)$ from the definition for $f(x) = x^2$</summary>

Use:

$f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}$

Compute:

- $f(x + h) = (x + h)^2 = x^2 + 2xh + h^2$
- $f(x + h) - f(x) = x^2 + 2xh + h^2 - x^2 = 2xh + h^2$

Then:

$f'(x) = \lim_{h \to 0} \frac{2xh + h^2}{h}
= \lim_{h \to 0} (2x + h) = \boxed{2x}$

</details>

## Derivatives of Polynomials and Exponential Functions

Derivatives of basic functions can be found using simple rules.

### Power Rule

If $n$ is a constant:

$$
\frac{d}{dx}(x^n) = nx^{n - 1}
$$

### Exponential Rules

- $\frac{d}{dx}(e^x) = e^x$
- $\frac{d}{dx}(a^x) = a^x \ln a$ for $a > 0$

---

<details>
<summary><strong><u>Example 1:</u></strong> Differentiate $f(x) = 4x^5 - 3x^2 + 7$</summary>

Use the power rule:

- $f'(x) = 4 \cdot 5x^{4} - 3 \cdot 2x + 0$
- So: $f'(x) = 20x^4 - 6x$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Differentiate $f(x) = 5e^x + 2 \cdot 3^x$</summary>

Apply exponential rules:

- $f'(x) = 5e^x + 2 \cdot 3^x \ln 3$
- So: $f'(x) = \boxed{5e^x + 2 \cdot 3^x \ln 3}$

</details>

## Basic Derivative Properties

Before applying advanced rules, remember these **linearity properties**:

### Sum and Difference Rule

$$
\frac{d}{dx}[f(x) \pm g(x)] = f'(x) \pm g'(x)
$$

### Constant Multiple Rule

$$
\frac{d}{dx}[c \cdot f(x)] = c \cdot f'(x)
$$

These let you differentiate term-by-term.

---

<details>
<summary><strong><u>Example 1:</u></strong> Differentiate $f(x) = 7x^3 - 4x + 5$</summary>

Apply the rules term-by-term:

- $\frac{d}{dx}(7x^3) = 21x^2$
- $\frac{d}{dx}(-4x) = -4$
- $\frac{d}{dx}(5) = 0$

So:

$f'(x) = \boxed{21x^2 - 4}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Differentiate $f(x) = \frac{1}{2}x^4 + 3x^2 - 9$</summary>

Differentiate each term:

- $\frac{d}{dx}(\frac{1}{2}x^4) = 2x^3$
- $\frac{d}{dx}(3x^2) = 6x$
- $\frac{d}{dx}(-9) = 0$

So:

$f'(x) = \boxed{2x^3 + 6x}$

</details>

## Product and Quotient Rules

When differentiating products or quotients of functions, we use special rules.

### Product Rule

If $f(x)$ and $g(x)$ are both differentiable:

$$
\frac{d}{dx}[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)
$$

### Quotient Rule

If $f(x)$ and $g(x)$ are both differentiable and $g(x) \ne 0$:

$$
\frac{d}{dx} \left[ \frac{f(x)}{g(x)} \right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}
$$

---

<details>
<summary><strong><u>Example 1:</u></strong> Differentiate $f(x) = x^2 \sin x$</summary>

Let $u = x^2$, $v = \sin x$

Then:

- $u' = 2x$, $v' = \cos x$
- Apply the product rule:

$f'(x) = u'v + uv' = 2x \sin x + x^2 \cos x$

So:

$f'(x) = \boxed{2x \sin x + x^2 \cos x}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Differentiate $f(x) = \frac{x^2 + 1}{x^3}$</summary>

Let $u = x^2 + 1$, $v = x^3$

Then:

- $u' = 2x$, $v' = 3x^2$
- Use the quotient rule:

$f'(x) = \frac{(2x)(x^3) - (x^2 + 1)(3x^2)}{x^6}$

Simplify numerator:

- $2x^4 - 3x^4 - 3x^2 = -x^4 - 3x^2$

So:

$f'(x) = \boxed{\frac{-x^4 - 3x^2}{x^6}}$

</details>

## Derivatives of Trigonometric Functions

The six basic trigonometric functions have the following derivatives:

- $\frac{d}{dx}(\sin x) = \cos x$
- $\frac{d}{dx}(\cos x) = -\sin x$
- $\frac{d}{dx}(\tan x) = \sec^2 x$
- $\frac{d}{dx}(\cot x) = -\csc^2 x$
- $\frac{d}{dx}(\sec x) = \sec x \tan x$
- $\frac{d}{dx}(\csc x) = -\csc x \cot x$

---

<details>
<summary><strong><u>Example 1:</u></strong> Differentiate $f(x) = \sin x + \cos x$</summary>

Use the basic rules:

- $\frac{d}{dx}(\sin x) = \cos x$
- $\frac{d}{dx}(\cos x) = -\sin x$

So:

$f'(x) = \boxed{\cos x - \sin x}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Differentiate $f(x) = \tan x \cdot \sec x$</summary>

Let $u = \tan x$, $v = \sec x$

Then:

- $u' = \sec^2 x$, $v' = \sec x \tan x$

Use the product rule:

$f'(x) = u'v + uv' = \sec^2 x \cdot \sec x + \tan x \cdot \sec x \tan x$

Simplify:

$f'(x) = \boxed{\sec^3 x + \sec x \tan^2 x}$

</details>

## Derivatives of Exponential and Logarithmic Functions

These functions have consistent and powerful derivative rules.

### Exponential Rules

- $\frac{d}{dx}(e^x) = e^x$
- $\frac{d}{dx}(a^x) = a^x \ln a$, for $a > 0$

### Logarithmic Rules

- $\frac{d}{dx}(\ln x) = \frac{1}{x}, \quad x > 0$
- $\frac{d}{dx}(\log_b x) = \frac{1}{x \ln b}, \quad x > 0,\ b > 0,\ b \ne 1$

---

<details>
<summary><strong><u>Example 1:</u></strong> Differentiate $f(x) = \ln(x^2 + 1)$</summary>

Use the chain rule and $\frac{d}{dx}(\ln u) = \frac{1}{u} \cdot \frac{du}{dx}$:

Let $u = x^2 + 1$:

- $\frac{d}{dx}(x^2 + 1) = 2x$
- So: $f'(x) = \frac{1}{x^2 + 1} \cdot 2x = \boxed{\frac{2x}{x^2 + 1}}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Differentiate $f(x) = 4^x + \log_2 x$</summary>

Use the exponential and logarithmic rules:

- $\frac{d}{dx}(4^x) = 4^x \ln 4$
- $\frac{d}{dx}(\log_2 x) = \frac{1}{x \ln 2}$

So:

$f'(x) = \boxed{4^x \ln 4 + \frac{1}{x \ln 2}}$

</details>

## Derivatives of Hyperbolic Functions

Hyperbolic functions behave similarly to trig functions but have their own set of derivatives.

- $\frac{d}{dx}(\sinh x) = \cosh x$
- $\frac{d}{dx}(\cosh x) = \sinh x$
- $\frac{d}{dx}(\tanh x) = \text{sech}^2 x$
- $\frac{d}{dx}(\coth x) = -\text{csch}^2 x$
- $\frac{d}{dx}(\text{sech } x) = -\text{sech } x \tanh x$
- $\frac{d}{dx}(\text{csch } x) = -\text{csch } x \coth x$

---

<details>
<summary><strong><u>Example 1:</u></strong> Differentiate $f(x) = \sinh x + \cosh x$</summary>

Use the rules:

- $\frac{d}{dx}(\sinh x) = \cosh x$
- $\frac{d}{dx}(\cosh x) = \sinh x$

So:

$f'(x) = \boxed{\cosh x + \sinh x}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Differentiate $f(x) = \tanh x \cdot \text{sech} x$</summary>

Let $u = \tanh x$, $v = \text{sech} x$

Then:

- $u' = \text{sech}^2 x$, $v' = -\text{sech} x \tanh x$

Use the product rule:

$f'(x) = u'v + uv' = \text{sech}^2 x \cdot \text{sech} x + \tanh x \cdot (-\text{sech} x \tanh x)$

Simplify:

$f'(x) = \boxed{\text{sech}^3 x - \text{sech} x \tanh^2 x}$

</details>

## Chain Rule

The **Chain Rule** is used when one function is nested inside another.

If $y = f(g(x))$, then:

$$
\frac{dy}{dx} = f'(g(x)) \cdot g'(x)
$$

This allows us to differentiate compositions like $\sin(x^2)$ or $\ln(3x + 1)$.

---

<details>
<summary><strong><u>Example 1:</u></strong> Differentiate $f(x) = \sin(x^2)$</summary>

Let $u = x^2$, so $f(x) = \sin(u)$

Then:

- $f'(x) = \cos(u) \cdot \frac{du}{dx} = \cos(x^2) \cdot 2x$
- So: $f'(x) = \boxed{2x \cos(x^2)}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Differentiate $f(x) = \ln(3x + 1)$</summary>

Let $u = 3x + 1$, so $f(x) = \ln(u)$

Then:

- $\frac{d}{dx}(\ln u) = \frac{1}{u} \cdot \frac{du}{dx}$
- $\frac{du}{dx} = 3$

So:

$f'(x) = \frac{1}{3x + 1} \cdot 3 = \boxed{\frac{3}{3x + 1}}$

</details>

## Implicit Differentiation

When a function is defined **implicitly** (rather than as $y = f(x)$), we use implicit differentiation:

- Differentiate both sides with respect to $x$
- Use the Chain Rule on all $y$ terms
- Solve for $\frac{dy}{dx}$

---

<details>
<summary><strong><u>Example 1:</u></strong> Differentiate $x^2 + y^2 = 25$</summary>

Differentiate both sides:

- $\frac{d}{dx}(x^2) + \frac{d}{dx}(y^2) = \frac{d}{dx}(25)$
- $2x + 2y \frac{dy}{dx} = 0$

Solve for $\frac{dy}{dx}$:

$\frac{dy}{dx} = \boxed{-\frac{x}{y}}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Find $\frac{dy}{dx}$ if $x^3 + y^3 = 6xy$</summary>

Differentiate both sides:

- $\frac{d}{dx}(x^3) + \frac{d}{dx}(y^3) = \frac{d}{dx}(6xy)$
- $3x^2 + 3y^2 \frac{dy}{dx} = 6y + 6x \frac{dy}{dx}$

Move all terms involving $\frac{dy}{dx}$ to one side:

$3y^2 \frac{dy}{dx} - 6x \frac{dy}{dx} = 6y - 3x^2$

Factor:

$\frac{dy}{dx}(3y^2 - 6x) = 6y - 3x^2$

Solve:

$\frac{dy}{dx} = \boxed{\frac{6y - 3x^2}{3y^2 - 6x}}$

</details>

## Linear Approximations and Differentials

A **linear approximation** uses the tangent line to estimate function values near a known point.

### Linear Approximation Formula

$$
L(x) = f(a) + f'(a)(x - a)
$$

This estimates $f(x)$ near $x = a$.

---

The **differential** $dy$ approximates the change in $y$ for a small change $dx$:

$$
dy = f'(x)\,dx
$$

---

<details>
<summary><strong><u>Example 1:</u></strong> Approximate $\sqrt{4.1}$ using linearization at $a = 4$</summary>

Let $f(x) = \sqrt{x}$, so $f'(x) = \frac{1}{2\sqrt{x}}$

- $f(4) = 2$, $f'(4) = \frac{1}{4}$

Then:

$L(x) = f(4) + f'(4)(x - 4) = 2 + \frac{1}{4}(x - 4)$

Estimate:

$L(4.1) = 2 + \frac{1}{4}(0.1) = \boxed{2.025}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Use differentials to estimate change in $y$ for $f(x) = \ln x$ at $x = 1$, $dx = 0.05$</summary>

We use: $dy = f'(x)\,dx$

- $f'(x) = \frac{1}{x}$
- $f'(1) = 1$

Then:

$dy = f'(1) \cdot dx = 1 \cdot 0.05 = \boxed{0.05}$

So $\ln(1.05) \approx \ln(1) + dy = 0 + 0.05 = \boxed{0.05}$

</details>

## Josh’s Tip

> The derivative is the foundation of everything in calculus.
>
> Every rule — whether it’s product, chain, or implicit — is just a different way to ask:
>
> * How is this function changing right now?
> * What’s the slope of the tangent line?
> * Can I model this with a simple linear approximation?
>
> Think of the derivative as a **toolbox**:
>
> * Use the **limit definition** when asked to build from scratch.
> * Use **rules** (power, product, chain) to move fast and clean.
> * Use **linearization** and **differentials** to estimate and approximate.
>
> Mastering derivatives isn’t about memorizing — it’s about recognizing **what kind of change** you're working with.
