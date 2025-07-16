# Applications of Derivatives

## Key Ideas

Derivatives help us understand how a function behaves: where it increases or decreases, peaks, curves, and flattens out.

Applications of derivatives include:

* Identifying maxima and minima
* Understanding curve shapes
* Solving motion and rate problems
* Optimizing values
* Approximating roots of equations

---

## Max and Min Values

A function can have **local extrema** (maxima or minima) at **critical points**, where the derivative is zero or undefined.

We find **absolute extrema** by checking critical points and endpoints.

<img src="../images/max-min.png" alt="Max Min Values" width="400"/>

<details>
<summary><strong><u>Example:</u></strong> Find and classify critical points</summary>

Let \$f(x) = x^3 - 6x^2 + 9x + 2\$

\$f'(x) = 3x^2 - 12x + 9 = 3(x - 1)(x - 3)\$

Critical points at \$x = 1\$, \$x = 3\$. Use the First Derivative Test to classify them.

</details>

---

## Rolle’s Theorem

If a function \$f\$ is continuous on $\[a, b]\$, differentiable on \$(a, b)\$, and \$f(a) = f(b)\$, then there exists \$c \in (a, b)\$ such that \$f'(c) = 0\$.

<img src="../images/rolles-theorem.png" alt="Rolle's Theorem" width="400"/>

<details>
<summary><strong><u>Example:</u></strong> Verify Rolle’s Theorem</summary>

Let \$f(x) = x(x - 4)\$ on $\[0, 4]\$.

\$f(0) = f(4) = 0\$

\$f'(x) = 2x - 4 \Rightarrow f'(c) = 0 \Rightarrow c = 2\$

Since \$c \in (0, 4)\$, Rolle’s Theorem holds.

</details>

---

## Mean Value Theorem (MVT)

If \$f\$ is continuous on $\[a, b]\$ and differentiable on \$(a, b)\$, then:

$$
\exists c \in (a, b) \text{ such that } f'(c) = \frac{f(b) - f(a)}{b - a}
$$

<img src="../images/mean-value-theorem.png" alt="Mean Value Theorem" width="400"/>

<details>
<summary><strong><u>Example:</u></strong> Apply MVT to $f(x) = x^2$ on $[1, 3]$</summary>

Average rate:

\$\frac{f(3) - f(1)}{3 - 1} = \frac{9 - 1}{2} = 4\$

Since \$f'(x) = 2x\$, set \$2x = 4 \Rightarrow x = 2 \in (1, 3)\$.

</details>

<details>
<summary><strong><u>Practice:</u></strong></summary>

1. Verify MVT for \$f(x) = \sqrt{x}\$ on $\[1, 4]\$
2. Find \$c\$ for \$f(x) = \ln x\$ on $\[1, e]\$

</details>

---

## Graph Behavior: Increasing, Concavity, Inflection

* If \$f'(x) > 0\$, the function is increasing
* If \$f'(x) < 0\$, the function is decreasing
* If \$f''(x) > 0\$, the graph is concave up
* If \$f''(x) < 0\$, the graph is concave down
* Inflection point: \$f''(x) = 0\$ and concavity changes sign

<img src="../images/concavity-inflection.png" alt="Concavity and Inflection" width="400"/>

<details>
<summary><strong><u>Example:</u></strong> Concavity of $f(x) = x^4 - 4x^2$</summary>

\$f''(x) = 12x^2 - 8 = 0 \Rightarrow x = \pm \sqrt{\frac{2}{3}}\$

Test intervals:

* Concave up on \$(-\infty, -\sqrt{2/3}) \cup (\sqrt{2/3}, \infty)\$
* Concave down on \$(-\sqrt{2/3}, \sqrt{2/3})\$

</details>

<details>
<summary><strong><u>Example:</u></strong> Inflection point of $f(x) = x^3 - 3x$</summary>

\$f''(x) = 6x = 0 \Rightarrow x = 0\$

Sign changes → inflection point at \$(0, 0)\$.

</details>

---

## L'Hôpital’s Rule

If substitution gives \$\frac{0}{0}\$ or \$\frac{\infty}{\infty}\$, apply:

$$
\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}
$$

<details>
<summary><strong><u>Example:</u></strong> $\lim_{x \to 0} \frac{\sin x - x}{x^3}$</summary>

Apply L'Hôpital’s Rule three times:

\$\lim\_{x \to 0} \frac{-\cos x}{6} = \boxed{-\frac{1}{6}}\$

</details>

<details>
<summary><strong><u>Example:</u></strong> $\lim_{x \to \infty} \frac{\ln x}{x}$</summary>

