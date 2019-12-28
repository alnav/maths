# Limits

## Right-hand and left-hand limits

Suppose $f(x)$ gets really close to **R** for values of $x$ that get really close to (but are not equal to) $a$ from the right. Then we say R is the **right-hand limit** of the function $f(x)$ as $x$ approaches $a$ from the right.

- $f(x) \to R$ as $x \to a^+$ 

or 

- $\lim_{x \to a^+} f(x) = R$

If $f(x)$ gets really close to **L** for values of $x$ that get really close to (but are not equal to) $a$ from the left we say L is the **left-hand limit** of the function $f(x)$ as $x$ approaches $a$ from the left.

- $f(x) \to R$ as $x \to a^-$ 

or 

- $\lim_{x \to a^-} f(x) = L$

## Possible limit behaviours

- Right-hand and left-hand limits may **both exist and be equal**
- Right-hand and left-hand limits may **both exist, but may fail to be equal**
- Right- and/or left-hand limit could **fail to exist due to blowing up to $\plusmn\infin$**
- Right-hand/or left-hand limit could **fail to exist because it oscillates** between many values e.g. sin function

## Definition

If a function $f(x)$ approaches some value $L$ as $x$ approaches $a$ from both the right and the left, then **the limit** of $f(x)$ exists and equal $L$.

If:
- $\lim_{x \to a^+} f(x) = \lim_{x \to a^-} f(x) = L$

Then:
- $\lim_{x \to a} f(x) = L$

Remember that $x$ is approachin $a$ but does not equal $a$.

# Limit laws

Suppose:
- $\lim_{x \to a} f(x) = L$
- $\lim_{x \to a} g(x) = M$

Then:

- Limit law for addition: $\lim_{x \to a} [f(x) + g(x)] = L + M$
- Limit law for subtraction: $\lim_{x \to a} [f(x) - g(x)] = L - M$
- Limit law for subtraction: $\lim_{x \to a} [f(x) \cdot g(x)] = L \cdot M$
- Limit law for division: if $M \not ={0}$, then $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{L}{M}$

# Continuity

$f$ is **continuous** at $x = a$ if $\lim_{x \to a} f(x) = f(a)$
- if a function is continuous, it makes it much more easier to calculate limit
- functions can also be right- or left-continuous
- to be continuous, needs to be right- AND left-continuous
- if left-hand limit $\lim_{x \to a^-} f(x)$ and right-hand limit $\lim_{x \to a^+} f(x)$ both exist at a point $x = a$, but they are not equal, we say that $f$ has a **jump discontinuity** at $x = a$
- if the overall limit $\lim_{x \to a} f(x)$ exists (left- and right-hand limit agree) but the overall limit does not equal $f(a)$, then we say that $f$ has a **removable discontinuity** at $f=a$
- **Overall continuitiy** there are no discontinuities in a function
  - Limit of a continuous function will always equal to value of function at that point
  - functions that are continuous anywhere are:
    - constant
    - $g(x) = x$
    - $|x|$
    - $\sin x$
    - $\tan x$ is not continuous (when $\cos x = 0$)
- If $f(x)$ and $g(x)$ are continuous at a point, $h(x) = f(x) \cdot g(x)$ is also continuous at that point
-  any polynomial is continuous
-  composition of function:
   -  $h(x) = f(g(x))$
   -  for $x$ approaching $a$: $g(x) = g(a)$, therefore $f(g(x)) = f(g(a))$
   -  $h$ is continuous at $a$
   -  e.g. $\sin(x^2 + 1)$ is continuous everywhere

## Continuous functions

- all polynomials
- $\sqrt[3]x$
- $|x|$
- $cos x$ and $sin x$
- exponential functions $a^x$ with base $a > 0$

Following functions are continuous of right-continuous at the specified values of $x$
- $\sqrt{x}$, for $x > 0$
- $tan x$, at all $x$ where it is defined
- logarithmic functions $\log_a x$, with base $a > 0$, for $x > 0$

## Intermediate value theorem

If $f(x)$ is continuous on the interval $[a,b]$and $M$ lies between the values of $f(a)$ and $f(b)$, then there is at least one point $c$ between $a$ and $b$ such that $f(c) = M$

A function $f$ is *continuous on a closed interval $[a,b]$* if it is right-continuous at $a$, left-continuous at $b$ and continuous at all points between $a$ and $b$

