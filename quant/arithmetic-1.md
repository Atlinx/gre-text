# Arithmetic 1
#flashcards/quant/arithmetic-1

All primes < 100
?
2, 3,  5,  7,  11,  13,  17,  19,  23,  29,  31,  37,  41,  43,  47,  53,  59,  61,  67,  71,  73,  79, 83,  89,  97
**mnemonic**
2 3 5 7
1 3 7 9
3 9
1 7
1 3 7
3 9 
1 7
1 3 9
3 9 
7

PEMDAS
?
- Parentheses
- Exponents
- Multiplication
- Division
- Addition
- Subtraction

Primes from $[1, 50]$
?
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47
**mnemonic**
2 3 5 7
1 3 7 9
3 9
1 7
1 3 7

Primes from $[50, 100]$
?
53, 59, 61, 67, 71, 73, 79, 83, 89, 97
**mnemonic**
3 9 
1 7
1 3 9
3 9 
7

Distance in GRE
?
- Distance means absolute value of the difference between two numbers
- **Ex.** Distance between -5 and 3
	- $\text{distance} = |-5 - 3| = |-8| = 8$

Integers in interval $[a, b]$ formula
?
- $b - a + 1$
	- If inclusive
- $b - a$
	- If exclusive on one-side
- $b - a - 1$ 
	- If exclusive on both-sides

Sum of consecutive integers in an interval $[a,b]$ formula
?
$$\frac{n}{2} (a + b)$$
- $n =$ number of integers in interval

Sum
?
- Result of addition
- **Ex.** $a + b$

Difference
?
- Result of subtraction
- **Ex.** $a - b$

Quotient
?
- Result of division
- **Ex.** $\dfrac{a}{b}$

Product
?
- Result of multiplication
- **Ex.** $a \times b$

Factor
?
- Number that divides another number
- Also known as a **divisor**
- **Ex.** 3 is a factor of 6, because $3 \times 2 = 6$

Multiple
?
- A number $a$ is a multiple of $b$, if $\dfrac{b}{a} = x$ or $a \cdot x = b$, where $x$ is an integer
- **Ex.** 6 is a multiple of 3 because $\dfrac{6}{3} = 2$
- If a number $x$ has a factor $y$, then $x$ is a multiple of $y$

Finding factors for $n$
?
1. Let $x = 1$
2. If $\dfrac{n}{x} = b$, and $b$ is an integer, then record $x, b$ as factors
3. Try the next number $x = x + 1$
4. Continue until you loop back to a factor you've already recorded

Factorial $n!$
?
- $n! = 1 \times 2 \times 3 \times \dots \times n$
- The factors of $n!$ are all the numbers from $[1, n]$
- $0! = 1$

Finding non-factors of factorials
?
- Prime non-factor
	- Given a factorial $n!$, find the next prime number after $n$
	- Repeat to find more prime non-factors
- Composite non-factor
	- Given a factorial $n!$, find the next prime number after $n$
	- Then multiply that prime number by $2, 3, \dots$ to get the next few composite numbers
	- Repeat with the next prime number, until you have a pool of composite non-factors
	- Sort the non-factors to get the composite non-factors in ascending order

Counting number of factors of $a$ for $n!$ when $a$ is prime
? ^count-prime-factor-in-factorial
- Relevant for problems like $\dfrac{100!}{5^x}$
- Repeatedly divide the number $n$ by $a$, and flooring the result each time
- Finally, sum together all the numbers
- This effectively finds all occurrences of
	- $a^1, a^2, a^3, \dots$

Counting number of factors of $a$ for $n!$ when $a$ is **not** prime
? ^count-composite-factor-in-factorial
- Relevant for problems like $\dfrac{100!}{12^x}$
- Break the composite number into it's prime factorization
	- **Ex.** $12^x = (2^2 \cdot3)^x = 2^{2^x} \cdot 3^x$
