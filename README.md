# IBM-HR-Analytics-Employee-Attrition-Analysis
This project analyzes employee attrition using the fictional IBM HR Analytics dataset from Kaggle. The objective was to identify key factors contributing to employee turnover and demonstrate how Excel can be used to perform end-to-end business analysis, from data exploration and statistical modeling to optimization and executive decision support.

The project combines descriptive analytics, inferential statistics, scenario analysis, and optimization techniques commonly used by business, finance, operations, and HR analysts.

Employee turnover increases recruitment costs, reduces productivity, and negatively impacts organizational performance.

The goal of this project was to answer the following questions:

* Which factors are most strongly associated with employee attrition?
* Which variables significantly predict turnover?
* How should a limited salary increase budget be allocated to maximize retention?
* What actionable recommendations can improve employee retention?

Tools Used:
* Power Query
* Pivot Tables and Pivot Charts
* Correlation Analysis
* Multiple Linear Regression
* Scenario Analysis (Goal Seek)
* Optimization using Excel Solver
* Data visualization

<img width="1081" height="916" alt="{6290DBB1-E245-40D6-AA05-9450DCE7E2DF}" src="https://github.com/user-attachments/assets/70d0d118-9295-4c04-8202-f95c06f6f770" />


Investigated employee demographics and workplace characteristics through:
* Department
* Job Role
* Overtime
* Monthly Income
* Job Satisfaction
* Environment Satisfaction
* Relationship Satisfaction
* Years at Company


<img width="1152" height="582" alt="{34D64895-623A-4C0F-824A-79381EF574A6}" src="https://github.com/user-attachments/assets/988cf1a4-71e0-4064-9734-3f6cb9c338b5" />


**Correlation Analysis**
* Measured relationships between employee attributes and attrition to identify potential predictors.

<img width="840" height="499" alt="{823D8293-BF6A-4FED-B82E-AA5BF63E6884}" src="https://github.com/user-attachments/assets/dfd10fe7-ead0-4147-87f6-74aaa158e3eb" />


**Multiple Linear Regression**
* Built a regression model to quantify the impact of employee characteristics on attrition while controlling for other variables.

**Model Results:**

* R² = 12.1%
* F = 28.88
* p < 0.001


<img width="1034" height="620" alt="image" src="https://github.com/user-attachments/assets/4283a7ab-0783-4a86-a153-ec28e88b92e3" />

**Scenario Analysis**
* Used Goal Seek to estimate compensation changes required to reach targeted attrition reductions.

<img width="776" height="332" alt="{D6A6C0A2-9B35-4B96-9740-BB826D9A1F5B}" src="https://github.com/user-attachments/assets/a57288cf-f079-4727-9044-8b01fe98053b" />

**Optimization**
* Used Excel Solver to optimize salary allocations under a fixed compensation budget.

**Key Findings**
* Overtime was the strongest predictor of employee attrition.
* Higher Job Satisfaction, Environment Satisfaction, and Relationship Satisfaction significantly reduced attrition risk.
* Monthly Income and Job Level were not statistically significant after controlling for workplace factors.
* Targeted salary increases are more effective than uniform salary adjustments under budget constraints.
* Employee satisfaction and workload management appear more influential than compensation alone.
  
**Business Recommendations**
* Reduce excessive overtime through workload balancing and staffing adjustments.
* Prioritize retention efforts for high-risk employees identified by the regression model.
* Combine targeted salary increases with employee engagement initiatives.
* Allocate compensation strategically rather than evenly across the workforce.
* Use optimization techniques to maximize retention outcomes within budget constraints.

Original Source: IBM HR Analytics Employee Attrition & Performance
(https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)


Created by Walter Keel | July 2026
