# Data Analysis 2
#flashcards/quant/data-analysis-2

How does shifting/scaling distributions affect standard deviation and mean?
?
- If we add $a$ to all data
	- Mean shifts
	- Standard deviation does not change
- If we scale data by $a$
	- Mean may shift
	- We scale the standard deviation by $a$

Standardization
?
- Defining each datapoint based on the number of standard deviations away from the mean
	- This allows us to compare different distributions
	- Standardized data has
		- $\sigma = 1$
			- Standard deviation of $1$
		- $\mu=0$
			- Mean of $0$
- Scaling a distribution **does not always** increase standard deviation
	- **Ex.** If all elements of the distribution have the exact same value
		- Scaling would only move the mean
- **Ex.**
	- Given a list $[1, 2, 3, 4, 5]$
	- Mean: 
		- $\dfrac{1 + 5}{2} = 3$
		- Since we have evenly spaced set, median = mean
	- Standard deviation: 
		- $\displaystyle \sigma = \sqrt{ \frac{1}{5} ((-2)^2 + (-1)^2 + 0^2 + 1^2 + 2^2) } = \sqrt{ 2 } \approx 1.414$
	- Standardizing the dataset:
		- $\displaystyle \frac{-2}{1.414} = -1.414$
		- $\displaystyle \frac{-1}{1.414} = -0.707$
		- $\displaystyle \frac{0}{1.414} = 0$
		- $\displaystyle \frac{1}{1.414} = 0.707$
		- $\displaystyle \frac{2}{1.414} = 1.414$
	- We are left with the list
		- $[-1.414, -0.707, 0, 0.707, 1.414]$

Set
?
- Unordered collection of unique numbers
- Written as $\{ 1, 2, 4 \}$
- Objects in the set are called elements/members
- **Ex.**
	- $\{ 1, 2, 3 \} = \{ 2, 3, 1 \}$
	- $\{ 4, 5, 6, 6 \} = \{ 5, 4, 6 \}$
- A set with 2 or more elements must have standard deviation $> 0$ because every element must be unique
- Size of a set $A$ is denoted by $|A|$

Empty set
?
- Set with no elements
- AKA null set
- Denoted by $\emptyset$

List
?
- Ordered collection of numbers
- Duplicates are allowed
- Written as $[ 1, 2, 3 ]$
- **Ex.**
	- $[ 1, 2, 3 ] \neq [ 3, 1, 2 ]$
	- $[ 1, 2, 3 ] \neq [ 1, 2, 2, 3 ]$
- A list with two or more elements could have standard deviation $=0$ because elements could be all the same

Set intersections
?
- Intersection of two sets $A$ and $B$ is denoted as
	- $A \cap B = C$
- The new set $C$ is comprised of elements in both $A$ and $B$

Set union
?
- Union of two sets $A$ and $B$ is denoted as
	- $A \cup B = C$
- The new set $C$ is comprised of all elements from $A$ and all elements from $B$

Mutually exclusive sets
?
- Two sets $A$ and $B$ are mutually exclusive if they have no intersection
	- $A \cap B = \emptyset$

Subset
?
- A set $A$ is a subset of another set $B$ if all elements of $A$ are inside of $B$
- Denoted by $A \subseteq C$
- AKA complete overlap

Complement of set
?
- The complement of a set is made up of all the elements that are not in the set
- $$\huge \begin{align}
	A^c &= \text{U} - A \\
	|A^c| &= |\text{U}| - |A| \\
	|U| &= |A| + |A^c|
	\end{align}$$
	- $A =$ a set
	- $A^c =$ the complement of set $A$
		- Everything not in $A$
	- $\text{U} =$ set of all possible elements
		- The total

Inclusion-exclusion principle
?
- Formula for calculating the size of the union of one or more sets
	- Add the size of the union all elements, remove the size of 2-group unions, add the size of 3-group unions, etc.
- Union of two sets
	- $$\huge \begin{align}
	|A \cup B| &= |A| + |B| - |A \cap B|
	\end{align}$$
	- A more useful version is
		- $$\huge |U| = |A| + |B| + |C| - |S_{=2}| + |S_{\text{none}}|$$
		- $U =$ set containing all elements
		- $S_{=2} =$ set of elements that are part of exactly two groups $AB$
		- $S_{\text{none}} =$ set of elements that are not in any group
- Union of three sets
	- $$\huge \begin{align}
	|A \cup B \cup C| &= |A| + |B| + |C|  \\
	&- |A\cap B| - |A\cap C| - |B \cap C|  \\
	&+ |A \cap B \cap C| \\ \\
	\end{align}$$
	- A more useful version of the 3 set formula is
		- $$\huge \begin{align}
		|U| &= |A| + |B| + |C|  \\
		&- |S_{\text{=2}}|  \\
		&- 2 |S_{\text{=3}}| \\
		&+ S_{\text{none}}
		\end{align}$$
		- $U =$ set containing all elements
		- $S_{=2} =$ set of elements that are part of exactly two groups $AB, BC, CD$
		- $S_{=3} =$ set of elements that are part of exactly three groups
		- $S_{\text{none}} =$ set of elements that are not in any group

