# Math 53 Review

## Continuity

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

## Calculating *PARTIAL* Derivatives
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



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI4MTUxMTQ3OF19
-->