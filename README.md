![A futuristic financial interface on a dark blue background, with blue and violet 3D bar charts and overlaid line graphs that illustrate stock market or fintech data trends.](https://unsplash.com/photos/concept-of-stock-market-and-fintech-data-analysis-blue-and-violet-digital-bar-charts-over-dark-blue-background-futuristic-financial-interface-3d-rendering-LaU3HadwEeE)
# Applied_statistics
## Problem 1: Combinations and Simulation

The Lady Tasting Tea experiment[^1] when 10 cups of tea are used, 3 cups have milk added first, 7 cups have tea added first, the cups are thoroughly shuffled so that they seemingly cannot be told apart. 

Tasks:
1.  Calculate probability of randomly selecting exactly the 3 cups with milk added first.
2.  Then simulate the process 1,000 times to verify result. Clearly explain your reasoning and code.

Solution:


## Problem 2: Normal Distribution

Task:
1.  Evaluate whether numpy.random.standard_normal() generates values from a true normal distribution[^2] by generating a sample of 100,000 values. 
2.  Then use scipy.stats.shapiro() to test whether the sample comes from a normal distribution. Explain the test results and output clearly. 
3. Create a histogram of sample and overlay the probability density function (PDF) of the standard normal distribution on the histogram. Clearly explain your reasoning and code.

Solutions:


## Problem 3: t-Tests

Tasks:
1.  Comparing the resting heart rates of smokers and non-smokers from dataset containing resting heart rates for a sample of patients, along with whether they smoke or not. Calculate the t-statistic based on the data set, using Python without scipy or statsmodels. 
2. Comparing it to the value given by scipy.stats. Explain your work and list any sources used.

Solution:


## Problem 4: Type I Errors

Tasks: 
1.  Estimating the probability of committing a type I error in specific circumstances. To begin, create a variable called no_type_i and set it to 0. Now use a loop to perform the following test 10,000 times.
Use numpy.random.standard_normal() to generate three samples with 100 values each.
2. Perform one-way anova on the three samples and add 1 to no_type_i whenever a type I error occurs.
Summarize and explain your results.

Solution:

## Problem 5: Binomial Distribution
Tasks:
1.  Explain the binomial distribution to your colleagues. Write a note about it, using numpy and/or scipy to generate values and explain its properties. 
2. Use matplotlib to graphically enhance your explanations.

Solution:


Resources:
[^1]:   https://en.wikipedia.org/wiki/Lady_tasting_tea 
[^2]:   https://en.wikipedia.org/wiki/Normal_distribution



