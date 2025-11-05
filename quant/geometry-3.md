# Geometry 3
#flashcards/quant/geometry-3

Area of circle
?
- $$\huge \pi r^2$$
	- $r =$ radius of circle

Area of a sector
? ^area-sector
- $$\huge a_{\text{sector}} = \frac{x}{360} \cdot \pi r^2$$
	- $x =$ central angle
	- $r =$ radius
- This is the same idea as finding the [[geometry-2#^arc-length|arc length]], since we multiply the total area by how much space our central angle takes up out of the entire circle


Tangent line
?
- Line that intersects only one point on a circle's circumference
	- This line is perpendicular to the radius line drawn from the center of the circle
	- Recall that as we increase the number of sides on a regular polygon, the interior angle approaches $180^\circ$, which is the same angle as the side of a flat line
- ![[Pasted image 20251104143830.png]]


Chord
?
- Line segment connecting any two points in the circle
	- ![[Pasted image 20251104143721.png]]
- The chord is always shorter than it's corresponding arc
	- ![[Pasted image 20251104193454.png]]

Inscribed polygon
?
- A polygon $A$ is inscribed inside of polygon $B$
- This means $A$ is drawn inside $B$ such that **ALL** of $A$'s vertices are touching $B$ but exceeding the edges of $B$
- Does not have to be a regular polygon
- Inscribing shapes lets you share lengths across multiple shapes
	- **Ex.** Square inscribed inside a circle
		- The diagonal of the square is also the diameter of the circle 
- **NOTE:**
	- Some pairs of shapes cannot be inscribed
	- **Ex.** Decagon cannot be inscribed inside of a square, because not all vertices are touching the edges of the square
	- ![[Pasted image 20251104194534.png]]
- 

Circumscribed polygon
?
- A polygon $A$ is circumscribed about another polygon $B$
- This means $A$ is drawn around $B$, such that **ALL** of $B$'s vertcies are touching but not exceeding the edges of $A$
- Does not have to be a regular polygon

Max area of inscribed polygon
?
- Given a polygon $A$ inscribed inside of a polygon $B$
- Shape that maximizes inscribed area is a regular polygon
- As $A$'s shape approaches $B$'s shape, the area of $A$ increases until it's identical to the area of $B$
	- ![[Pasted image 20251104195359.png]]

Concentric circles
?
- Two circles are concentric if they share the same center
- Doubling the radius or diameter quadruples the area, because the radius is squared in the area formula of a circle

3D figures
?
- Cubes
- Cylinders/Prisms
- Spheres
- Cones/Pyramids

Cube 
?
- 3D equivalent of a square
- All sides of the cube have equal length
- Calculations
	- $$\huge \text{volume} = s^3$$
	- $$\huge \text{surface area} = 6s^2$$

Rectangular prism
?
- 3D equivalent of a rectangle
- Calculations
	- Given
		- $l =$ length of prism
		- $w =$ width of prism
		- $h =$ height of prism
	- $$\huge \text{volume} = lwh$$
	- $$\huge \text{surface area} = 2lh + 2wh + 2lw$$
Sphere
?
- Calculations
	- Given
		- $r =$ radius
	- $$\huge \text{surface area} = 4\pi r^2$$
	- $$\huge \text{volume} = \frac{4}{3} \pi r^3$$

Pyramid/cone
?
- 3D shape with a base that's a specific shape and tapers off into a single vertex
- Calculations
	- Given
	- $$\huge \text{surface area} = a_{\text{base}} + a_{\text{top}}$$
	- $$\huge \text{volume} = \frac{1}{3} a_{\text{base}} h$$

Prism/cylinder
?
- 3D shape where end caps are the same shape and connected together to form a tube
- Calculations
	- Given
		- $a_{\text{end cap}} =$ area of the end cap
		- $a_{\text{sides}} =$ area of the sides of the prism/cylinder
			- **Ex.** For a cylinder, the sides is just one long rectangle with height $h$ and width $2\pi r$
	- $$\huge \text{surface area} = 2 a_{\text{end cap}}+a_{\text{sides}}$$
	- $$\huge \text{volume} = a_{\text{end cap}} h$$

Generic capped 3D
?
- Calculations
	- Surface area $=$ sum of all face's areas
	- Volume = $a_{b}h$
		- $a_{b} =$ area of the base shape

Relationship between volume, surface area
?
- Surface area > volume for small objects
- Surface area = volume
	- Cutoff point where surface area is the same as the volume
- Surface area < volume for large objects

Open cylinder
?
- Cylinder without a cap
- This affects surface area measurements

Right cylinder/cone/prism/pyramid
?
- Cylinder/cone/prism/pyramid that is standing straight up and is not slanted

Longest diagonal of a cube
?
- Longest diagonal of a cube spans from one corner to the opposite corner
- $$\huge \text{diagonal} = s \sqrt{ 3 }$$
	- $s =$ length of a side of a cube
- You can derive this formula by drawing a right triangle with the diagonal as the hypotenuse
	- ![[Pasted image 20251104210650.png]]

Longest diagonal of a rectangular solid
?
- $$\huge \text{longest diagonal} = \sqrt{ l^2 + w^2 + h^2 }$$
	- $l =$ length of prism
	- $w =$ width of prism
	- $h =$ height of prism
- **NOTE:** This formula looks just like the 3D distance formula, because it is!
	- Finding longest diagonal is equivalent to finding the distance from the origin $(0, 0, 0)$ to the 3D point $(l, w, h)$