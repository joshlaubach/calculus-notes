# Limits

## Key Ideas

- A **limit** describes what a function approaches as the input gets arbitrarily close to a value.
- Limits allow us to define instantaneous rate of change and address undefined expressions.
- Mastery of limits is essential for understanding derivatives, integrals, and continuity.

---

## The Tangent and Velocity Problems

### The Tangent Problem

To find the slope of a curve at a point (i.e., a tangent), we approximate it using secant lines.

Let \( f(x) = x^2 \), and consider the slope of the secant line from \( x = 1 \) to \( x = 1 + h \):

$$
\frac{f(1 + h) - f(1)}{h}
$$

The **tangent line slope** is the limit as \( h \to 0 \):

$$
\lim_{h \to 0} \frac{(1 + h)^2 - 1}{h} = \lim_{h \to 0} \frac{2h + h^2}{h} = \lim_{h \to 0} (2 + h) = 2
$$

<img src="../images/tangent-secant-lines.png" alt="Tangent and Secant Lines" width="400"/>

---

### The Velocity Problem

If \( s(t) \) is the position of an object, the **average velocity** over time interval \( [t, t + h] \) is:

$$
\frac{s(t + h) - s(t)}{h}
$$

The **instantaneous velocity** at time \( t \) is:

$$
\lim_{h \to 0} \frac{s(t + h) - s(t)}{h}
$$

<img src="../images/instantaneous-velocity.png" alt="Instantaneous Velocity" width="400"/>

---

## The Limit of a Function

The notation:

$$
\lim_{x \to a} f(x) = L
$$

means the value of \( f(x) \) can be made arbitrarily close to \( L \) by taking \( x \) sufficiently close (but not equal) to \( a \).

If the left-hand and right-hand limits exist and are equal, the two-sided limit exists.

---

## Calculating Limits Using the Limit Laws

Use these rules to simplify and compute limits algebraically:

- **Sum Rule**:  
  \( \lim_{x \to a} [f(x) + g(x)] = \lim f(x) + \lim g(x) \)

- **Product Rule**:  
  \( \lim_{x \to a} [f(x) \cdot g(x)] = \lim f(x) \cdot \lim g(x) \)

- **Quotient Rule** (if \( \lim g(x) \ne 0 \)):  
  \( \lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim f(x)}{\lim g(x)} \)

- **Power Rule**:  
  \( \lim_{x \to a} [f(x)]^n = [\lim f(x)]^n \)

- **Root Rule**:  
  \( \lim_{x \to a} \sqrt[n]{f(x)} = \sqrt[n]{\lim f(x)} \)

---

## The Precise Definition of a Limit

We say:

$$
\lim_{x \to a} f(x) = L
$$

if for every \( \varepsilon > 0 \), there exists \( \delta > 0 \) such that whenever:

$$
0 < |x - a| < \delta \quad \Rightarrow \quad |f(x) - L| < \varepsilon
$$

This formalizes the idea of “getting arbitrarily close.”

### Example:  
Prove that \( \lim_{x \to 2} (3x + 1) = 7 \)

Let \( \varepsilon > 0 \). Choose \( \delta = \frac{\varepsilon}{3} \). Then:

$$
|x - 2| < \delta \Rightarrow |3x + 1 - 7| = 3|x - 2| < 3\delta = \varepsilon
$$

<img src="../images/epsilon-delta-graph.png" alt="Epsilon-Delta Graph" width="400"/>

---

## Tutor’s Tip

Don’t treat limits like plug-and-chug problems. Instead:

- Sketch the graph to see what the function is approaching.
- Analyze both sides to see if the limit exists.
- Use algebra to simplify before applying limit laws.
- For rigorous work, understand how $\varepsilon$ and $\delta$ connect inputs and outputs.

Limits build the bridge between algebra and calculus. Take your time here — it pays off later.
