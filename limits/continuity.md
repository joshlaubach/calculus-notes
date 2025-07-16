# Continuity

## Key Ideas

- A function is **continuous at a point** if:
  1. $f(a)$ is defined  
  2. $\lim_{x \to a} f(x)$ exists  
  3. $\lim_{x \to a} f(x) = f(a)$
- A function is **continuous on an interval** if it is continuous at **every point** in that interval.
- Continuity allows the use of powerful theorems like the **Intermediate Value Theorem** (IVT).

---

## Continuity at a Point

A function is continuous at $x = a$ when the graph has **no holes, jumps, or vertical asymptotes** at that point.

### Example:

Let  
$$
f(x) = 
\begin{cases}
x^2 & x \ne 2 \\\\
5 & x = 2
\end{cases}
$$

Here, $f(2) = 5$ but $\lim_{x \to 2} f(x) = 4$, so  
$\lim_{x \to 2} f(x) \ne f(2)$ — this function is **discontinuous at $x = 2$**.

<img src="../images/removable-discontinuity.png" alt="Removable Discontinuity" width="400"/>

---

## Types of Discontinuity

### 1. Removable Discontinuity  
A hole in the graph — the limit exists, but the function is either undefined or defined incorrectly.

### 2. Jump Discontinuity  
The left- and right-hand limits exist but are not equal.

<img src="../images/jump-discontinuity.jpg" alt="Jump Discontinuity" width="400"/>

### 3. Infinite Discontinuity  
A vertical asymptote — the function grows without bound as it approaches a point.

<img src="../images/infinite-limit.png" alt="Infinite Limit" width="400"/>

---

## Continuity on Intervals

- A function is **continuous on an open interval** $(a, b)$ if it is continuous at every point in that interval.
- A function is **continuous on a closed interval** $[a, b]$ if it is continuous on $(a, b)$ and:
  - $\lim_{x \to a^+} f(x) = f(a)$  
  - $\lim_{x \to b^-} f(x) = f(b)$

---

## Intermediate Value Theorem (IVT)

If $f$ is continuous on $[a, b]$ and $N$ is any number between $f(a)$ and $f(b)$, then **there exists $c \in (a, b)$ such that $f(c) = N$**.

This guarantees that continuous functions hit **every value between two endpoints**.

---

## Example Problems

**Example 1**:  
Is the following function continuous at $x = 3$?

$$
f(x) = 
\begin{cases}
x + 1 & x < 3 \\\\
7 & x = 3 \\\\
x^2 & x > 3
\end{cases}
$$

**Solution**:  
Check left- and right-hand limits:

- $\lim_{x \to 3^-} f(x) = 4$
- $\lim_{x \to 3^+} f(x) = 9$
- So $\lim_{x \to 3} f(x)$ **does not exist**  
⟹ Not continuous at $x = 3$

---

## Practice Problems

1. Determine if each function is continuous at the given point:
   - $f(x) = \frac{x^2 - 1}{x - 1}$ at $x = 1$
   - $f(x) = \sqrt{x - 2}$ at $x = 2$
   - $f(x) = \frac{1}{x - 3}$ at $x = 3$

2. State the type of discontinuity (if any):
   - $f(x) = \frac{|x|}{x}$ at $x = 0$

3. Use IVT to justify whether $f(x) = x^3 - x - 2$ has a root in $[1, 2]$

---

## Tutor’s Tip

Don’t just memorize continuity rules — **practice visualizing the graph**.  
Ask yourself:

- Is there a hole, jump, or asymptote?
- Can I evaluate the function directly?
- Do the left and right sides agree?

When in doubt, **graph it**. Continuity is visual at its core.
