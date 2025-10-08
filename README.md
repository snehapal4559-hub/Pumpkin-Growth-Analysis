# Statistical Analysis of Pumpkin Plant Growth: A Comparative Study

## Project Overview

This project provides a comprehensive statistical analysis of pumpkin plant growth over a 12-week period. The core objective is to determine whether a specific treatment has a significant positive effect on the growth of pumpkin plants compared to a control group. The analysis employs both parametric and non-parametric hypothesis tests, as well as linear trend fitting, to rigorously evaluate the treatment's impact across various growth parameters.

## Hypothesis

[cite_start]The analysis for each parameter was conducted based on the following hypotheses[cite: 5, 6]:

* [cite_start]**Null Hypothesis ($H_0$):** There is no significant difference in the average value of the parameter between the control group and the treated group. [cite: 5]
* [cite_start]**Alternative Hypothesis ($H_1$):** The average value of the parameter is significantly higher in the treated group than in the control group. [cite: 6]

The level of significance ($\alpha$) was set at 0.05. [cite_start]The null hypothesis is rejected if the calculated p-value is less than 0.05[cite: 7, 8].

## Methodology

The analytical approach involved a week-by-week comparison of the two plant groups.

1.  [cite_start]**Visualization:** Weekly mean values for each parameter were plotted for both the control and treated groups to allow for initial visual comparison[cite: 10].
2.  **Linear Trend Fitting:** A linear trend line was fitted to the data for each group to model the growth rate over time. [cite_start]The quality of this fit was assessed using the Multiple R² value[cite: 11, 13].
3.  [cite_start]**Statistical Testing:** To formally test for significant differences, two distinct statistical tests were performed for each week[cite: 15]:
    * [cite_start]**Student’s t-test** (parametric) [cite: 15]
    * [cite_start]**Wilcoxon’s rank-sum test** (non-parametric) [cite: 15]

## Parameters Analyzed

[cite_start]The study tracked ten distinct growth parameters for the pumpkin plants[cite: 20]:

* [cite_start]Plant Length [cite: 21]
* [cite_start]Number of Leaves [cite: 22]
* [cite_start]Number of Nodes [cite: 23]
* [cite_start]Leaf Length [cite: 24]
* [cite_start]Leaf Width [cite: 25]
* [cite_start]Number of Tendrils [cite: 26]
* [cite_start]Number of Buds [cite: 27]
* [cite_start]Number of Flowers [cite: 28]
* [cite_start]Number of Fruits [cite: 29]
* [cite_start]Tendril Length [cite: 30]

## Summary of Results

The analysis consistently demonstrated the effectiveness of the treatment across most growth metrics.

* [cite_start]**Significant Positive Impact:** For parameters like **Plant Length**, **Number of Leaves**, **Number of Nodes**, **Number of Buds**, **Number of Fruits**, and **Tendril Length**, the treated group showed a statistically significant and consistently higher growth rate compared to the control group, especially after the first few weeks of application[cite: 41, 52, 64, 114, 137, 145].
* [cite_start]**Delayed Effect:** For **Leaf Width**, the treatment showed no significant effect initially but resulted in a significant increase in width from the 10th week onwards[cite: 88, 89].
* [cite_start]**No Significant Effect:** The analysis of **Leaf Length** showed no statistically significant difference between the treated and control groups throughout the observation period[cite: 76].
* **Non-Linear Trends:** The **Number of Flowers** showed a non-linear trend, with the number first increasing and then decreasing for both groups. [cite_start]The linear model was not a good fit for this parameter, but the hypothesis tests still indicated a significantly higher number of flowers in the treated group during the peak weeks[cite: 120, 122, 127].

## Tools & Technologies

* **R:** Used for all statistical computations, hypothesis testing, and generation of plots.
