# Applications of Derivatives

## Key Ideas

- Derivatives help us understand the **behavior** of functions: when they increase/decrease, curve up/down, and where they peak or change direction.
- They are also powerful tools in **solving real-world problems** involving motion, rates, and optimization.

---

## Max and Min Values

A function's **local maximum** or **minimum** occurs at critical points, where the derivative is zero or undefined.

<img src="derivative-applications-images/max-min.png" alt="Max Min Values" width="400"/>

### Practice Problems

1. Find the critical points of $f(x) = x^3 - 6x^2 + 9x + 2$.
2. Determine if $x = -1$ is a max, min, or neither for $f(x) = x^3 - 3x$.
3. Find absolute extrema of $f(x) = x^2 - 4x + 3$ on $[0, 5]$.

---

## Rolle's Theorem

If a function is continuous on $[a, b]$, differentiable on $(a, b)$, and $f(a) = f(b)$, then there's some $c \in (a, b)$ such that $f'(c) = 0$.

<img src="derivative-applications-images/rolles-theorem.png" alt="Rolle's Theorem" width="400"/>

### Practice Problems

1. Show that $f(x) = x^2 - 4x + 4$ satisfies Rolle’s Theorem on $[2, 4]$.
2. Find the value of $c$ for $f(x) = \cos x$ on $[0, 2\pi]$.

---

## Mean Value Theorem (MVT)

If $f$ is continuous on $[a, b]$ and differentiable on $(a, b)$, then:

$$
\exists\ c \in (a, b) 	ext{ such that } f'(c) = rac{f(b) - f(a)}{b - a}
$$

<img src="derivative-applications-images/mean-value-theorem.png" alt="Mean Value Theorem" width="400"/>

### Practice Problems

1. Verify MVT for $f(x) = x^2$ on $[1, 3]$.
2. For $f(x) = \sqrt{x}$ on $[1, 4]$, find $c$ that satisfies the theorem.

---

## How Derivatives Affect Graph Shape

- $f'(x) > 0$: function is increasing  
- $f''(x) > 0$: graph is concave up  
- Inflection points occur where $f''(x)$ changes sign

<img src="derivative-applications-images/concavity-inflection.png" alt="Concavity and Inflection" width="400"/>

### Practice Problems

1. Find intervals of concavity for $f(x) = x^4 - 4x^2$.
2. Determine inflection points of $f(x) = x^3 - 3x$.

---

## Indeterminate Forms and L'Hôpital's Rule

Used when direct substitution gives $rac{0}{0}$ or $rac{\infty}{\infty}$.

$$
\lim_{x 	o a} rac{f(x)}{g(x)} = \lim_{x 	o a} rac{f'(x)}{g'(x)} 	ext{ (if limit exists) }
$$

<img src="derivative-applications-images/lhopital.png" alt="L'Hopital's Rule" width="400"/>

### Practice Problems

1. Evaluate: $\lim_{x 	o 0} rac{\sin x - x}{x^3}$
2. Evaluate: $\lim_{x 	o \infty} rac{\ln x}{x}$

---

## Curve Sketching

Use critical points, inflection points, and asymptotic behavior to sketch a function’s graph.

<img src="derivative-applications-images/curve-sketching.png" alt="Curve Sketching" width="400"/>

### Practice Problems

1. Sketch the curve of $f(x) = x^3 - 3x^2 + 2$ using derivatives.
2. Identify all intervals where the function is increasing and concave down.

---

## Related Rates

Differentiate with respect to $t$ and relate multiple changing quantities.

<img src="derivative-applications-images/related-rates.png" alt="Related Rates" width="400"/>

### Practice Problems

1. A ladder slides down a wall. If the bottom moves at 2 ft/sec, how fast is the top falling?
2. A balloon rises at 5 ft/sec while a person walks away. Find the rate the distance between them changes.

---

## Optimization

Use critical points and endpoints to solve maximum or minimum value problems.

<img src="derivative-applications-images/optimization.png" alt="Optimization" width="400"/>

### Practice Problems

1. Find dimensions of a rectangle with perimeter 40 m that encloses max area.
2. Maximize the volume of a box made by cutting squares from corners of a 10×10 square.

---

## Newton’s Method

Numerical technique to approximate roots.

$$
x_{n+1} = x_n - rac{f(x_n)}{f'(x_n)}
$$

<img src="derivative-applications-images/newtons-method.png" alt="Newton's Method" width="400"/>

### Practice Problems

1. Use Newton’s Method with $x_0 = 1.5$ to approximate a root of $f(x) = x^3 - x - 1$.
2. Approximate $\sqrt{5}$ using Newton’s Method on $f(x) = x^2 - 5$.

---

## Tutor’s Tip

Many calculus problems are **disguised applications of derivatives**. Know which technique fits:
- **Critical points** → optimization or sketching  
- **Rates changing** → related rates  
- **Limits with 0/0** → L’Hôpital  
- **"Approximate a root"** → Newton’s

Every tool here begins with a derivative. Know how and why to use each.
