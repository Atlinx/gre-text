# Arithmetic 2
#flashcards/quant/arithmetic-2

Counting positive factors
? ^counting-positive-factors
- [[arithmetic-1#^prime-factorization|Prime factorize]] the number, and rewrite in exponential form
	- **Ex.** $2^3 3^2 5^2$
- Add one to the exponents of each prime number, and multiple the numbers together
	- **Ex.** $(3 + 1) \times (2 + 1) \times (2 + 1) = 4 \times 3 \times 3 = 36$

Counting total factors
? ^counting-total-factors
- If you want to find the number of positive and negative factors, take the total number of positive factors and multiply by 2

Counting odd factors
? ^counting-odd-factors
- Prime factorize the number into exponential form
	- **Ex.** $2^33^25^2$
- Exclude 2, and use the [[#^counting-positive-factors|counting positive factors]] technique as usual
	- **Ex.** $3^25^2 \to (2 + 1) \times (2 + 1) = 3 \times 3 = 9$
	- Note that this works because 2 is the only even prime number, and multiplying odd numbers with odd numbers is the only way to produce an odd number

Counting even factors
?
- Prime factorize the number into exponential form
	- **Ex.** $2^33^25^2$
- Method 1
	- Add one to the exponents of each prime number except for 2, and multiply the numbers together
		- **Ex** $3 \times (2 + 1) \times (2 + 1) = 3 \times 3 \times 3 = 27$
	- If there are no 2 factors, then there are no even factors
- Method 2
	- Do [[#^counting-total-factors|total factors]] - [[#^counting-odd-factors|odd factors]]

Counting number of shared factors
?
- Given two numbers $a$ and $b$, we want to find the number of shared factors between the two
- Prime factorize the two numbers into exponential form
	- **Ex.** $2^33^25^2$ and $2^237^2$
- Find the factors they have in common
	- **Ex.** $2^23$
- Perform the [[#^counting-positive-factors|counting positive factors]] method
	- **Ex.** $(2 + 1) \times (1 + 1) = 3 \times 2 = 6$

Least common multiple with prime factorization
?
- Given two numbers $a$ and $b$, we want to find the least common multiple between the two numbers
- Prime factorize the two numbers into exponential form
	- **Ex.** $2^33^25^2$ and $2^237^2$
- Take the large terms from each exponential form to form a new number
	- **Ex.** $2^33^25^27^2 = 88200$

Three ringing bells
?
- Bell A rings every 12 seconds. Bell B rings every 15 seconds. Bell C rings every 20 seconds. if they all ring simultaneously at exactly the same time, how long will it take for them to ring simultaneously again?
	- Calculate the LCM of $12, 15, 20$

Unit digit
? ^unit-digit
- The unit digit is the digit in the ones place of the number
	- **Ex.** $28323$, unit digit is $3$
- You can derive the pattern of unit digits of $X^n$ by repeatedly taking the last digit of the previous result and and multiplying it by $X$
	- **Ex.** $3^n$
		- $3^1 = 3$
		- $3^2 = 9$
		- $3^3 = 27$
		- $3^4 = \dots1$ because $3 \times 7 = 21$
		- $3^5 = \dots3$ because $1 \times 3 = 3$
	- After you have the pattern you can answer questions like what's the unit digit of $3^{41}$
		- Divide the exponent by the number of times it repeats and find the remainder
			- **Ex.** $\dfrac{41}{4} = 10.25$, therefore remainder is $1$
		- The remainder is the exponent to use
			- **Ex.** 
				- Remainder of $1$ means we use the unit digit of $3^1$
				- Remainder of $0$ means we use unit digit of $3^4$
- Pattern of unit digits
	- $0^n$ → always 0 
	- $1^n$ → 1
	- $2^n$ → 2, 4, 6, 8, repeat
	- $3^n$ → 3, 9, 7, 1, repeat
	- $4^n$ → 4 6 repeat
	- $5^n$ → always 5
	- $6^n$ → always 6
	- $7^n$ → 7, 9, 3, 1 repeat
	- $8^n$ → 8, 4, 2, 6 repeat
	- $9^n$ → 9, 1 repeat
	- $10^n \to$ always 0

Quotient
?
- The result of division
	- **Ex.** $\dfrac{17}{5} = 3 \hspace{0.5em} R \hspace{0.5em} 2$
		- Quotient = $3$

Remainder
?
- Leftover from dividing a number with something that doesn't go evenly into it
	- **Ex.** $\dfrac{17}{5} = 3 R 2$
	- Remainder = $2$
- Remainder must always be **positive**
- For negative numbers, we have to pick a number **smaller** than the number as the quotient, and then calculate the remainder, which ensures it's positive
	- **Ex.** $\dfrac{-14}{4} = 4 \hspace{0.5em} R \hspace{0.5em} 2$
	- $4 \times 4 = -14 + 16 = 2$
- Remainder is usually relevant to the original problem, meaning we don't simplify the numbers
	- **Ex.** $\dfrac{3}{6} = 2 \hspace{0.5em} R \hspace{0.5em} 3$
	- We **do not** simplify the fraction into $\dfrac{1}{2} = 0 \hspace{0.5em} R \hspace{0.5em} 1$
- Remainder of $\dfrac{x}{10}$ is just the last digit of $x$

Remainder of $\dfrac{a^n}{b}$ when $b \leq 10$
?
- First, calculate the [[#^unit-digit|unit digit]] of $a^n$
- Then calculate the remainder of $\dfrac{\text{unit digit}}{b}$

Remainders and addition
?
- AKA modular arithmetic
- Given $\dfrac{17 + 12}{10}$
	- We can calculate the remainders of $17$ and $12$ separately and then add them together
- In formal terms
	- $(17 + 12) \text{ mod } 10 = ((17 \text{ mod } 10) + (12 \text{ mod } 10)) \text{ mod } 10$

Fraction
?
- $\dfrac{a}{b}$
	- Represent
	- $a =$ numerator
		- Must be an integer
	- $b =$ denominator
		- Must be an integer
		- Cannot be $0$
- Integers can be represented as a fraction
	- **Ex.** $3 = \dfrac{3}{1}$

Improper fraction
?
- If numerator of the fraction is greater than the denominator
- **Ex.** $\dfrac{9}{2}$

Simplifying fractions
?
- We can remove/add common factors from both numerator and the fraction to make an equivalent fraction
- **Ex.** $\dfrac{3}{6} = \dfrac{1}{2}$

Rational number
?
- Number that can be written as a fraction
- If it's represented as a decimal, it will have either no decimal places, a fixed number of decimal places, or a repeating set of decimal digits
	- **Ex.** $\dfrac{7}{4}, 3.\bar{32}$

Irrational number
?
- Numbers that are not rational
- **Ex.** $\sqrt{2},\pi$
- Properties
	- Sum of two irrational numbers $\to$ might be rational ($-\pi + \pi = 0$)
	- Product of two irrational numbers $\to$ might be rational ($0 \times \pi = 0$)
	- Sum of rational + irrational number $\to$ $0 + \pi = \pi$ must be irrational
		- Cannot remove all the the decimal parts of the irrational number without being a rational number itself

Mixed number
?
- Number represented as an integer + a fraction
- **Ex.** $3 \dfrac{2}{3} = 3 + \dfrac{2}{3}$
- Can be derived by simplifying improper fractions
	- Divide the numerator by the denominator, and write the integer to the left
	- Write the remainder as the new numerator
	- **Ex.** $\dfrac{11}{3} = 3 \dfrac{2}{3}$
- Can be converted back into an improper fraction
	- Multiply the integer by the denominator, and then add the numerator to find the new numerator
	- **Ex.** $3 \dfrac{2}{3} = \dfrac{11}{3}$

Adding/subtracting fractions
?
- Find the LCM of the denominators, and multiply it with both fractions

Multiplying fractions
?
- Multiply the numerators together to form the new numerator
- Multiply the denominators together to form the new denominator
- **NOTE:**
	- Before multiplying, you can simplify the fraction using factors from both fractions, since the result of multiplication ultimately creates a new fraction whose numerator = product of the previous numerators and denominator = product of the previous denominators
	- **Ex.** $\displaystyle \frac{\cancel{ 3 }}{\cancel{ 7 }} \times \frac{\cancel{ 49 } (7)}{\cancel{ 9 } (3)} = \frac{7}{3}$

Dividing fractions
?
- Flip the divisor fraction (the fraction you are dividing by)
- Then multiply the two fractions as normal
- **Ex.** $\displaystyle \frac{3}{2} \div \frac{2}{3} = \frac{2}{3} \times \frac{2}{3} = \frac{4}{9}$

Decimal system
?
- Common method for writing numbers with 10 digits
	- 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- Each decimal place represents a power of 10
	- $10^2$ → hundreds place
	- $10^1$ → tens place
	- $10^0$ → units place
	- $10^{-1}$ → tenths place
	- $10^{-2}$ → hundredths place
- Each time you multiply by $10$, the decimal place moves right
	- **Ex.** $3.4 \times 10 = 34$
- Each time you divide by $10$, the decimal place moves left
	- **Ex.** $3.4 \div 10 = 0.34$
- Other systems
	- Binary system
		- 0, 1
	- Hexadecimal system (16 characters)
		- 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F

Scientific notation
?
- Method of representing numbers as
	- $a \times 10^b$
		- $a =$ decimal number
			- Find this number by moving the decimal point right after the first non-zero digit
		- $b =$ an integer
			- This is the number of places you've moved the decimal place
- **Ex.** 
	- $335.38 = 3.3538 \times 10^2$
	- $0.007323 = 7.323 \times 10^{-3}$
	- $3.384 = 3.384 \times 10^0$

Numbers as powers of 10
?
- Can rewrite every number as powers of 10
- **Ex.** 
	- $36 = 3 \times 10^1 + 6 \times 10^0$
	- $177.3 = 1 \times 10^2 + 7 \times 10^1 + 7 \times 10^0 + 3 \times 10^{-1}$

Terminating decimal
?
- Fraction when converted into a decimal number has a fixed decimal portion

Non-terminating decimal
?
- Fractions when converted into a decimal number that goes on forever

Repeating decimal
?
- Decimal number who's decimal portion repeats
- Repetition is represents as a bar over the portion that repeats
	- **Ex.** $4.8\bar{6}$
- This means the number is a rational number

Checking if a fraction terminates or not
?
- Steps
	- Prime factorize the denominator
	- If the denominator is comprised of the factors of 10, which are 2 or 5
		- If the denominator has extra factors, try prime factorizing the numerator, which might let you cancel out the extra factors
- **Ex.** $\dfrac{28}{2^05^3}$ → terminates
- **Ex.** $\dfrac{28}{7 \cdot 2^3}$ → does not terminate

Convert repeating decimal to fraction
?
- Starts with $x = a$, where $a$ is the repeating number
	- **Ex.** $x = 0.\bar{34}$
- Multiply by some power of $10$ until the entire repeating portion is on the left
	- **Ex.** $100 x = 34.\bar{34}$
- Subtract this new equation by the previous equation, to cancel out the repeating portion
	- **Ex.** 
		- $99x = 34$
		- $x = \dfrac{34}{99}$

$\dfrac{x}{y} = 3.625$, where $x$ and $y$ are positive integers. What could be the remainder of $\dfrac{x}{y}$?
?
- Break decimal down into mixed fraction
	- $3 \dfrac{625}{1000}$
- Simplify the fraction
	- $3 \dfrac{5}{8}$
- The numerator is the remainder
- Any answer choice that is a multiple of the remainder is valid

Given an integer $x$ and $x + 1$, do the two integers share prime factors?
?
- No, integers that are one away from each other do not share any prime factors
	- Adding 1 creates another number that's multiple of 1
	- But all numbers are multiples of 1, and 1 isn't considered prime
- If it was $x + 2$, $x + 3$,  or any greater difference, then there could be the possibility of sharing factors