- The number of occurrences for $a$ is limited by the count of the largest prime factor
	- Therefore you must find the count of the largest prime factor
	- See [[#^count-prime-factor-in-factorial|counting prime factor in a factorial]]
- If a prime factor occurs multiple times in $a$, then you count the largest sum as $2^2$

Number of trailing zeroes in factorial $n!$
?
- Number of trailing zeroes in a factorial is determined by the number of multiples of 10 there are in the factorial
	- $10 = 5 \times 2$, therefore $5$ is the limiting multiple
- Find the number of multiples of $5$ in the factorial 
	- See [[#^count-prime-factor-in-factorial|counting prime factor in a factorial]]

Even-odd rules for sum + product
?
- Sum
	- $\text{even} + \text{even} = \text{even}$
	 - $\text{even} + \text{odd} = \text{odd}$
	  - $\text{odd} + \text{odd} = \text{even}$
- Product
	- $\text{even} \times \text{even} = \text{even}$
	 - $\text{odd} \times \text{even} = \text{even}$
	 - $\text{odd} \times \text{odd} = \text{odd}$

Non-negative
?
$\geq 0$

Non-positive
?
$\leq 0$

Even
?
- Number that is a multiple of 2
- This includes 0

Odd
?
- Number that is not a multiple of 2

Divisibility rules
?
- 1 → All numbers are divisible by 1
- 2 → Last digit is divisible by 2 (0, 2, 4, 6, 8)
- 3 → Sum of all digits is divisible by 3
- 4 → Last 2 digits make a number that's divisible by 8
- 5 → Last digit is 0 or 5
- 6 → Divisible by 2 and 3
- 7
	- Sum of alternating positive/negative blocks of 3 digits starting from the right is divisible by 7
	- Take last digit, multiply by 2, and subtract from the number formed by the remaining digits, and check if the result is divisible by 7
- 8
	- Divisible by 2 and 4
	- Last 3 digits make a number that's divisible by 8
- 9 → Sum of digits is divisible by 9
- 10 → Last digit ends in 0
- 11 → Sum of alternative positive/negative digits is divisible by 11

Prime
?
- Number that is only divisible by itself and 1

Composite
?
- Number that is not prime
- Number that is divisible by 1, itself, and at least one other number

Prime factorization (decomposition)
? ^prime-factorization
- Method for breaking down a number into it's prime factors
- Each number has a unique set of prime factors that when multiplied together, form the number
	- **Ex.** $18 = 3^2 \times 2$
- Steps
	- Write the number
	- Split the number into two factors
	- Then repeatedly split those factors down into two factors each, until you're left with primes
	- You can rewrite the number as a product of primes
		- **Ex.** $18 = 3^2 \times 2$

Greatest common factor (GCF)
? ^greatest-common-factor
- The largest factor that is shared between two numbers
- Given two numbers $a$ and $b$, we want to find the GCF between both numbers
- Steps
	1. Find the prime factors of $a$ and $b$
	2. Take the set of prime factors that exists in both $a$ and $b$ 's prime factorization
	3. Take the product of this subset of factors to get the GCF

Least common multiple (LCM)
? ^least-common-multiple
- The smallest multiple that is shared between two numbers
- Given two numbers $a$ and $b$, we want to find the LCM of both numbers
- Steps
	1. Multiply $a$ by $1, 2, 3, \dots$ a few times
	2. Multiple $b$ by $1, 2, 3, \dots$ a few times
	3. The first number that occurs in both lists is the LCM
		1. You can repeatedly extend the lists as necessary so the highest value of one can catch up to the other

Adding numbers to multiples
?
- Given $a$ and $b$ are both multiples of $3$, then  $a + b$ is also a multiple of $3$
- **Ex.** $3 + 6 = 9$ is a multiple of $3$
- **Ex.** $30! + 29$ is still a multiple of $29$

Count multiples in an interval
? ^count-multiple-interval
- Given an interval $[a, b]$, we want to find number of multiples of $m$ in the interval
- Find the new interval boundaries in the multiple number line
	- Find $a_{1} = \left\lceil  \dfrac{a}{m}  \right\rceil$, which is the lower bound that's a multiple of $m$
		- If the interval is exclusive on the lower bound and $\dfrac{a}{m} = 0$, then $a_{1} = a_{1} - 1$
	- Find $b_{1} = \left\lfloor  \dfrac{b}{m}  \right\rfloor$, which is the new upper bound that's a multiple of $m$
		- If the interval is exclusive on the upper bound and $\dfrac{a}{m} = 0$, then $a_{1} = a_{1} + 1$
	- $b_{1} - a_{1} + 1 =$ number of multiples of $m$ in the interval

Sum of multiples in an interval 
?
- Given an interval $[a, b]$, we want to find the sum of the multiples of $m$ in the interval
- Find the interval boundaries $[a_{1}, b_{1}]$ in the multiple number line
	- See [[#^count-multiple-interval|counting multiples in an interval]]
- $\dfrac{n}{2} \cdot m (a_{1} + b_{1}) =$ sum of multiples in interval

Three consecutive integer properties
?
- Given three consecutive integers
	- Sum is divisible by 3
	- Product
		- Is divisible by 3
		- Is divisible by 2
		- Is divisible by 4 or 8 if you have two even numbers surrounding an odd number
			- Otherwise, it might not be divisible if you have $\text{odd} \times \text{even} \times \text{odd}$ as your consecutive numbers
- Given three consecutive integers of any pattern
	- **Ex.** 
		- Three consecutive even integers
		- Three consecutive multiples of 4
	- Previous rules still hold
	- Proof of summation rule
		- $n + (n+a) + (n + 2a) = 3n + 3a = 3(n + a)$
		- Therefore summation of any consecutive sequence is divisible by 3
	- Proof of product rules
		- $(n - a) n (n + a)$
		- Divisible by 2, since you're bound to find a multiple of $2a$ inside the 3 term consecutive sequence 
		- Divisible by 3, since you're bound to find a multiple of 3a inside of the 3 term consecutive sequence
		- When both outer terms are a multiple of $2a$, then it's divisible by both 4 and 8

0 properties
?
- Even
- Neither positive or negative
- Is a multiple of every integer
	- All integers are factors of 0, including itself
- Is not a factor of any other integer
- $0^x = 0$ when $x \neq 0$
- $x^0 = 1$ when $x \neq 0$
- $0^0 = \text{undefined}$
	- **Ex.** Given $x^0=1$ and $0^x=0$ for some $x > 0$, consider what happens when $x \to 0$
		- Both statements become nearly identical, and at $x = 0$, it creates a contradiction

$\sqrt{ 36 }$
?
- $6$
	- The square root of a positive number is always positive on the GRE