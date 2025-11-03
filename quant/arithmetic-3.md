# Arithmetic 3
#flashcards/quant/arithmetic-3

Rounding decimal
?
- Steps
	- Look at place you want to round to
	- Look at the place immediately after to the righ
		- If the number is 0-4, then keep the original number
		- If then number if 5-9, then increase the original place by 1
			- If it's 9 + 1, then the digit becomes 0, and we carry the 1 to the left
- **Ex.**
	- Given number $384234.489 \hspace{0.5em} 743$ and we want to round to the thousandth's place
		- $384234.490$

Exponent rules
?
- $x^0 = 1$
	- **NOTE:** $0^0 = \text{undefined}$
- $x^{-y} = \dfrac{1}{x^y}$
	- Negative exponents "flip" the fraction
- $\left( \dfrac{x}{y} \right)^a = \dfrac{x^a}{y^a}$
- $(x^a)^b = x^{ab}$
		- **NOTE:** $x^{a^b} \neq (x^a)^b \neq x^{ab}$
- $(x y)^a = x^a y^a$
- $x^ax^b = x^{a + b}$
- $\dfrac{x^a}{x^b} = x^{a - b}$

Roots
?
- $^a\sqrt{ x } = b$
	- "taking the $a$ root of $x$"
	- $b$ satisfies the following relationship
		- $b^a = x$
- $\sqrt{ x } = ^2\sqrt{ x }$
- Even roots cannot be taken for negative numbers
- Odd roots can be taken for negative numbers, and will produce a negative root
- Roots that are not perfect are irrational numbers
	- **Ex.** $\sqrt{ 2 }$
- **NOTE:** GRE specifies that
	- If $n^2 = 64$, then $n = \pm 8$
	- If $n = \sqrt{ 64 }$, then $n = 8$
		- There are no negative answers if a square root is directly written

Root as exponents
?
- We can rewrite roots as an exponent
	- $\huge ^a\sqrt{ x^b } \text{ = } x^{\frac{b}{a}}$
		- **Ex.** $\sqrt{ 4 }^3 = 4^{\frac{3}{2}} = ^2\sqrt{ 4^3 } = \sqrt{ 64 } = 4$
	- $\huge ^a\sqrt{ x } \text{ = } x^{\frac{1}{a}}$

Root rules
?
- $(^a\sqrt{ x })^a = x$
	- We "undid" the root operation
- $^a\sqrt{ x^a }$
	- We "undid" the squaring operation
- You can combine roots that have the same base
	- $\sqrt{ a } \sqrt{ b } = \sqrt{ ab }$
	- $\displaystyle \frac{\sqrt{ a }}{\sqrt{ b }} = \sqrt{ \frac{a}{b} }$

Simplifying roots
?
- Break the number under the radical into numbers that are squares
	- **Ex.** $\sqrt{ 50 } = \sqrt{ 25 \cdot 2 } = \sqrt{ 25 } \cdot \sqrt{ 2 } = 5 \sqrt{ 2 }$
- You can also break the number down into it's prime factorization and then extract out valid integers
	- **Ex.** $\sqrt{ 2000 } = \sqrt{ 2^4 5^3 } = \sqrt{ 2^4 5^2 } \cdot \sqrt{ 5 } = 2^2 \cdot 5 \cdot \sqrt{ 5 } = 20\sqrt{ 5 }$

Rationalizing the denominator
?
- Process for rewriting denominator as a rational number
	- Given $\dfrac{5}{\sqrt{ 2 }}$
		- Multiply both numerator and denominator by the root
			- **Ex.** $\displaystyle \frac{5 \cdot \sqrt{ 2 }}{\sqrt{ 2 } \cdot \sqrt{ 2 }} = \frac{5\sqrt{ 2 }}{2}$
	- Given $\dfrac{5}{1 - \sqrt{ 5 }}$
		- We can multiply the numerator and denominator by the corresponding part of the binomial $1 + \sqrt{ 5 }$
			- **Ex.** $(1 - \sqrt{ 5 })(1 + \sqrt{ 5 }) = 1 + \sqrt{ 5 } - \sqrt{ 5 } - 5 = 1 - 5 = -4$

Real numbers
?
- Category of numbers that includes
	- Integers
	- Decimals
	- Fractions (Rational numbers)
	- Irrational numbers

Absolute value
?
- $|\pm x| = x$
	- **Ex.** $|-2| = 2$
	- **Ex.** $|2| = 2$
- Measures the "distance" of a number from 0
- Measures the "magnitude" of the number

Real number 5 main properties
?
- Commutative property
	- $a + b + c = c + b + a$
	- $abc = cba$
- Associative property
	- $(a + b) + c = a + (b + c)$
	- $(ab)c = a(bc)$
- Distributive property
	- $a(b + c) = ab + ac$
- Identity property
	- $a + 0 = a$
	- $0 \cdot a = 0$
	- $1 \cdot a = a$
- Inverse property
	- $a + (-a) = 0$
	- $a \cdot \dfrac{1}{a} = 1$

