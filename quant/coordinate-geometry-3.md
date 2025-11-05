# Coordinate Geometry 3
#flashcards/quant/coordinate-geometry-3


Graphing quadratics by factoring
?
- You can factor standard form of the a quadratic equation (parabola) to find the x-intercepts
- The tip of the parabola is in the middle between the two x-intercepts
- **Ex.**
	- $y = x^2 + 2x - 3$
		- $y = (x - 1)(x + 3)$
		- x-intercepts are $1$ and $-3$
		- $\displaystyle \frac{1 + (-3)}{2} = -\frac{2}{2} = -1$
			- Tip is located at $x = -1$
			- $y = 1 - 2 - 3 = -1 - 3 = -4$
				- Tip is located at $(-1, -4)$

Graphing quadratics by completing square
?
- You can complete the square to reshape the standard form into the [[coordinate-geometry-2#^parabola-vertex-form|parabola vertex form]]
- **Ex.**
	- $y = x^2 - 8x + 4$
		- $y + 16 = x^2 - 2 * 4 x + 16 + 4$
		- $y + 12 = (x - 4)^2$
		- Tip is located at $(4, -12)$

Discriminant and quadratic equations
?
- Recall that discriminant $b^2 - 4ac$ can determine the number of solutions
	- One solution
		- Tip of parabola touches the x-axis
	- Two solutions
		- Parabola intersects with x-axis twice
	- Zero solutions
		- Parabola does not touch x-axis

Circle equation
?
- $$\huge (x - x_{0})^2 + (y - y_{0})^2 = r^2$$
	- $(x_{0}, y_{0}) =$ center of circle
	- $r =$ radius of circle from center
	- It's very important that we're adding $x^2$ to $y^2$
		- Otherwise, it's not a circle
	- To convert a non-standard circle formula to this format
		- Complete the square for $x$ and $y$
		- **Ex.** $3 = x^2 + 4x + y^2 - 6y$
			- $3 + 4 + 9 = (x^2 + 4 + 4) + (y^2 - 6y + 9)$
			- $16 = (x + 2)^2 + (y - 3)^2$

Graphing absolute value
?
- $$\huge y - y_{0} = a|x - x_{0}|$$
	- $(x_{0}, y_{0}) =$ center tip of absolute value
	- $a =$ scaling factor
		- Positive -> V shape from tip
		- Negative -> inverted V shape from tip (flipped)

Graphing absolute value in general
?
- Given $y = |x^2 - 2|$
	- Write out both equations
		- $y = x^2 - 2$
		- $y = -x^2 + 2$
	- Graph both equations
	- Keep the parts of the graph that are positive

Rotating point 90 degrees
?
- $(x, y) \to \text{rotate }90^\circ \to (-y, x)$
- $(x, y) \to \text{rotate }-90^\circ \to (y, -x)$

Even odd function graphical properties
?
- Even functions are symmetric around y-axis
	- **NOTE:** If it's symmetric around the x-axis, it doesn't count
		- **Ex.** $y^2 = x$ is a horizontal parabola, which is neither even nor odd function
- Odd functions are symmetric with the origin ($y=-x$)

Graphing square root
?
- $y = \sqrt{ x }$
	- Graphs top half of a parabola lying on it's side
- $y = -\sqrt{ x }$
	- Graphs bottom half of parabola lying on it's side
- $\sqrt{ y } = x$
	- Graphs right side of parabola
- $-\sqrt{ y } = x$
	- Graphs left side of parabola

Calculating intersection
?
- Set the two equations equal to each other and solve for $x$
- **Ex.**
	- $y = x^2$ and $x = y^2$
		- If we have a quadratic, we **DON'T** want to take the square root, since that limits our domain
		- Instead, raise the first equation $y=x^2$ by a power of $2$
	- $y^2=x^4$ and $x=y^2$
	- $x^4=x$
	- Therefore, the two curves intersect at $x =0, 1$

Graph shift rules
?
- Given a curve defined by
	- $f(a(x - x_{0})) = x + y_{0}$
	- $a =$ amount to scale by
		- Negative $\to$ flip
		- $0 < |a| < 1 \to$ shrink down
		- $1 < |a| \to$ scale up
	- $x_{0} =$ amount to shift horizontally (+ means rightwards)
	- $y_{0} =$ amount to shift vertically (+ means up)