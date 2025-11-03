# Algebra 3
#flashcards/quant/algebra-3

Function
?
- Equation that takes in an input and produces an output
- GRE only cares about single-variate functions
- **Ex.** $f(x) = x^2 + 1$
	- Input is $x$
	- Output is the result of $x^2 + 1$ 

Recursive functions
?
- Steps to solve
	1. Start with the initial equation they give you
	2. Manipulate the equation based on the function's definition to get the next recursive iteration
	3. Repeat as many iterations as necessary to reach the desired value
		1. If you notice a pattern, you can try to skip ahead
- **Ex.**
	- $f(x)$ is a function such that $f(x + 1) = 10f(x)$. If $f(3) = 5$, what is the value of $f(6)$?
	- $f(3) = 5$
	- $f(3 + 1) = 10 f(3) = f(4) = 10 \cdot 5 = 50$
	- If you notice a pattern, you can try to skip ahead
		- $6 - 3 = 3$
		- $f(6) = 5 \cdot 10^3 = 5000$

Function with expression in input
?
- **Ex.** Function $f$ is defined by $f(3x + 2) = 2x^3 + 8$ What is $f(11)$?
	- You solve for the expression in the input first
		- $3x + 2 = 11$
		- $3x = 9$
		- $x = 3$
	- Then you plug in the $x$ value into the function
		- $f(3) = 2 \cdot 3^3 + 8 = 2 \cdot 27 + 8 = 54 + 8 = 62$

Domain
?
- The set of all valid input values for a function
- Often written in set builder notation
	- **Ex.** $\{ x \in \mathbb{R} : x \neq 2\}$
- **Ex.** $f(x = \sqrt{ x })$
	- Domain: $x \geq 0$

Range
?
- The set of all valid outputs for a function
- **Ex.** $f(x) = x^2$

Even functions
?
- $f(-x) = f(x)$
- This means negative inputs have the same output as their corresponding positive input
- Sign of input has no affect on output
- **Ex.** 
	- $f(x) = x^2 + x^4$
		- Polynomial with all even degrees
	- $|x| = 3$
		- Absolute value
	- $f(x) = x^2 + 3$
		- **NOTE:** $x^0$ is considered an even degree!

Odd functions
?
- $f(-x) = -f(x)$
- Negative inputs make the output negative
- Signs have an affect on the output
- **Ex.**
	- $f(x) = x^3 + x^7$
		- Polynomial with all odd degrees

A number is moved two places to the right
?
- $10^2n$

Isabella is putting Easter eggs into as many baskets as needed until she runs out of eggs. If she places 3 eggs into each basket except one, she'll have to place 2 eggs in the final basket. If she places 5 eggs into each basket except one, she'll also have to place 2 eggs into the final basket. If Isabella has fewer than 20 eggs total, how many eggs does she have?
?
- Limiting factor is eggs
- Equation
	- $3a+2=e$
	- $5b+2=e$
	- $e \leq 20$
- Solving
	- Set first two equations equal
		- $3a + 2 = 5b + 2$
		- $3a = 5b$
	- $a = 5, 50, \dots$
	- $b = 3, 30, \dots$
		- We know $a$ must be $5$ or contain $5$ as a factor
		- We know $b$ must be $3$ or contain $3$ as a factor
	- Since total number of eggs $\leq 20$, only $a=5$ works, which gives us $17$ total eggs

Simple interest
?
- Getting a fixed % of an initial amount every year
- $$\huge \text{total} = p(1 + nr)$$
	- $p =$ principle (initial amount)
	- $r$ = annual interest rate in decimal
	- $n =$ number of years

Compound interest
?
- Getting % of your current amount in the account every year
- $$\huge \text{total} = p\left( 1+\frac{r}{c} \right)^{nc}$$
	- $p =$ principle
	- $r =$ annual interest rate in decimal
	- $n =$ number of years
	- $c$ = number of times we apply the interest in a year

