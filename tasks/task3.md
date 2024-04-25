## Cancellation laws

Let $(G, *)$ be a group and let $x, y, z \in G$.

### Problem 1

**Theorem.** If $x * y = x * z$, then $y = z$.

*Proof.* Let's multiply both sides by $x^{-1}$ on the left side:

$$x^{-1} * x * y = x^{-1} * x * z$$

Thus

$$
\begin{align*}
    (x^{-1} * x) * y &= (x^{-1} * x) * z \\
    e * y &= e * z \\
    y &= z
\end{align*}
$$

This proves the claim. $\square$

### Problem 2

**Theorem.** If $y * x = z * x$, then $y = z$.

*Proof.* Let's multiply both sides by $x^{-1}$ on the right side:

$$y * x * x^{-1} = z * x * x^{-1}$$

Thus

$$
\begin{align*}
    y * (x * x^{-1}) &= z * (x * x^{-1}) \\
    y * e &= z * e \\
    y &= z
\end{align*}
$$

This proves the claim. $\square$
