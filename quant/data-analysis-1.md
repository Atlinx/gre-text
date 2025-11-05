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
	- Mode = $\{ 1, 2, 3 \}$

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
