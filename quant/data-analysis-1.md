# Data Analysis 1
#flashcards/quant/data-analysis-1

Bar graph
?
- Compares amount of single variable

Histograms
?
- Shows frequency information in buckets
- Shows distribution of data

Segmented bar chart
?
- Datapoints are overlayed on top of each other

Table
?
- Can shows frequency of value 

Pie chart
?
- Compares relative amounts
- Often used for frequencies or percentages

Scatterplot
?
- Plotting datapoints with two variables
- Can then find a line of best-fit or trend line
- 

Line graph
?
- Trend over time

Measures of central tendency
?
- Mean
	- Tend to be skewed by outliers
	- Average of all the datapoints
- Median
	- Resistant to outliers
	- Middle of the datapoints
- Mode
	- Resistant to outliers
	- Most frequent value in the datapoints

Mean
?
 - $$\huge \text{mean} = \frac{x_{0} + x_{1} + \dots + x_{n}}{n}$$
	- Tend to be skewed by outliers
	- Average of all the datapoints
- Sometimes you want to manipulate the sum directly as a variable
- **Ex.** 
	- $\displaystyle \frac{s_{1}}{5} = 10$
	- $s_{1} = 50$

Median
?
- Resistant to outliers
- Middle of the datapoints after they're sorted from low to high
	- If there are an odd number of datapoints
		- Take the middle of the datapoints
	- If there is an even number of datapoints
		- Take the average of the middle 2 datapoints 
- Given consecutive sequence of numbers that increase by a fixed multiple of $m$, just take the average of the first and last number
	- **Ex.** Median of multiples of 3 from 1 to 50
		- $\displaystyle \frac{3 + 48}{2} = \frac{51}{2} = 25.5$

Mode
?
- Resistant to outliers
- Most frequent value in the datapoints
	- **Ex.** $1, 2, 3, 3, 5$
	- Mode = $3$
- If there are multiple values that share the highest frequency, the mode is then defined as a set that contains these multiple values
	- **Ex.** $1, 1, 2, 2, 3, 3$
	- Mode = $[ 1, 2, 3 ]$

Median = mean relationship
?
- Median = mean
	- By accident
	- If dataset is evenly spaced
		- **Ex.** $3, 4, 5, 6, 7$
		- Median = mean = 5
	- If dataset is symmetrical
		- **Ex.** $3, 4, 6, 9, 9, 12, 14, 15$
		- The change from 1st to 2nd element is the same as the change from the last to second to last element
			- ![[Pasted image 20251104232147.png]]
		- Median = mean = 9 

Weighted mean
?
- Like average by each number has a weight to it
- **Ex.**
	- Given the following frequency table
	- Number: 3 Freq: 1
	- Number: 7 Freq: 5
	- Number: 11 Freq: 3
	- Total freq = 9
	- $$\frac{3 * 1 + 7 * 5 + 11 * 3}{9} = \frac{71}{9} \approx 7.889$$
		- The unit is measured in the number

Quartile
?
- Divides data into four even groups
	- Each group should contain 25% of the data
- Boundaries
	- **Min**
	- Q1
	- **Q2 Median**
	- Q3
	- **Max**
- Groups
	- Quartile 1 is between min and Q1
	- Quartile 2 is between Q1 and Q2
	- Quartile 3 is between Q2 and Q3
	- Quartile 4 is between Q3 and max
- Steps to finding quartiles
	- Find halfway point and make boundary
		- If boundary is on element, then exclude this element from future quartiles
		- If boundary is between two numbers, then take the average of the two numbers as the boundary
	- Find halfway points from start to median and from median to start
		- If boundary is on element, then exclude this element from future quartiles
		- If boundary is between two numbers, then take the average of the two numbers as the boundary
- ![[Pasted image 20251105002804.png]]

Percentiles
?
- Splitting data into 100 groups
- If some is in the $n$th percentile, then they are better than $n$ people
- **Ex.**
	- $0^{th}$ percentile $\to$ Better than 0% (no one)
	- $1^{th}$ percentile $\to$ Better than 1% of people
	- $99^{th}$ percentile $\to$ Better than 99% of other people
- Cannot get $100^{th}$ percentile, because that would mean being better than every in the dataset, including yourself

Measures of dispersion
?
- Measures how "spread out" data is
- Types
	- Range
	- Interquartile range
	- Standard deviation

Range
?
- $$\huge \text{range} = \text{max} - \text{min}$$
Interquartile range
?
- $$\huge \text{interquartile range} = Q_{3} - Q_{1}$$

Standard deviation
?
- Population formula
	- $$\huge \sigma = \sqrt{ \frac{1}{N} \sum_{i=1}^N (x_{i} - \mu)^2 }$$
		- $\sigma =$ standard deviation of the population
		- $x_{i} =$ datapoint $i$
		- $\mu =$ average/mean of all the datapoints in the entire population
		- $N =$ total number of datapoints in the entire population
- Sample formula
	- $$\huge s = \sqrt{ \frac{1}{n - 1} \sum_{i=1}^n (x_{i} - \bar{x})^2 }$$
		- $s =$ standard deviation of the sample
		- $x_{i} =$ datapoint $i$
		- $\bar{x} =$ average/mean of all the datapoints in the sample
		- $n =$ total number of datapoints in the sample
	- Sample standard deviation is generally larger than the population standard deviation
- Measures the "average" of how far points are away from the mean
	- It's squared to give more weight to farther values
- You can eyeball standard deviation by looking at how much each value deviates from the mean
	- **Ex.** $[ 1, 100, 999 ]$ vs. $[ 99, 100, 101 ]$
		- The first step clearly has a larger standard deviation than the second set
	- Cases
		- All same numbers in dataset
			- **Ex.** $[ 3, 3, 3 ]$
			- $$\huge \sigma = 0$$
		- Exactly two numbers (or two sets of identical numbers) in dataset
			- **Ex.** $[ 2, 2, 4, 4 ]$
			- $$\huge \displaystyle \sigma = \frac{a + b}{2} - a$$
				- $a =$ lower number
				- $b =$ higher number
- **NOTE:**
	- If we have these two lists: $[1, 3], [1, 2, 3]$
		- The standard deviation for the first list is $1$
		- The standard deviation for the second list is **lower** than $1$
			- This is because in the second list we have an element whose standard error is $0$

Outliers
?
- Datapoints that differ significantly from most other datapoints
	- **Ex.** "Extreme" values on the outskirts of the distribution
- Outliers can skew the dataset 
	- Affects
		- Range
		- Average
	- Minimal affect on
		- Interquartile range
		- Median

5 number summary
?
- Summarizes a distribution using 5 numbers:
	- Min
	- Q1
	- Q2 (median)
	- Q3
	- Max

Boxplot
?
- Plots 5 number summary on a number line
- Steps
	- Label min, Q1, Q2, Q3, max
	- Draw a box between Q1 and Q2, and Q2 and Q3
	- Draw a line (whisker) between min and Q1, and Q3 and max
- ![[Pasted image 20251105004555.png]]