# Capstone_1_Cancer
1st capstone: research proposal on cancer morbidity trends


# Overview

Our country spends the most on healthcare of any industrialized country, with the least relative return on that investment. Simultaneously, constant exposure to carcinogenic agents concerns the average insurer, even as access to care and towards preventative care improves. The cost of individual coverage rises yearly, while health disparities historically present in our system only exacerbate conditions; seeming to neutralize any progress made.

# The Data

The focus of my proposal is actually a combined dataset; the historical trends in death rates of men and women in the United States("https://raw.githubusercontent.com/mwarnsle1/Cap1-fem/main/DeathTrend-ALL.xlsx%20-%20All%20US.csv". It details the 10 major types of cancers men and women in the U.S. population died of, per 100_000, from 1930 to 2018.

This data was chosen due to Cancer being the second leading cause of death in the country, which is a public health concern. Though the death rate has seen a steady decline since the 1990s(https://www.cancer.org/latest-news/facts-and-figures-2021.html#helpful_resources), coinciding with the smoking epidemic, some cancers are dropping at a much slower rate than others(e.g. breast), while others like prostate cancer have stagnated.

# Hypothesis

Given the implications for these trends, I plan to take a closer look to see if women have had a significantly higher rate of cancer deaths than men.

Ha: Women will have a significantly higher rate of cancer deaths than men between 1980 and 2018.
Ho: The null hypothesis is that there will be no difference in the rate of cancer deaths between men and women between 1980 and 2018.
Methods

For my research, I combined two datasets, "trends in death rates, 1930-2018" for men and women into one larger csv file. This was for both ease of accessibility and analysis of all cancer types. The combined dataset catalogued the unique kinds of cancer that both men and women died by. For the analysis, I used a binning strategy to split the dataset up again by gender, to compare death rates of men and women, by Year. I than split the data up further into smaller subsets, for each gender, for the years between 1980 and 2018, to test the hypotheses.

To test the initial distribution of the data, its descriptive statistics (i.e. skewness and kurtosis) were evaluated along with a histogram for a visual check. If these seemed to preliminarily indicate a normal distribution, an independent samples t-test could be applied between the groups, at a two-tailed 95% confidence interval. If the data did not appear normally distributed, the Kruskal-Wallis test could be applied to test for a normal distribution.

# Results

Based on the descriptive statistics and visualization, the data appeared to have been normally distributed, and an independent sample t-test was conducted. The results showed a significant difference between the two groups. That is, I was able to reject the null hypothesis, which was that there was no difference between the rate of deaths in men and women, from 1980 and 2018. A two-proportion z-test was then applied to provide more power and confirm the alternative hypothesis.

# Discussion & Recommendations

A closer look at the data indicates that women actually had a lower overall rate of cancer deaths than men, between the years of 1980 and 2018. While further analyses would need to be conducted to definitively find why that is, a visual check illustrates how even though breast cancer has the highest rates of cancer deaths overall, men have the highest rates of death in liver, stomach, and pancreas cancer. Also, the American Cancer Society did not factor in breast cancer of men in the data. For further insights, this data could be included. Additionally, which cancers have higher rates of morbidity within different time periods could be investigated, and from those outcomes, examine the possible higher rates between men and women, or any other trends that may be present for future analyses. 
