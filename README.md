# Welcome to the Personal Project - OptiMarket: Uncovering the Ultimate Marketing Approach

Hello! I'm Ayumu Justin Ueda, a Data Science student at UC Berkeley. You can find my profile on (https://www.linkedin.com/in/ayumu-ueda-ab1879224/).

In this project, as a data scientist at a car insurance company, I've been provided with last year's data documenting the outcomes of marketing campaigns involving various types of strategies (a combination of insurance renewal plans - Offer1 and Offer2, and different sales channels - Agent, Branch, Call Center, Email).


## Objective:
My objective is to enhance the KPI, specifically the acceptance rate of offers, in the upcoming marketing phase by identifying the most effective combinations of customer segments and marketing strategies (a combination of offer type and sales channel).
<br/><br/>

## Project Overview:

### 1. Customer segmentation for pinpointing optimal marketing strategies in each category:

**Skills Applied:**
* Parametric Statistical Inference(Test of Homogeneity, Chi Square Test)
* K-means Clustering
* Principal Component Analysis (PCA)

**Conclusion for this section:**

|    |   cluster | best marketing strategy   |
|---:|----------:|:--------------------------|
|  0 |         0 | Offer2_Agent              |
|  1 |         1 | Offer1_Email              |
|  2 |         2 | Offer2_Branch             |
|  3 |         3 | Offer2_Agent              |
|  4 |         4 | Offer2_Call Center        |
|  5 |         5 | Offer2_Agent              |
|  6 |         6 | Offer2_Email              |
|  7 |         7 | Offer2_Email              |
|  8 |         8 | Offer2_Call Center        |
|  9 |         9 | Offer2_Agent              |

The best combination of marketing strategies is as outlined above.

For future marketing initiatives, we can utilize customer information such as gender, education, etc., categorizing them into one of the ten groups mentioned. This approach allows us to employ the most effective marketing strategy for each group, ultimately increasing the number of car insurance renewals and enhancing the profitability of our insurance department.

### 2. Optimizing Email Sales through A/B Testing:

**Skills Applied:**
* Parametric Statistical Inference(Anova one sided test)
* Non-Parametric Statistical Inference(Kruskal-Wallis test)
* A/B test (Bootstrap)

**Conclusion for this section:**

After conducting A/B testing on the marketing campaign, it's evident that Promotion 1 is the most effective in increasing sales.

I have decided to implement Promotion 1 for the email marketing campaign.