Additional real number properties
?
- If product of two numbers = 0, then at least one of the numbers must be 0
	- $ab = 0 \to a = 0 \text{ and/or } b = 0$
- $\dfrac{0}{x} = \text{undefined}$

Race to infinity
?
- If $a = 1$
	- $a^2 = a = \sqrt{ a }$
- If $a > 1$
	- $a^2 > a > \sqrt{ a }$
	- Think "race to infinity", which determines how fast numbers scale
- If $0 < a < 1$
	- $\sqrt{ a } > a > a^2$
	- Race to infinity is flipped when we have fractions, since multiplying fractions together lead to smaller numbers

Absolute value properties
- $|a + b| \leq |a| + |b|$
	- This is because one of the values ($a$ or $b$) could be negative, which would cause the number to be smaller than if you'd summed together the absolute value of each individual number
- $|a||b| = |ab|$

Ratios
?
- Ratio of $a$ to $b$ means $\dfrac{a}{b}$ or $4:6$
	- **Ex.** The banana to apply ratio is four to six = $\dfrac{4}{6}$
		- 4 bananas corresponds to 6 apples
	- By treating ratios as fractions, you can simplify the ratio
- Ratio of multiple groups is represented as $a:b:c$
	- **Ex.** The ratio of bananas to apples to oranges is $2:3:4$
- **NOTE:**
	- Ratios don't describe actual quantities
	- Some problems may only give you ratio information, therefore you don't know how adding or subtracting to one group would affect the ratio

Proportions
?
- Proportion is equation with two fractions (two ratios)
- **Ex.**
	- $\displaystyle \frac{a}{b} = \frac{c}{d}$
	- A person can run 4 miles in 30 minutes. How long will it take this person to run 6 miles, assume the person runs at a constant rate?
		- $\displaystyle \frac{4}{30} = \frac{6}{x}$
		- $4x = 180$
		- $x = 45$

Unit conversions with ratios
?
- Write out the ratio relating two units together, along with the labels for the units
	- The denominator is your input, and numerator is your output
	- Take your input, (which is the same unit as your denominator), and multiply it with the fraction
	- Imagine "cancelling out" the units from the denominator and your input
- **Ex.**
	- $\displaystyle \frac{3 \text{ mi}}{6 \text{ sec}} \cdot 12\text{ sec} = \frac{3 \text{ mi}}{\cancel{ 6 \text{ sec} }} \cdot \cancel{ 12\text{ sec} } (2)  = 6 \text{ mi}$

Percent
?
- Fraction, ratio, or "parts per 100"
	- The fraction can also be represented as a decimal number, with 1.0 = 100% and 0 = 0%
- Can be greater than 100
- **Ex.** 
	- 37% is 37 parts per 100
		- Can also be written as 0.37 or $\dfrac{37}{100}$
	- A is 200% of B
		- A is double B

Percent equality property
?
- $a\%$ of $b$ = $b\%$ of $a$
- **Ex.**
	- $300\% \text{ of } 17 = 17\% \text{ of 300}$
	- $3.00 \cdot 17 = 0.17 \cdot 3$
		- Notice how there is always a $\dfrac{1}{100}$ factor on both sides of the equation

$a$ is what percentage of $b$?
?
- $\dfrac{a}{b}$

What is $a\%$ of $b$?
?
- $b \cdot \dfrac{a}{100}$

$a$ is $b\%$ of $c$. What is $c$?
?
- $\dfrac{b}{100} \cdot c = a$

Finding percent change
?
- Take the difference over the original value to find the % increase or decrease
- **Ex.** 
	- Bob had 12 marbles and 18 marbles today. What was the percent change in marbles?
		- $18 - 12 = 6$
		- $\dfrac{6}{12} = \dfrac{1}{2} = 0.5 = 50\%$
		- There was a $50\%$ **increase** in the number of marbles
	- Bob had 18 marbles and 12 marbles today. What was the percent change in marbles?
		- $12 - 18 = -6$
		- $\dfrac{-6}{12} = -\dfrac{1}{2} = -0.5 = -50\%$
		- There was a $50\%$ **decrease** in the number of marbles

Finding net result of percent change
?
- **Ex.**
	- What number is $42\%$ larger than $60$?
		- Convert the percentage to a decimal, and add $1$
			- $0.42 + 1 = 1.42$
		- Multiply the result with the number
			- $1.42 \cdot 60 = 85.2$
	- What number is $42\%$ smaller than $60$?
		- Convert the percentage to a decimal
		- Subtract that decimal from $1$
			- $1 - 0.42 = 0.58$
		- Multiply the result with the number
			- $0.58 \cdot 60 = 34.8$

Percent versus vs. percent more
?
- What is $30\%$ of $100$?
	- $0.3 \cdot 100 = 30$
- What is $30\%$ more than $100$?
	- $1.3 \cdot 100 = 130$

Equivalence between fraction, decimal, ratio, percent
?
 - You can convert between fractions, decimals, ratios, and percent's
- **Ex.** 
	- $\dfrac{1}{2} = 0.5 = 1:2 = 50\%$
	- $\dfrac{1}{3} = 0.\bar{3} = 1:3 = 33.\bar{3}\%$