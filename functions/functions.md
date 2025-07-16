# Functions and Their Representations

## Key Ideas

Functions assign **exactly one output** to each input, and they can be represented in several ways:

* **Verbal**: Describes how inputs map to outputs in words
* **Numerical**: Shows values in a table
* **Visual**: Draws the graph of the function
* **Algebraic**: Defines a rule or formula like $f(x) = x^2$

The **domain** is the set of inputs; the **range** is the set of outputs.  
A graph represents a function if it passes the **vertical line test**.

---

## Definitions

A **function** is a rule that assigns to each input exactly one output.

Formally:

> A function is a rule that assigns to each element $x$ in a set $D$ exactly one element $f(x)$ in a set $R$.

- **Domain**: The set of all valid inputs $x$
- **Range**: The set of all outputs $f(x)$ produced from inputs in the domain

---

<details>
<summary><strong><u>Example 1:</u></strong> Is $f(x) = \sqrt{x}$ a function? What is its domain?</summary>

Yes — each input $x \geq 0$ produces one output: $\sqrt{x}$.

- You can’t take the square root of negative numbers (in reals), so:
- **Domain**: $[0, \infty)$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Is $f(x) = \pm \sqrt{x}$ a function?</summary>

No — for a single input $x$, this rule gives two outputs: $+\sqrt{x}$ and $-\sqrt{x}$.

This **violates** the definition of a function.

</details>


---
## Representations of Functions

Functions can be expressed in four major ways:

* **Verbal** — a description in words  
* **Numerical** — a table of values  
* **Visual** — a graph in the $xy$-plane  
* **Algebraic** — a formula like $f(x) = x^2$

These forms describe the same idea: a rule assigning one output to each input.

---

<details>
<summary><strong><u>Example 1:</u></strong> Represent the function $f(x) = x^2$ in four ways</summary>

- **Verbal**: The output is the square of the input.  
- **Numerical**:

  | $x$ | $f(x)$ |
  |-----|--------|
  | $-2$ | $4$   |
  | $-1$ | $1$   |
  | $0$  | $0$   |
  | $1$  | $1$   |
  | $2$  | $4$   |

- **Visual**: Graph is a parabola opening upward.  
- **Algebraic**: $f(x) = x^2$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> A verbal rule says: “The output is 3 more than twice the input.”</summary>

Translate into other forms:

- **Algebraic**: $f(x) = 2x + 3$  
- **Numerical**:

  | $x$ | $f(x)$ |
  |-----|--------|
  | $0$  | $3$   |
  | $1$  | $5$   |
  | $2$  | $7$   |

- **Visual**: Straight line with slope 2, $y$-intercept 3

</details>

---

## Graphs and the Vertical Line Test

A function has **only one output** for each input. On a graph, this means:

> A graph represents a function if **no vertical line** intersects it more than once.

This is known as the **vertical line test**.

---

<details>
<summary><strong><u>Example 1:</u></strong> Does the graph of $f(x) = \sqrt{x}$ pass the vertical line test?</summary>

Yes. Every input $x \geq 0$ has exactly one output $\sqrt{x}$.

No vertical line crosses the curve more than once.

✅ **It is a function.**

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Does the graph of $x^2 + y^2 = 1$ pass the vertical line test?</summary>

No. This is a circle — a vertical line through $x = 0$ intersects the graph at two points: above and below.

❌ **It is not a function.**

</details>

## Domain and Range

To find the **domain**, look for restrictions:

- Cannot divide by zero
- Cannot take even roots of negative numbers (if using real numbers)
- Cannot take $\ln$ or $\log$ of nonpositive numbers

The **range** is the set of possible output values. It can be found by analyzing or graphing the function.

---

<details>
<summary><strong><u>Example 1:</u></strong> Find the domain of $f(x) = \frac{1}{x^2 - 1}$</summary>

Denominator cannot be zero:

- $x^2 - 1 = 0 \Rightarrow x = \pm 1$

So:

- **Domain**: $\boxed{(-\infty, -1) \cup (-1, 1) \cup (1, \infty)}$

</details>

<details>
<summary><strong><u>Example 2:</u></strong> Find the domain and range of $f(x) = \sqrt{x - 2}$</summary>

Inside the square root must be $\geq 0$:

- $x - 2 \geq 0 \Rightarrow x \geq 2$

So:

- **Domain**: $\boxed{[2, \infty)}$
- **Range**: Since square roots produce nonnegative outputs: $\boxed{[0, \infty)}$

</details>

## Josh’s Tip

> Don’t rush past functions — they’re the **foundation** of everything else in calculus.
>
> You’ll be plugging functions into other functions, graphing them, differentiating them, and using them to model real-world behavior.
>
> Before asking “how does it change?” (calculus), make sure you understand:
>
> * What is the **input**?
> * What is the **rule**?
> * What is the **output**?
>
> If you're clear on that, the rest of the course becomes 10× easier.