Mixture problem
?
- **Ex.** Solution A contains 30% alcohol and Solution B contains 55% alcohol. If 300 mL of solution A is mixed with 200 mL of Solution B, then alcohol accounts for what percentage of the combined mixture?
- Calculate total mixture volume
	- $300 + 200 = 500$
- Calculate total alcohol content
	- $300 \cdot 0.3 + 200 \cdot 0.55 = 90 + 110 = 200$
- Calculate total alcohol percentage
	- $\dfrac{200}{500} = \frac{400}{1000} = 0.4$

Mixture problem conversion formula
?
- To find out how much of an element we have to add 
	- $$\huge \dfrac{a}{b} = \frac{p_{b} - p_{f}}{p_{f} - p_{a}}$$
		- $a =$ amount of A
		- $b =$ amount of B
		- $p_{b} =$ percentage of compound in B
		- $p_{a} =$ percentage of compound in A
		- $p_{f} =$ percentage of compound in final mixture
- **Ex.** Fertilizer A contains 35% of compound V and Fertilizer B contains 60% of compound V. How many kg of Fertilizer B should be mixed with 10 kg of Fertilizer A so that the resulting mixture contains 50% of compound V?

Distance formula
?
- $$\huge d = rt$$
	- $d =$ distance
	- $r =$ rate
	- $t =$ time
- Note that rate must have the units of distance / time for this formula to work

Work rate
?
- $w = rt$
	- $w =$ work done
	- $r =$ rate of work
	- $t =$ time
- If there are multiple identical producers/consumers
- $w = nrt$
	- $n =$ number of producers/consumers

Relative speed
?
- Given two objects $a$ and $b$ moving at specific speeds, find the relative speed between $a$ and $b$
- $$\huge s_{\text{a relative b}} = s_{b} - s_{a}$$
	- $s_{a} =$ speed of $a$, positive
	- $s_{b} =$ speed of $b$, with +/- sign indicating direction relative to $a$
- **Ex.** A train $a$ is moving 30 mph north. Another train $b$ is moving 45 mph south. What is the relative speed between train $a$ and train $b$?
	- $s_{\text{a relative b}} = -45 - 30 = -75$
	- Train $b$ is moving 75 mph away from train $a$

Working together
?
- If a problem has two people working together on the same task (assuming it can be done by multiple people in parallel), you add their rates together to find the net rate of the task

Working against each other
?
- If a problem has two people working against each other, subtract their rates to find the net rate of the task.

Sequence
?
- Ordered list of things
- Sequences can be formulated as
	- $n$ itself
		- $a_{n} = 2n$
	- A recurrence relation
		- **Ex.** 
			- $a_{n} = a_{n -1} + 3$
			- $a_{0} = 1$

Extrapolating function fallacy
?
- We cannot determine the next value of an unknown function from just it's outputs
- If we are just given a mystery function $f(x)$, and values of $x = 1, 2, 3, 4$
	- $f(1) = 1, f(2) = 4, f(3) = 9, f(4) = 16$
	- This is not enough information to determine $f(5)$
		- **Ex.** $f(x)$ could be a piecewise, disjoint function that suddenly sets $f(5) = 0$
	- We must have a definition for the function in order to predict with it

Series
?
- Sum of the first $n$ terms of a sequence
- **Ex.**
	- $1 + 2 + 3 + 4 + \dots$
	- $\displaystyle \sum_{1}^n n$

Telescoping series
?
- Special series where the terms cancel each other out, leaving just the first and/or last term

Min and max values of series
?
- Given a series defined by $\displaystyle a_{n} = \frac{1}{n + 4}$
- If we write it out, we get
	- $$\frac{1}{5} + \frac{1}{6} + \dots + \frac{1}{n + 3} + \frac{1}{n + 4}$$
- The fractions are in decreasing order, therefore we can use the first and last elements to estimate the max and min sums
	- $\dfrac{1}{5} \cdot n$ is the largest sum possible (max)
	- $\dfrac{1}{n + 4} \cdot n$ is the smallest sum possible (min)

