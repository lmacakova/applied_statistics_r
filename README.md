![magnifying glass over math's formulas](https://images.pexels.com/photos/3729557/pexels-photo-3729557.jpeg)
# Applied Statistics - Assessment
## Lucia Macakova

This is is my Assessment for the module Applied Statistics, as a student of Atlantic Technical University in the programme of Data Analytics. 

## The Purpose of Assessment:

* Describe the stochastic nature of real-world measurements.
* Source documentation to programmatically perform a statistical test.
* Select an appropriate statistical test to investigate a claim.
* Perform a statistical test on data.

## How to work with jupyter notebook problems.ipynb:
1.  Clone the repository with:
bash
```
git clone https://github.com/lmacakova/applied_statistics_r.git
cd applied_statistics_r
```
2. Create virtual environment and install dependences:
bash
```
python -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows PowerShell
.venv\Scripts\Activate.ps1

pip install --upgrade pip
pip install -r requirements.txt
```
3.  Open the notebook in VS Code or Visual Code and select Python (applied) as the kernel.

# Problems: 
## Problem 1: Combinations and Simulation

The Lady Tasting Tea experiment[^1] when 10 cups of tea are used, 3 cups have milk added first, 7 cups have tea added first, the cups are thoroughly shuffled so that they seemingly cannot be told apart. 

Tasks:
1.  Calculating the probability of randomly selecting exactly the 3 cups with milk added first.
2.  The simulation of the process 1,000 times to verify result.

Solution: I counted the probability of choosing certain number of cups with hypergeometric formula[^2] and made a simulation of random choosing 3 cups from 10 in 1,000. I found the results of probability from the simulation fluctuating, so I increased the number of trials to 1,000,000, to reach the theoretical values of probability.

## Problem 2: Normal Distribution

Task:
1.  Evaluating whether numpy.random.standard_normal() generates values from a true normal distribution[^3] by generating a sample of 100,000 values. 
2.  Using scipy.stats.shapiro()[^4] to test whether the sample comes from a normal distribution.  
3. Creating a histogram[^5] of sample and overlaying the probability density function (PDF)[^6] of the standard normal distribution on the histogram.

Solutions: I generated a sample of 100,000 values, and tested it with Shapiro-Wilk test. I chose Kolmogorov-Smirnov[^7] test to further prove the normal distribution of data. Than I created a histogram of data and describe characteristics of normal distribution of data.

## Problem 3: t-Tests

Tasks:
1.  Comparing the resting heart rates of smokers and non-smokers from sets containing resting heart rates for a sample of patients, along with whether they smoke or not. Calculating the t-statistic[^8] based on the data set, using Python without scipy or statsmodels. 
2. Comparing it to the value given by scipy.stats. Explain your work and list any sources used.

Solution: First I checked assumptions about samples, so test could be done correctly. Than I calculated t-statistic with Welch's method[^9], which can be apply when variance of samples are not equal.

## Problem 4: Type I Error

Tasks: 
1. Generating three samples with 100 values each with numpy.random.standard_normal()
2. Performing one-way anova on the three samples and counting whenever a type I error occurs.

Solution:

## Problem 5: Binomial Distribution
Tasks:
1.  Explain the binomial distribution to your colleagues. Write a note about it, using numpy and/or scipy to generate values and explain its properties. 
2. Use matplotlib to graphically enhance your explanations.

Solution:


Resources:\
[^1]:   https://en.wikipedia.org/wiki/Lady_tasting_tea
[^2]:   https://www.youtube.com/watch?v=uzN7U88KSx8
[^3]:   https://en.wikipedia.org/wiki/Normal_distribution
[^4]:   https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.shapiro.html#shapiro
[^5]:   https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.histhtml#matplotlib-pyplot-histd
[^6]:   https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html#scipy-stats-norm
[^7]:   https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.kstest.html#kstest
[^8]:   https://en.wikipedia.org/wiki/Student%27s_t-test
[^9]:   https://en.wikipedia.org/wiki/Welch%27s_t-test
[^10]:  https://en.wikipedia.org/wiki/Type_I_and_type_II_errors

Contact:\
Lucia Macakova\
email: G00439449@atu.ie


