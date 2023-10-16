# 13.2 = Derivatives and Integrals of Vector Functions

- Construct, plot, analyze, differentiate, and integrate parametric representations of vector-valued functions.
- Apply vectors to solve applied problems involving basic physics concepts such as velocity, force, and work.
- Determine points of intersection and collision, if they exist, for particles along paths given by parametric or vector-valued functions.
- Use the derivative to find and/or sketch unit tangent vectors and/or tangent lines to plane curves.
- Find the points of intersection of plane curves and/or the angle between them.
- Evaluate definite and indefinite integrals of vector functions.
- Derive and/or use formulas for derivatives of operations on vector functions.

$$\frac{d\vec{r}}{dt} = \vec{r'}(t) = \lim_{h \to 0} \frac{\vec{r}(t + h) - \vec{r}(t)}{h}$$
- **Secant visualization** = Similar to derivative of 2D function
	- $P$ and $Q$ have position vectors $\vec{r}(t)$ and $\vec{r}(t + h)$
	- $\vec{PQ}$ represents the vector $\vec{r}(t + h)- \vec{r}(t)$ (*secant vector*)
	- As $h \to 0$, the vector approaches a vector that lines **on the tangent line**
	- $\vec{r'}(t)$ is called the **tangent vector** to the curve $\vec{r}$ at point $P$
![](../../Images/Pasted%20image%2020231015110236.png)

- **Computation = Differentiate each component of $\vec{r}$**
> If $\vec{r}(t) = \langle f(t), g(t), h(t) \rangle = f(t)\textbf{i} + g(t)\textbf{j} + h(t)\textbf{k}$ where $f, g, h$ are differentiable functions, then
> $\vec{r'}(t) = \langle f'(t), g'(t), h'(t) \rangle = f'(t) \textbf{i} + g'(t) \textbf{j} + h'(t) \textbf{k}$
![](../../Images/Pasted%20image%2020231015110611.png)
