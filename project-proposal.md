Jessica Gajiwala, Sophie He, Naomi Ortega, Sunny Sun, Zhengwu Xiao

Group 24

Project Proposal

Problem statement and importance 

We are analyzing the factors that influence salary in AI jobs. This problem is important because the AI job market is growing rapidly, so we want to understand what factors drive the salaries of individuals across the industry. The implications of our project may be important to students planning for a career in AI, or to individuals seeking to enter the workforce who want to plan their career path or consider advanced degrees, according to the outlook for salaries.

We will consider 25 AI job roles spanning different education requirements, experience levels, locations, and more. We are first interested in seeing whether there is an effect of the type of AI job role on salary. Furthermore, advanced degrees and seniority level often lead to higher salaries, so we want to analyze if this holds for AI jobs, and if there is a varied effect across roles. Our analysis aims to yield an informative result about whether compensation is more rewarded by education level or experience level, and if the preference for education or experience level varies across roles. This points to consequences for how those seeking jobs in artificial intelligence might plan their education path. 

Another important factor we will consider is, after accounting for role variations and experience level, whether the location an AI job is in, as well as whether it is remote, makes it more likely to pay higher. Knowing where AI jobs pay higher may drive applicants to migrate to well-paying areas for work or to seek more remote work. Additionally, AI roles are situated across a variety of industries. We want to know if there are significant differences in how much people make in AI roles depending on the field. This may impact which domains students in AI-related majors choose to specialize in.

Data source 

The data source we will use is a dataset of AI job listings. It contains 1,500 samples of job postings of AI and Machine learning roles posted between the years of 2025 and 2026\. There are 25 distinct variables. Some of the key features of this data set are annual salary, years of experience, and education required. 

Where will we acquire the data from 

The dataset is from Kaggle. It is linked here: [AI Jobs Market 2025-2026 | Salaries](https://www.kaggle.com/datasets/alitaqishah/ai-jobs-market-2025-2026-salaries). 

Proposed Analyses

We propose to compare linear regression models to analyze which predictors, like Years of Experience, Education Level, and Company Size, influence salary. In exploratory data analysis, we will fit linear regression models predicting salary for each of the covariates and check the F statistic and R-squared to see which covariates influence salary the most. We will use the influential covariates for further analysis. To validate our model’s reliability, we will use Cook’s Distance to identify high-leverage outliers and check QQ-plots for curvature or vertical shifts that indicate non-normality in the salary residuals. 

We will use a T-test to determine whether there is a difference in salary between remote and in person jobs, and a Kolmogorov-Smirnov test to compare the distribution of salary between entry and senior level positions. Using ANOVA, we will compare salaries across multiple groups, such as job roles, locations, or industries. If the assumptions for ANOVA are not reasonable, we may use a nonparametric alternative such as the Kruskal-Wallis test. 

Expected Outcomes 

We expect there to be variation between the type of AI role and salaries, since technical roles may have higher pay compared to more business or governance roles. Next, we expect there to be a positive relationship between experience level and salary, since salary tends to increase with more years of work experience. For education level, we similarly expect a positive relationship, since higher education signals access to higher-paying roles and salaries. We hope to produce a definitive outcome on whether education level or experience level has the greater effect on salary in AI jobs. For examining the city of the AI role, we expect some variation. For example, major cities like San Francisco, which are AI hubs, may have higher salaries (in USD) compared to other cities. We expect that company size also may impact salary, because larger companies have more resources to pay their employees compared to smaller start-up companies. Overall, our expected outcomes of the project are to determine the most influential factors affecting salary in artificial intelligence jobs through a thorough analysis of job characteristics.


Feedback from TA: 
The proposal includes relevant methods, such as EDA, linear regression, t-tests, K-S tests, ANOVA, Kruskal-Wallis tests, and regression diagnostics. To strengthen the methodology, the group should make the multivariable regression model the main analysis rather than comparing each covariate separately, and they may want to consider log-transforming salary because salary data are often skewed.