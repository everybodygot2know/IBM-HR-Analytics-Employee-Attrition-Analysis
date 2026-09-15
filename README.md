# IBM-HR-Analytics-Employee-Attrition-Analysis
This project analyzes employee attrition using the fictional IBM HR Analytics dataset from Kaggle. The objective was to identify key factors contributing to employee turnover and demonstrate how Excel can be used to perform end-to-end business analysis, from data exploration and statistical modeling to optimization and executive decision support.

The project combines descriptive analytics, inferential statistics, scenario analysis, and optimization techniques commonly used by business, finance, operations, and HR analysts.

Employee turnover increases recruitment costs, reduces productivity, and negatively impacts organizational performance.

The goal of this project was to answer the following questions:

* Which employee and workplace factors are most strongly associated with attrition?
* Which variables remain statistically significant after controlling for other factors?
* How can scenario analysis and optimization be used to explore potential compensation strategies under a fixed budget?
* What workplace factors may deserve further attention in employee retention efforts?

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




**Correlation Analysis**
* Measured relationships between employee attributes and attrition to identify potential predictors.


<img width="1152" height="582" alt="{34D64895-623A-4C0F-824A-79381EF574A6}" src="https://github.com/user-attachments/assets/988cf1a4-71e0-4064-9734-3f6cb9c338b5" />



**Multiple Linear Regression**
* Built a multiple linear regression model as an exploratory linear probability model to estimate relationships between employee characteristics and the probability of attrition while controlling for other variables.

<img width="840" height="499" alt="{823D8293-BF6A-4FED-B82E-AA5BF63E6884}" src="https://github.com/user-attachments/assets/dfd10fe7-ead0-4147-87f6-74aaa158e3eb" />

**Model Results:**

* R² = 12.1%
* F = 28.88
* p < 0.001


**Scenario Analysis**
* Goal Seek was used to explore hypothetical compensation changes associated with selected attrition targets under the estimated model. 

<img width="1034" height="620" alt="image" src="https://github.com/user-attachments/assets/4283a7ab-0783-4a86-a153-ec28e88b92e3" />


**Optimization**
* Used Excel Solver to demonstrate how a fixed compensation budget could be allocated across employees under a set of model assumptions and constraints.

<img width="776" height="332" alt="{D6A6C0A2-9B35-4B96-9740-BB826D9A1F5B}" src="https://github.com/user-attachments/assets/a57288cf-f079-4727-9044-8b01fe98053b" />


**Key Findings**
* The regression model was statistically significant overall (F = 28.88, p < .001), indicating that the included variables collectively have a meaningful relationship with employee attrition.
* The model explained approximately 12.1% of the variation in attrition, suggesting that important determinants of turnover remain outside the variables included in the analysis.
* Overtime showed one of the strongest positive associations with attrition.
* Higher Job Satisfaction, Environment Satisfaction, and Relationship Satisfaction were significantly associated with lower attrition.
* Monthly Income and Job Level were not statistically significant after controlling for the other factors in the model.
* Scenario and optimization analyses demonstrated how Excel tools such as Goal Seek and Solver can be used to evaluate hypothetical retention strategies under budget constraints.

**Business Recommendations**
* Investigate excessive overtime and workload distribution, given the strong association between overtime and attrition.
* Monitor employee satisfaction measures and identify teams or job roles where satisfaction scores are consistently low.
* Treat compensation as one component of retention strategy rather than assuming salary increases alone will reduce attrition.

Original Source: IBM HR Analytics Employee Attrition & Performance

(https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)


Created by Walter Keel | July 2026
