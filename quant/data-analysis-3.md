# Data Analysis 3
#flashcards/quant/data-analysis-3

Event
?
- Something that hapepns

Probability
?
- A number from 0 to 1
	- Also represented as a fraction or a percentage
	- **Ex.** $P(A) = 0.25 = \dfrac{1}{4} = 25\%$
- AKA likelihood
- The probability of an outcome is
	- $$\huge \text{P(A)} = \frac{\text{successful outcomes}}{\text{total outcomes}}$$
- Probability describes how likely an **event** is to occur
	- **Ex.** $P(\text{coin heads}) = 0.5$
- The probability of all possibilities = 1 

Pulling marbles out of bag
?
- Probability of pulling a marble with a color $A$ out of a bag (even **without replacement**) will always be $\dfrac{\text{marble count}}{\text{total marbles}}$

Complement event
?
- The complete event is the event not happening
- Given an event $A$, its complement is denoted as $A^c$
- $$\huge P(A^c) = 1 - P(A)$$

Complete overlap events (Complete dependence)
?
- Two events are completely overlapping if one event can only happen if another event happens
- $$\huge P(A|B) = 1$$
	- Event $A$ is guaranteed to happen when event $B$ happens

Independence events spectrum
?
- Events lie on a spectrum
	- Mutually exclusive
		- $P(A \cap B) = 0$
		- $P(A \cup B) = P(A) + P(B) \leq 1$
	- A little dependent
	- Independent
		- $P(A \cap B) = P(A)P(B)$
		- $P(A \cup B) = P(A) + P(B) - P(A \cap B)$
	- Very dependent
	- Completely dependent (complete overlap)
		- $P(A \cap B) = \min(P(A), P(B))$
		- $P(A \cup B) = \max(P(A), P(B))$

Independent events
?
- Two events are independent if they happen simultaneously and they don't influence each other
- If two events are independent, then
- $$\huge \begin{align}
P(A \cap B) &= P(A)P(B) \\
P(A | B) &= P(A)
\end{align}$$
- **Ex.** Flipping heads ten times in a row with ten coin flips

Mutually exclusive events
?
- Two events are mutually exclusive if they cannot happen simultaneously
- $$\huge P(A \cap B) = 0$$
- **Ex.** Flipping heads and flipping tails in one coin flip
- If two events are mutually exclusive, then
	- $P(A \cup B) = P(A) + P(B) \leq 1$

$P(A \cap B)$
?
- $$\huge P(A \cap B) = P(A)P(B|A)$$
	- $P(B|A)$

$P(A \cup B)$
?
- $$\huge P(A \cup B) = P(A) + P(B) - P(A \cap B)$$
- If two events are mutually exclusive, then 
	- $$\huge P(A \cup B = P(A) + P(B))$$

$P(A \oplus B)$
?
- $$\huge P(A \oplus B) = P(A) + P(B) - 2 P(A \cap B)$$
- This means probability of $A$ XOR $B$
	- In other words, probability of $A$ or $B$, but not both

Probability and combinatorics
?
- **Ex.** Bob flips a coin 5 times. What's the probably he gets a head exactly 3 times?
	- $$\begin{align}
	\left( \frac{1}{2} \right)^5 \frac{5!}{3!2!} &= \frac{1}{32} \cdot \frac{5 \cdot 4}{2!}*  \\
	&= \frac{1}{32} \cdot 5 \cdot 2 \\
	&= \frac{1}{32} \cdot 10 \\
	&= \frac{5}{16} = 0.3125
	\end{align}$$
	- We first find the probability of the specific outcome
	- Then we find all permutations of that outcome

At least/most questions
?
- If we have an at least or at most question, we can negate the event, and then calculate $1 -$ probability of the negated event
	- Use this method if the negated event has less cases we have to worry about
- **Ex.** Vivek flips a coin six times. What's the probability he gets at least one heads?
	- $$\begin{align}
		P(\text{heads} \geq 1 ) &= 1 - P(\text{heads} = 0) \\
		&= 1 - 0.5^6 \\
		&= 1 - \frac{1}{64} \\
		&= \frac{63}{64} = 0.984375
		\end{align}$$

Given probability
?
- $$\huge \begin{align}
	P(A | B) &= \frac{P(A \cap B)}{P(B)} \\
	&= \frac{\text{successes of } A \text{ and } B}{\text{successes of } B}
	\end{align}$$
	- Probability of event $A$ happening given event $B$ has happened
