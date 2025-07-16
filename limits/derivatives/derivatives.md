# Derivatives

## Key Ideas

- A **derivative** measures how a function changes — it gives the **instantaneous rate of change** or **slope of the tangent line**.
- Derivatives are defined as a **limit** and follow specific rules for different types of functions.
- Derivatives can be applied directly or through rules like the **product rule**, **chain rule**, or **implicit differentiation**.

---

## Definitions

**Derivative at a point:**

$$
f'(a)=\lim_{h \to 0}\frac{f(a+h)-f(a)}{h}
$$

**Derivative as a function:**

$$
f'(x)=\lim_{h \to 0}\frac{f(x+h)-f(x)}{h}
$$

---

## Derivative as a Function

The derivative defines a **new function** that tells us the slope of the original function at any input $x$.

If $f(x)=x^2$, then:

$$
f'(x)=\lim_{h \to 0}\frac{(x+h)^2-x^2}{h}=\lim_{h \to 0}\frac{2xh+h^2}{h}=2x
$$

---

## Derivatives of Polynomials and Exponential Functions

### Polynomial Rule:  
For any constant $n$:

$$
\frac{d}{dx}(x^n)=nx^{n-1}
$$

### Exponential Functions:

- $\frac{d}{dx}(e^x)=e^x$
- $\frac{d}{dx}(a^x)=a^x\ln a$ for $a>0$

---

## Product and Quotient Rules

### Product Rule:

$$
\frac{d}{dx}[f(x)g(x)]=f'(x)g(x)+f(x)g'(x)
$$

### Quotient Rule:

$$
\frac{d}{dx}\left[\frac{f(x)}{g(x)}\right]=\frac{f'(x)g(x)-f(x)g'(x)}{[g(x)]^2}
$$

---

## Derivatives of Trigonometric Functions

- $\frac{d}{dx}(\sin x)=\cos x$
- $\frac{d}{dx}(\cos x)=-\sin x$
- $\frac{d}{dx}(\tan x)=\sec^2 x$
- $\frac{d}{dx}(\cot x)=-\csc^2 x$
- $\frac{d}{dx}(\sec x)=\sec x \tan x$
- $\frac{d}{dx}(\csc x)=-\csc x \cot x$


---

## Derivatives of Exponential and Logarithmic Functions

$$
\frac{d}{dx}(\ln x)=\frac{1}{x},\quad x>0\\
\frac{d}{dx}(\log_b x)=\frac{1}{x\ln b},\quad x>0,\ b>0,\ b\ne1
$$

Recall:

$$
\frac{d}{dx}(e^x)=e^x,\quad \frac{d}{dx}(a^x)=a^x\ln a
$$

---

## Derivatives of Hyperbolic Functions


- $\frac{d}{dx}(\sinh x)=\cosh x$
- $\frac{d}{dx}(\cosh x)=\sinh x$
- $\frac{d}{dx}(\tanh x)=\text{sech}^2 x$
- $\frac{d}{dx}(\text{csch } x)=-\text{csch } x\coth x$
- $\frac{d}{dx}(\text{sech } x)=-\text{sech } x\tanh x$
- $\frac{d}{dx}(\coth x)=-\text{csch}^2 x$


---

## Chain Rule

If $y=f(g(x))$, then:

$$
\frac{dy}{dx}=f'(g(x))\cdot g'(x)
$$

### Example:

Let $f(x)=\sin(x^2)$

Then:

$$
f'(x)=\cos(x^2)\cdot 2x
$$

---

## Implicit Differentiation

Used when $y$ is defined implicitly by an equation involving both $x$ and $y$.

### Example:

Given:

$$
x^2+y^2=25
$$

Differentiate both sides:

$$
2x+2y\frac{dy}{dx}=0
$$

Solve for $\frac{dy}{dx}$:

$$
\frac{dy}{dx}=\frac{-x}{y}
$$

---

## Linear Approximations and Differentials

The **linear approximation** (or linearization) of a function near a point uses the tangent line:

$$
L(x)=f(a)+f'(a)(x-a)
$$

This gives a quick estimate of $f(x)$ near $x=a$.

### Example:

Let $f(x)=\sqrt{x},\ a=4$. Then $f(4)=2$, and $f'(x)=\frac{1}{2\sqrt{x}}$, so $f'(4)=\frac{1}{4}$.

Linear approximation:

$$
L(x)=2+\frac{1}{4}(x-4)
$$

Estimate $\sqrt{4.1}\approx L(4.1)=2+\frac{1}{4}(0.1)=2.025$

---

**Differentials** describe approximate changes in a function.

If $y=f(x)$, then the differential $dy$ is:

$$
dy=f'(x)\,dx
$$

This estimates the change in $y$ given a small change $dx$ in $x$.

---

## Tutor’s Tip

Use the derivative not just to compute slopes — but to **predict**, **approximate**, and **analyze**.  
When something is hard to compute exactly, the derivative gives you a **nearby linear model** that’s fast and intuitive.
