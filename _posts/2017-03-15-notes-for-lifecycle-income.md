---
layout: post
title: "Notes For Life Cycle Income"
categories: income lifecycle
description: "Notes For Life Cycle Income"
excerpt_separator: <!--more-->

---
## Conclusions
Q1: Howmuch lifetime inequality exists in the United States today ? * A1: A lot! (relative to our prior.)

Q2: Howmuch has average lifetime income changed since the 1950s ? 
* A2: For three-quarters of population: None.

Q3: Howmuch has lifetime inequality changed since the 1950s ?
* A3: Lots of increase within gender groups. Little increase overall (thanks to shrinking lifetime gender gap!)
* A4: Most differences in income occur before age 25. 

## DATA

1. SSA Master File
	SSA Master Earnings File: Population data from1978 to 2013 – Wage/Salary income. No top coding. (SE income also available. Non-top-coded after 1993). – All workers in all 
	sectors. – Lifetime income for 6 cohorts. We combine them all in one.

	`Question: is there top-coding? Is there a cut-off?`

	Answer [here](https://www.ssa.gov/policy/docs/ssb/v69n3/v69n3p29.html) under "limitations"
	> Foremost, earnings data were first collected for the sole purpose of computing Social Security benefits. In the earlier years, only data on earnings up to the OASDI-taxable maximum were collected because any earnings over this amount did not factor into the benefit formula. 

2. CWHS Sample: 
	1% nationally representative panel from 1957 to 2013 (57 years). – Wage/Salary Income. Imputed above SSA taxable limit. – Commerce and Industry workers. 70% of labor force. – Lifetime (31 year) income for 27 cohorts.

Two samples:

- Social Security Administration records

- 57 years of data.

– Sample 0: All U.S. born individuals with an SSN between ages 25 and 55 (alive). Youngest full cohort turned 55 in 2013. 

– Baseline sample: Individuals with: Y Ymin = $1650£31 (in 2012 dollars) and oe have non-trivial income (exceeding Ymin) in 15 out of 31 years

- Uses a 1% sample of the SSA master file. Fitered for commerce and industry. Represents roughly 70% of private sector employment in 20014. 

- No discounting applied

### Not Working
Lots of people are not working. What can't the CPS tell us that this data tell us? Data show that nearly 27 percent of people who make more than 10k work less than 20 years in their lives. 

![notworking]({{site.baseurl}}/imgs/notworking.png)

Not working has real costs. And the curve is very steep. Not working 6 years on average costs people $30k annually.

![notworking]({{site.baseurl}}/imgs/notworking-costs.png)

### For most men, lifetime Income Has Fallen

```Lifetime income == 1/31 * sum(income from age 25-55).``` 

> Perhaps more strikingly, more than three-quarters of men have experienced no rise in their lifetime income, despite the fact that the U.S. economy has grown by more than 30% during this time.

Caveat:
>  Our data set does not contain individual-level information on non-wage benefits, but we use the NIPAs to obtain an upper bound on the growth of such benefits. Incorporating the growth in these benefits mitigates but does not overturn the results.

![men]({{site.baseurl}}/imgs/batchart-men.png)

You can see the decline in incomes for 25 yr olds after 2000. It's mirrored as the cohorts age. The mirroring between the pink and blue dots is interesting because it suggests that 
1. The bulk of the average persons income gains occur early in the first 10 years of their career. 
2. But also those changes are highly anchored to what you made when you were 25. 

So if you made a lot relative to other cohorts when you were 25, those gains will carry on with you when you're 35. Researchers explain that this little fact explains lots of variation what people typically make their entire lives. 

I think the worthy frame here is the average joe. While Bill Gates or coding academy graduates may go from making very little money to alot of money, income in a bland, normal job is more graduated than that. Your earnings slowly accumulated.

### The two periods of lifecycle income growth: 

1957-1967: Average lifetimes incomes grew 21.9%/ median grew 12.3%

1967-1983: Average lifetimes incomes grew 1.5%/ median fell <1%

Found that income has fallen. Why? Perhaps cohorts born after 1970s spend more of their working lives during the slow growth years of 2000 and the Great Recession.


Now let's move on to women.

![women]({{site.baseurl}}/imgs/batchart-women.png)

What's interesting is how compressed these charts are. It suggest for women 25 at in 1960, approximately women born in 1935 didn't see much of a rise in income their entire lives. They could expect to see 10k in income growth their entire lives. Most of the income gains for women were generational. Women age 25 in 1980 earned $7k more than women the same age who were born in 1960. 

You can see that women entering the workforce in the late 90s started to break through. The chart fanning out suggests that their incomes started to rise much more rapidly than women in generations past. 

It's not coincidental that this spread started to take places in the mid 70s, when women birth control started to become common among women age 25 and up.

### Inequality

This is an interesting statement:

``` Cross-sectional measures of tax burden understates the lifetime burden by 2–4% for median worker. ```

1. Suggests that people throughout their lives earn more than we thought. How do people measure lifetime income with cross sectional measures. Is he talking about synthetic cohorts?

2. 
> a 25-year-old man who was at the top decile of the income distribution of his cohort in 1968 had income that was 3.3 times (P90/P10 = e1.2) the income of a man who as in the bottom decile. By the time of the last cohort, those who turned 25 in 2012, this ratio had risen rose from 3.3 to 9.0. This is a remarkable 2.7 fold rise in the P90/P10 ratio, which is higher than the total rise in the cross-sectional P90/P10 ratio for men, which went up from 4 to 10, for a rise by 2.5 fold.34

### Share of the pie by gender. 

For cohorts 1955-1983, men have made roughly 80% and women had made 20% of all the lifetime money. Throughout the lifetime of each cohort. 

## My observations

* Today, the top 10 percent of 25-year-olds makes 9 times more than the bottom 10 percent. Traditionally, the top 10 percent made 3.3 more than the bottom 10. **(How are these people classified? by lifetime income?)**

* We can see inequality play out, not only over time, but through the course of a life. 

* Two people born the same year, can lead to different paths.

* Most of the typical person incomes are made between 25 and 35
* Womens incomes in the 60s and 80s are largely dependent on when they entered the labor market. 
* Two interesting things happened. Starting in the 70s, the charts start to spread out. The spread is suggestive of careers developing (see Claudia Goldin/Francine Blau) and women using the pill (also Goldin)
percent.  
* Incomes for young men have dropped off for young men, but they have held for women.

## Takeaways

1. What's most striking are the bat charts, by far. It's amazing to see that data in such detail. 
2. Early incomes gains are your biggest gains. They are persistent.  
3. Dropping out of the workforce is costly. The curve is very steep. 
4. Earnings for 25 year olds have dropped off. Incomes, in fact, were better then. 