\$\lim\_{x \to \infty} \frac{1/x}{1} = 0 \Rightarrow \boxed{0}\$

</details>

---

## Curve Sketching

<img src="../images/curve-sketching.png" alt="Curve Sketching" width="400"/>

Steps:

* Use \$f'(x)\$ for intervals of increase/decrease
* Use \$f''(x)\$ for concavity and inflection points
* Identify extrema and asymptotes

<details>
<summary><strong><u>Example:</u></strong> $f(x) = x^3 - 3x^2 + 2$</summary>

\$f'(x) = 3x^2 - 6x = 3x(x - 2)\$

Critical points: \$x = 0\$, \$x = 2\$

\$f''(x) = 6x - 6 \Rightarrow x = 1 \text{ (inflection)}\$

* Increasing on \$(-\infty, 0)\$ and \$(2, \infty)\$
* Decreasing on \$(0, 2)\$
* Inflection point at \$(1, 0)\$
* Local max at \$(0, 2)\$
* Local min at \$(2, -2)\$

</details>

<details>
<summary><strong><u>Example:</u></strong> $f(x) = \frac{1}{x}$</summary>

* \$f'(x) = -\frac{1}{x^2}\$ ⇒ always decreasing
* \$f''(x) = \frac{2}{x^3}\$ ⇒ concave down on \$(-\infty, 0)\$, concave up on \$(0, \infty)\$
* No inflection point (undefined at \$x = 0\$)

</details>

---

## Related Rates

Use implicit differentiation with respect to time \$t\$.

<img src="../images/related-rates.png" alt="Related Rates" width="400"/>

<details>
<summary><strong><u>Example:</u></strong> Balloon and walker</summary>

Given: \$x = 24\$, \$y = 32\$, \$z = 40\$, \$dx/dt = 3\$, \$dy/dt = 5\$

\$z \frac{dz}{dt} = x \frac{dx}{dt} + y \frac{dy}{dt}\$

\$40 \frac{dz}{dt} = 24(3) + 32(5) = 232 \Rightarrow \frac{dz}{dt} = \boxed{5.8\text{ ft/s}}\$

</details>

<details>
<summary><strong><u>Example:</u></strong> Sliding ladder</summary>

Given: \$x = 6\$, \$dx/dt = 2\$, \$y = 8\$

\$x \frac{dx}{dt} + y \frac{dy}{dt} = 0 \Rightarrow 6(2) + 8 \frac{dy}{dt} = 0\$

\$\frac{dy}{dt} = \boxed{-1.5\text{ ft/s}}\$

</details>

---

## Optimization

<img src="../images/optimization.png" alt="Optimization" width="400"/>

Steps:

1. Set up target quantity
2. Use constraints
3. Write in one variable
4. Take derivative
5. Find critical points
6. Confirm max/min

<details>
<summary><strong><u>Example:</u></strong> Max area with perimeter 40</summary>

\$x + 2y = 40 \Rightarrow y = 20 - x\$

\$A = xy = x(20 - x) = 20x - x^2\$

\$A'(x) = 20 - 2x = 0 \Rightarrow x = 10, y = 10\$

> Max area when square: \$10 \times 10\$

</details>

<details>
<summary><strong><u>Example:</u></strong> Max volume from square</summary>

\$V(x) = x(10 - 2x)^2 = 100x - 40x^2 + 4x^3\$

\$V'(x) = 100 - 80x + 12x^2 = 0 \Rightarrow x = \frac{5}{3}\$

\$V = \frac{5}{3} \cdot \left(\frac{20}{3}\right)^2 = \boxed{\frac{2000}{27}}\$

</details>

---

## Newton’s Method

Use iteration:

$$
x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}
$$

<img src="../images/newtons-method.png" alt="Newton's Method" width="400"/>

<details>
<summary><strong><u>Example:</u></strong> Root of $f(x) = x^3 - x - 1$</summary>

* \$x\_0 = 1.5\$: \$x\_1 \approx 1.348\$, \$x\_2 \approx 1.325\$

> Approximate root: \$\boxed{1.325}\$

</details>

<details>
<summary><strong><u>Example:</u></strong> Estimate $\sqrt{5}$</summary>

\$f(x) = x^2 - 5\$, \$f'(x) = 2x\$, \$x\_0 = 2\$

* \$x\_1 = 2.25\$, \$x\_2 \approx 2.236\$
* \$\boxed{\sqrt{5} \approx 2.236}\$

</details>

---

## Josh’s Tip

> Every application above is just a different use of the **derivative**.
>
> Ask yourself:
>
> * Is this a **slope** or **rate**?
> * Do I need to **maximize or minimize**?
> * Am I tracking **change over time**?