- Union of $n$ sets
	- $$\huge \begin{align}
		|S_{\cup}| &= |S_{1}| -|S_{2}| + |S_{3}| - \dots + |S_{n}|
		\end{align}$$
	- $S_{\cup} =$ union of all n sets
	- $S_{n} =$ set of the union of $n$ sets
		- **Ex.**
			- $S_{1} =$ set of the union of just one set $= A + B + C + \dots$
			- $S_{1} =$ set of the union of 2 sets $= (A \cup B) + (B \cup C) + (C \cup D) + \dots$
			- $S_{2} =$ set of the union of 3 sets $= (A \cup B \cup C) + (A \cup C \cup D) + \dots$
- ![[Pasted image 20251105110459.png]]

Set problem-solving methods
?
- Venn diagram
- Table
- Formula $\to$ Inclusion-exclusion principle

Venn diagram (Set solving method)
?
- Graphical representation of two or more sets
- Steps
	- Draw a circle for each set
	- Each circle should intersect all of the previous circles
	- The outside area is "neither"
- ![[Pasted image 20251105110412.png]]

Frequency table (Set solving method)
?
- Make a table and label the rows with one category, and label the columns with the other category
- Good for complex problems
- Add totals to the ends
- ![[Pasted image 20251105110404.png]]

Counting choices
?
- To find all possible combinations of a set of choices, multiple the amount of options at each choice together
	- **Ex.** You have 3 choices for rice, 3 choices for protein, and 2 choices for tortillas for your burrito
		- $3 \cdot 3 \cdot 2 = 18$ possible combinations of burritos
- One of the options can be **doing nothing**
	- **Ex.** An ice cream shop has four flavors of ice cream and four optional toppings. How many different ice creams can be made?
		- $4 \cdot 2^4 = 64$
		- There are $4$ flavors
		- There are $4$ toppings
			- For each topping, you can either 
				- Include the topping
				- Exclude the topping
			- Therefore you have $2$ options for each topping

Combinatorics conditional choices
?
- If a choice is conditional, you can break it down into two or more mutually exclusive events that you then sum together
- **Ex.** Phone numbers have ###-###-#### format. The first 3 digits specifies an area code. The remaining 7 digits specifies a unique identifier. First digit of the 7-digit identifier must be from 2-9 inclusive. The two digits immediately after cannot both be 1.
	- How many unique identifiers are there for an area code of 103?
	- 7 digit identifier combos:
		- $8 \to$ First digit from 2-9 inclusive ($9 - 2 + 1 = 8$)
		- $1 \cdot 9 + 9 \cdot 10$
			- Here we have a conditional choice for the next 2 digits, therefore we break the choices down into two mutually exclusive cases that we then sum together
			- $1 \cdot 9 \to$ Choose $1$, then choose any digit except $1$ ($9$ options)
			- $9 \cdot 10 \to$ Choose anything except $1$, then choose any digit
		- $10^4 \to$ Remaining 4 digits can be any digit
	- $8 \cdot (1 \cdot 9 + 9 \cdot 9) \cdot 10^4 = 7,200,000$

$n!$ permutation
?
- $n!$ is the number of ways to permute $n$ objects
- Explanation
	- Imagine we have $n$ slots to put the $n$ objects in
		- For the $1$st object, we have $n$ slots to choose from
		- For the $2$nd object, we have $n - 1$ slots to choose from
			- One slot is already taken by the first object
		- For the $3$rd object, we have $n - 2$ slots to choose from
		- $\dots$
		- For the $nth$ object, we have $1$ slot to choose from
	- If we multiply these choices together, we get
		- $n \cdot (n - 1) \cdot \dots 2 \cdot 1 = n!$

Permutations
?
- Number of ways that things are arranged
- Order matters
- **Ex.** Choosing 3 people from group of 4, order matters
	- $$\begin{align}
ABC \neq BAC \neq CBA \\
DBC \neq BDC \neq CBD \\
ABC \neq DBC
\end{align}$$
- Number of permutations is always greater than number of combinations
- Formula
	- $$\huge nPr = \frac{n!}{(n - r)!}$$
		- $r =$ size of group
		- $n =$ total number of unique elements to pick from
	- Explanation
		- $n! =$ total number of ways to permute $n$ objects
		- $(n - r)! =$ number of ways to permute the objects that are not selected $(n - r)$
			- We divide by this to remove these permutations from the total count

Combinations
?
- Order does not matter
- Number of ways that things are arranged
- **Ex.** Choosing 3 people from group of 4, order does not matter
	- $$\begin{align}
