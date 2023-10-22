- Determine length of vector function
- Let
$$\textbf{r(t)} = \langle f(t), g(t), h(t) \rangle \text{ for } a \leq t \leq b$$
- Length $L$ is
$$L = \int^b_a |\textbf{r'}(t)| dt$$

> Find $L$ of the circular helix with vector equation
> $$\textbf{r}(t) = \langle 2 \cos t, 2 \sin t, 4t\rangle$$
> from $(2, 0, 0)$ to $(0, 2, 2\pi)$
---
> Find **limits of integration** ($t$)
> $4t = 0 \to t=0$
> $4t = 2\pi \to t = \pi/2$
> $0 \leq t \leq \pi/22$
---
> $$\textbf{r'}(t) = \langle -2\sin t, 2\cos t, 4\rangle$$
> $$|\textbf{r'}(t)| = \sqrt{4\sin^2 t + 4\cos^2 t + 16}$$
> Use identity
> $$=\sqrt{4(\sin^2 t + \cos^2 t) + 16}$$
> $$=2\sqrt{5}$$
> Definite integral of $2\sqrt(5)$
> **Final answer:** $\sqrt{5}\pi$

## Intuition
- If $\textbf{r}(t)$ is the **position vector** of a particle at $t$, then $\textbf{r'}(t)$ is the **velocity vector** and $|\textbf{r'}(t)|$ is the speed
	- To compute distance traveled, we must **integrate speed**

## Steps
1. Find limits of integration $t$
2. Find $$|\textbf{r'}(t)|$$
3. Integrate
![](../../Images/Pasted%20image%2020231021162319.png)

![](../../Images/Pasted%20image%2020231021162347.png)
![](../../Images/Pasted%20image%2020231021162354.png)
![](../../Images/Pasted%20image%2020231021162404.png)

# Arc Length Function
- Suppose $C$ is a curve given by a vector function
$$\textbf{r}(t) = f(t)\textbf{i} + g(t)\textbf{j} + h(t)\textbf{k}\hspace{2em}a \leq t \leq b$$
- Its **arc length function** $s$ is
![](../../Images/Pasted%20image%2020231021162719.png)
- Differentiate both sides of Part 1 using **Fundamental Theorem of Calculus**
![](../../Images/Pasted%20image%2020231021163050.png)
![](../../Images/Pasted%20image%2020231021165306.png)

