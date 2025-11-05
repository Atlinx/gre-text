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