ABC = BAC = CBA \\
DBC = BDC = CBD \\
ABC \neq DBC
\end{align}$$
- Formula
	- $$\huge {n \choose r} = nCr = \frac{n!}{r!(n - r)!}$$
		- $r =$ size of group
		- $n =$ total number of unique elements to pick from
	- Explanation
		- $n! =$ total number of ways to permute $n$ objects
		- $(n - r)! =$ number of ways to permute the objects that are not selected $(n - r)$
			- We divide by this to remove these permutations from the total count
		- $r! =$ number of ways to permute the $r$ objects we selected
			- We divide by this to remove these permutations from the total count
		- We're left with the total count of choosing $r$ objects from a set of $n$ objects, without double counting permutations of $n$
		- We can also frame choosing as
			- $$\huge nCr = \frac{nPr}{r!}$$

Permutations with restrictions
?
- Some permutation problems have restrictions
- **Ex.** Five friends $A, B, C, D, E$ go to a movie.
	- $B$ must sit in the middle. How many different ways can we arrange the seats?
		- $4 \cdot 3 \cdot 1 \cdot 2 \cdot 1 = 24$
			- $4$ options for the first seat
			- $3$ options for the second seat
			- $1$ option for the middle seat
	- $E$ must sit on either end
		- $\text{E's choice} \cdot \text{remaining} = 2 \cdot (4 \cdot 3 \cdot 2 \cdot 1) = 2 \cdot 24 = 48$
			- $2$ options for $E$ to sit on either end
			- Permute the remaining $4$ seats
	- $A$ must sit next to $B$
		- $\text{permute AB} \cdot \text{permute groups}= 2 \cdot (4 \cdot 3 \cdot 2 \cdot 1) = 48$
		- $2$ ways to permute $A$ sitting next to $B$ ($AB$, $BA$)
		- We then treat $AB$ as a single group and the seats they're sitting in as one seat
		- We now have $4$ seats to distribute to $4$ people, so we permute $4$
	- $A$ cannot sit next to $B$
		- $\text{all combos} - \text{A next to B} = 5! - (2 \cdot 4!) = 72$

Permutations with repeats
?
- Some permutations have identical objects, so we need to remove duplicates
- **Ex.** How many ways can the word FOOD be arranged?
	- $\dfrac{4!}{ 2!} = 4 \cdot 3 = 12$
	- We have $4$ letters
	- We have a group of $2$ identical Os
		- Therefore we want to divide by the number of ways we can permute the Os to remove them from the final total
- **Ex.** How many ways can the word MISSISSIPPI be arranged?
	- $\dfrac{11!}{4!2!4!} = 34650$
	- $11$ letters total
	- $4$ Is
	- $2$ Ps
	- $4$ Ss
- **Ex.** How many ways can letters from TEXTBOOK be arranged if all vowels must be together at front of word and all consonants at end?
	- $$\huge \frac{3! \cdot 5!}{2! \cdot 2!} = 180$$

Combinatoric car route problem
?
- Anjali is driving from her house to the store and can only go North or East. How many different routes can she take?
	- The stores is 4 blocks north and 3 blocks east.
- Solution
	- $\dfrac{7!}{4!3!} = 35$
	- It always takes $4$ north movements and $3$ east movements to get to the store
	- We permute $7$ total symbols ($4$ north and $3$ east), and divide by the size of each group to remove double counting

Permutations in a circle
?
- When people are put in a circle, any rotation of that ordering is considered the same permutation
- $$\huge \text{permutation}_{\text{circle}} = \frac{n!}{n} = (n - 1)!$$
	- There are $n$ ways to rotate a single permutation, therefore we divide by that to remove it from the count
- **Ex.** Given three friends $A, B, C$, how many ways can you sit the three in a circle?
	- $ABC = CAB = BCA$
	- We know there are $3$ ways to rotate the three friends, so we do
	- $\displaystyle \frac{3!}{3} = 2! = 2$

Combination patterns
?
- If you plot the number of combinations for each group size $r$ from $1$ to $n$
	- If $n$ is **even**, the peak will occur at the middle
		- This is because we have $r = [0, n]$ therefore $r$ has $n + 1$ possible values and $n + 1$ is odd
	- If $n$ is **odd**, then the peak is 2 elements in the middle
		- This is because we have $r = [0, n]$ therefore $r$ has $n + 1$ possible values and $n + 1$ is even
- The smallest number of combinations would be for $r = 0$ or $r = n$
- ![[Pasted image 20251105132220.png]]
	- **Ex.** At $r =\dfrac{n}{2}$, we have the largest number of combinations
- Plotting the possible $r$ values for $nCr$ will produce layer $r$ of **pascal's triangle**
	- Assume the first layer of the triangle is layer $0$

Permutation vs. combinations
?
- Permutations
	- Order
	- Arrange
	- Rankings
	- Sequences of letters or spelling
	- Sequence of visits
	- Seating arrangements
- Combinations
	- Groups
	- Sets
	- Subsets
	- Selecting team members or people to form a group