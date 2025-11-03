# Algebra 1
#flashcards/quant/algebra-1

Variables
?
- Unknown values in expressions, represented by a letter
- $x,y,z$ tend to represent variables
- $a,b,c$ tend to represent fixed constants
	- **Ex.** $0 = ax^2 + bx + c$
- Single variable may have more than one value
	- **Ex.** $(x - 2)(x)(x + 2) = 0$
		- $x = 2, 0, -2$
- Single variable may have infinitely many values
	- **Ex.** $x + y = 7$
- Single variable may have no possible value
	- **Ex.** $x = 0.3 x$

Algebraic expressions
?
- An equation that contains variables

Term
?
- Anything that is separated by addition
	- **Ex.** $4x^2 + 7x - 9$ has the terms $4x^2$, $7x$, $-9$
- Terms may contain more than one variable
	- **Ex.** $4xy + 3y$ has the terms $4xy$ and $3y$

Like terms
?
- Terms that have the same variable portion are called like terms
	- **Ex.** In $4x^2 + 3 + 7x^2$, $4x^2$ and $7x^2$ are like terms
- Like terms can be added together
	- $4x^2 + 3 + 7x^2 = 11x^2 + 3$

Constant
?
- Terms that are not connected to variables
- **Ex.** $4x^2 + 7x - 9$ has the constant $-9$

Coefficient
?
- Integer connected to a variable inside a term
- **Ex.** $4x^2 + 7x - 9$ has the coefficients $4$ and $7$

Polynomial
?
- Summation of terms, containing variables, coefficients, and constants
- The exponent of each term's variable must be $\geq 0$
	- If the exponent is $0$, then that term has no variable and it's a constant
- **Ex.** $4x^2 + 7x - 9$

Term degree
?
- The degree of a term in a polynomial is the sum of the exponents of the variables
- **Ex.**
	- $4x^2$ has a degree of 2
	- $4xy^2$ has a degree of 1 + 2 = 3

Polynomial degree
?
- The degree of a polynomial is highest degree out of any of the terms
- Concept of degree is only relevant for polynomials
- **Ex.**
	- $4x^2 + 7x - 9$ is a degree 2 polynomial
	- $8x + 3$ is a degree 1 polynomial

Factoring
?
- You can "factor" out common values from a polynomial
- You can extract any value from the polynomial — even if it doesn't exist in the polynomial, given you're dividing each term by the term you're extracting
- **Ex.**
	- $3x^2 + 6x = 3x(x + 2)$
	- $16xy^3 - 4x^2y + 6xy^2 = 2xy(8y^2 - 2x + 3y)$
	- $x^4 + x^6 = x^6(x^{4-6} + 1) = x^6{x^{-2} + 1}$
	- $x^{-4} + x^{-6} = x^{-6}(x^{-4 - (-6)} + 1) = x^{-6}(x^2 + 1)$

Operations with expressions
?
- Addition and subtraction work with like terms
- Multiplication works within the same term, and we can multiply the same variables together, and multiply the coefficients together

Fraction expressions with denominator containing $x$
?
- If a fraction expression has a variable $x$ in the denominator
	- Solve for when the denominator is $0$
	- This usually happens naturally as you factor the numerator and denominators into simpler forms
	- Any value of $x$ that causes the denominator to be $0$ will be excluded by the **domain** of the equation
		- In other words, any value of $x$ that causes the denominator to be $0$ will be excluded from the set of valid $x$ values
		- **Ex.** 
			- $\dfrac{1 + x}{x^2 - 3^2} = \dfrac{1 + x}{(x - 3)(x + 3)}$
			- $x \neq 3$ and $x \neq -3$

FOIL
?
- First, outside, inside, last
- Strategy for multiplying binomials together
- $(a + b)(c + d) = ac + ad + bc + bd$
- This can be extended to an arbitrary number of terms
	- Go from left to right on the first polynomial
	- For each term, match it with every term from left to right on the second polynomial

Algebraic identities
?
- Square of a binomial sum
	- $(a + b)^2 = a^2 + 2ab + b^2$
- Square of binomial difference
	- $(a - b)^2 = a^2 - 2ab + b^2$
- Difference of squares
	- $(a + b)(a - b) = a^2 - b^2$
