# Math 53 Review
## 14.1 Level Curves
With equation $f(x, y) = k$, where k is constant

*Aside*
$f(x,y) = z$ represents a surface $<x, y, z>$
$f(y) = x$ represents a vector $<x, y>$
## 14.2 Continuity

#### Definition with limits
Func$f$ of two variables is continuous is *continuous* at $(a, b)$ if 
$\lim_{(x, y) \to (a, b)} f(x, y) = f(a, b)$

$f$ is continuous on $D$ if $f$ is continuous at every point in $(a, b)$ in $D$

### Continuity – Clairaut's Theorem
$f_{yx} = f_{xy}$ when $f$ is continuous across

#### Squeeze Theorem
Useful for trig functions and fractions that can not be otherwise analyzed
Steps:
- Use min and max bounds to set and squeeze the function to find it's limit
- Similar to giving a starter point/helper function

## 14.3 Calculating *PARTIAL* Derivatives
$z = f(x, y)$
- To find $f_x$ regard y as constant & differentiate f(x, y) with respect to $x$
- To find $f_y$ regard x as constant & differentiate f(x, y) with respect to y
##### Finding $f_x$ and $f_y$ from limits
Use ${\lim_{x \to 0}}f_x = \frac{f(x + h, y) - f(x, y)}{h}$ 
(same for $f_y$)

##### Notations
$f_x = \frac{\partial f}{\partial x} = \frac{\partial}{\partial x}f(x,y) = \frac{\partial z}{\partial x}$

### Partial vs. Implicit differentiation
- Partial Differentiation
	- Can solve partial derivatives using limit above
	- Solving for one variable, other held constant
	- Say $g(x)= f(x, y)$ where $x$ is varied, $y$ is fixed
		- If $g$ has a derivative at $a$, this derivative is that partial derivative of $f$ with respect to $x$ at $(a, b)$
	- &#8594;  implicit!
- Implicit Differentiation
	- Solving for both variables, with one variable isolated at the end
	- differentiates expression that is not a function 


## 14.4 Tangent Planes + Linear Approx

Tangent Planes
- Planes are described by at min two lines
- Thus: tangent planes describe by **two** tangent lines

For a plane $S$ with point $P$, the tangent line of $S$ at $P$ consists of all possible tangents to $P$ (plane consisting of curves tangent to $S$ and passing through $P$)

*Equations*
Any plane passing through point $p = (x_0, y_0, z_0)$
$A(x-x_0) + B(y-y_0) + C(z-z_0) = 0$

$z-z_0 = \frac{-A}{C}(x-x_0) + \frac{-B}{C}(y-y_0)$
*thus, intersection at $y=y_0$*
$z-z_0 = a(x-x_0)$  &#8594; point-slope form
thus, $a = f_x(x_0, y_0)$

**Equation of Tangent Plane**
$z-z_0 = f_x(x_0, y_0)(x-x_0) + f_y(x_0, y_0)(y-y_0)$

**Linear Approximation/Tangent Plan Approx of $f$ at $(a,b)$**
From the form above:
$z = f_x(x_0, y_0)(x-x_0) + f_y(x_0, y_0)(y-y_0) + z_0$
Thus, linearization:
$f(x, y) \approx f(a,b) + f_x(a,b)(x-a) + f_y(a,b)(y-b)$

#### Differentiability 
If z can be written as 
$z = f_x(x, y) \Delta x+f_y(x,y)\Delta y + \epsilon_1 \Delta x+ \epsilon_2 \Delta y$ 
where $\epsilon \to 0, (\Delta x, \Delta y) \to (0, 0)$
OR
If $f_x, f_y$ exist near $(a, b)$ and are continuous at $(a,b)$, $f$ is differentiable at $(a, b)$


**Total Differentials**
$\Delta y, \Delta x$ &#8594; independent from one another
$dz$ &#8594;total differential

$dz = f_x(x, y)dx + f_y(x,y)dy$ = $\frac{\partial z}{\partial x}dx + \frac{\partial z}{\partial y}dy$
$dz = f_x(a,b)(x-a)+f_y(a,b)(y-b)$


**3+ vars**
$f(x, y, z) \approx f(a, b, c)+ f_x(a, b,c)(x-a) + f_y(a,b,c)(y-b)+...$
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4NDg5MTMwMTUsLTEzMzk1MDc0LDEyNz
ExNTQxNjMsLTIwMTM3ODYzOTUsLTE5NTAyMDUzNTMsNDQ4Mzcy
MTI4LC01MzUyNTcyNzYsLTczNTU3Mjc4MSwtMTU3NjA2MTg1NS
wxMjgxNTExNDc4XX0=
-->