- **Ex.** Ben flips a fair coin four times. Given that the coin lands on heads at least twice, what's the probability the coin lands on heads exactly three times?
	- Given information = $\text{heads} \geq 2$
	- Interested event = $heads = 3$
	- Break 4 coin flips down into cases, and find which ones satisfy the given information
	- Then find then find number of combinations of that event occurring (using permutations)
		- Case 1: TTTT $\to$ ignore
		- Case 2: TTTH $\to$ ignore
		- Case 3: TTHH
			- $P(\text{heads} = 2) = \displaystyle 0.5^4 \left( \frac{4!}{2!2!} \right) = 0.375$
		- Case 4: THHH
			- $P(\text{heads} = 3) = \displaystyle 0.5^4 \left( \frac{4!}{1!3!} \right) = 0.25$
		- Case 5: HHHH
			- $P(\text{heads} = 4) = \displaystyle 0.5^4 \left( \frac{4!}{4!} \right) = 0.0625$
	- $P(\text{heads} \geq 2) = 0.375 + 0.25 + 0.0625 = 0.6875$
	- Then, solve for the probability of the given event
		- $$\begin{align}
			P(\text{heads} = 3 \mid \text{heads}\geq 2) &= \frac{P(\text{head} = 3 \cap \text{head} \geq 2)}{P(\text{head} \geq 2)} \\
			&= \frac{0.25}{0.6875} \\
			&= \frac{4}{11} \\
			&\approx 0.36363
			\end{align}$$

Expected value
?
- The expected value of an event is the sum of all the possible values weighted by their likelihood
	- This gives us the "average" value we can expected from running this event many many times 
- $$\huge E[X] = \sum_{x} P(x) \cdot x$$
Birthday paradox
?
- At least how many random people do you need to put into a room so the probability that at least two people share a birthday is $\geq 50\%$?
- Answer is $23$
- $$\huge \begin{align}
f(x) &= \left( \frac{1}{365} \right)^x \left( \frac{365!}{(365 - x)!} \right) \\
f(23) &= \left( \frac{1}{365} \right)^{23} \left( \frac{365!}{(365 - 23)!} \right) \approx 0.4927 \\
f(40) &\approx 0.108 \\
f(48) &\approx 0.0394
\end{align}$$
	- $f(x) =$ probability of nobody sharing a birthday given $x$ people
- At $x = 23$, $P(\text{not sharing birthday}) = 1 - 0.4927 = 0.5073$

Distributions of data
?
- Frequency distribution
	- Shows how many people/things fall into a certain category
	- Can be shown in a histogram
	- ![[Pasted image 20251105182520.png]]
- Probability distribution
	- Shows the likelihood of a value occurring
	- Sum of probability distribution is $1$
	- ![[Pasted image 20251105182710.png]]

Skewness
?
- Skewness describes the shape of a distribution
- Symmetrical
	- The distribution is symmetrical
	- mean = median = mode
- Right skew (Positive skew)
	- The tail of the distribution is on the right
	- mode < median < mean
- Left skew (Negative skew)
	- The tail of the distribution is on the left
	- mean < median < mode
- ![[Pasted image 20251105183057.png]]
- The average follows the tail
	- Then the median follows
	- Finally the mode follows

Normal distribution
?
- Distribution with a bell-shaped curve
	- More data closer to the mean
- As a random sample becomes very large, it's going to exhibit a normal distribution
- Median and mean are approximately equal in a normal distribution, and located at the center of the symmetry
- If the normal distribution is a probability distribution, then
	- Area under curve $= 1$
- Mean standard deviation effects
	- As mean increase
		- Graph shifts rightward
	- As standard deviation increases
		- Graph becomes flatter and wider

68-95-99 rule
?
- AKA empirical rule
- 68% of datapoints lie $\leq 1$ standard deviations from the mean
- 95% of datapoints lie $\leq 2$ standard deviations from the mean
- 99% of datapoints lie $\leq 3$ standard deviations from the mean
- Starts from the left half of the normal distribution
	- 2% datapoints
	- 13.5% datapoints
	- 34% datapoints
		- 15% datapoints $\leq 0.5$ lie on left half
		- 19% datapoints $\leq 0.5$ lie on right half
		- May need this for problems that require more granular points