- Cube of a binomial sum
	- $(x + y)^3 = x^3 + 3x^2y + 3xy^2 + y^3$
- Cube of a binomial difference
	- $(x - y)^3 = x^3 - 3x^2y + 3xy^2 - y^3$

Factoring trinomial
?
- Given a trinomial $ax^2 + bx + c$, how can we split it into two factors?
	- **Ex.** $3x^2 - 7x - 6$
- Steps
	1. Attempt to factor the first term across both terms
		- **Ex.** $(3x + u_{0})(x + u_{1})$
			- Let $u_{0}$ and $u_{1}$ be the unknown constants
	2. Attempt to factor the constant across both terms
		- The constants we pick should satisfy the following condition:
			- The product of the outer coefficients added to the product of the inner coefficients should equal the middle coefficient of the trinomial
		- **Ex.** 
			- $2 \cdot u_{1} + 3 \cdot u_{0} = 7$
			- $(3x + 2)(x - 3)$
	3. Verify your solution by expanding the product of the two binomials

Binomial theorem (Binomial expansion using Pascal's triangle)
?
- Given $(a + b)^n$
- Build Pascal's triangle until you have $n + 1$ layers
	- The first layer of the triangle corresponds with $n = 0$
- Find the $n + 1$ layer in the triangle
- Each term in the triangle represents the coefficient of the term
	- $c_{0}, c_{1}, \dots, c_{m}$
- Your first term (leftmost term) is $c_{0} a^n b^0$
- Move to the right and decrease the exponent of $a$ while increasing the exponent of $b$
- Your last term should be $c_{m} a^0b^n$
- A handy way to check the term signs for the final expression
	- If the binomial expression is $(a+b)^n$, then every term is positive
	- If the binomial expression is $(a - b)^n$, then the first term is positive, the next term is negative, and the term's sign keeps flipping until you reach the last term

Exponent rules with variables
?
- Same exponent rules as with regular values

True or false: $\sqrt{ (x + y)^2 } = x + y$
?
- False
- See [[#^simplify-even-roots|simplify even roots]]

Simplifying square/even roots
? ^simplify-even-roots
- Whenever you remove a square/even root, you must wrap the result in an absolute value to account for the case that the value inside of the square/even exponent is negative, since even exponents allow both $-a$ and $a$ to be valid solutions
- **Ex.** $\sqrt{ (x + y)^2 } = |x + y|$

True or false: $2^{2^{2^2}} = 2^8$
?
- False
- The exponents apply to exponents, rather than the entire term
- The left side is not the same as $((2^2)^2)^2$

Equation
?
- Expression that is equal to another expression
- May contain one or more variables
- **Ex.** 
	- $x = 10$
	- $8x + 7y = 3$

Equation manipulation rules
?
1. You can add/subtract terms to both sides
2. You can substitute equations into other equations
3. Special cases
	- You cannot multiply both sides by $0$, since that would instantly destroy the equation
	- If you dividing by a variable $x$ and eliminate it, you must account for a potential $x=0$ solution

Equivalent equations
?
- Equations that are just scaled up versions of each other are considered equivalent equations

Linear equation
?
- Equation where variables are at most to the first power
- Equation forms a straight line when plotted on a graph
- **Ex.** $7x + y = 3$

Solving 1-variable system of equations
?
- Isolate the variable by performing operations to both sides until you get $x = \dots$

Solving multi-variable systems of equations
?
- Substitution
	- Isolate one variable $y = \dots x \dots$ in one equation
	- Substitute that value of $y$ into the occurrences of $y$ in another equation
	- Repeat until you end up with a 1-variable system of equation $x = \dots$
	- Then solve for 1-variable system until you get a solution $x = \dots$
	- Plug the value you got for $x$ into the previous substitution equations to find the value of $y$
		- Repeat for however many variables you need
- Scaling and subtracting equations
	- Scale an equation such that one of the term aligns with the same corresponding term in another equation
	- Subtract the two equations to create a new equation that does not contain that shared term
	- Repeat until you end up with a 1-variable system, and then solve it to get a solution $x = \dots$
	- Plug the value you got for $x$ into a previous equation to find the value of $y$
		- Repeat for however many variables you need