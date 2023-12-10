# MSBA-Capstone
Repo for IS 6812 Capstone 1

Summary of business problem and project objective
Home Credit Business Problem Statement

New loan borrowers struggle to secure loans due to insufficient or non-existent credit histories. Home Credit has identified this population as a potential customer segment to serve and provide a positive and safe borrowing experience since they are often overlooked by big banks and are, unfortunately, taken advantage of by untrustworthy lenders.

By using substitute data as a proxy for traditional credit scores (FICO and BK), the analytics team attempts to evaluate which metrics are the best indicators for applicants repaying their loans. The project deliverable will be a target variable probability prediction for each SK_ID_CURR in the data set. Submissions will be evaluated by Kaggle on the area under the receiver operating characteristic (ROC) curve between the predicted probability and the observed target. Additional deliverables must be agreed upon with the analyst and added to a revised business problem statement.

The project will be completed and presented in student groups by the end of the IS 6812 MSBA Capstone course Fall semester 2023. 


Group's solution to the business problem
Analytic Problems: Prediction of Loan Defaults: The primary analytical problem is to build predictive models that can effectively predict whether a loan applicant is likely to default. This involves analyzing historical data to identify patterns and features indicative of default.

Data Preprocessing: Dealing with missing values, outliers, and transforming the data into a suitable format for modeling is an essential part of the analysis.

Feature Engineering: Identifying and creating relevant features that contribute to the prediction of loan defaults. This may involve exploring interactions between variables and deriving meaningful features from the available data.

Our group leveraged various analytic and machine learning approaches to finalize a high-performance model. Prior to this, we individually conducted exploratory data analysis, data preparation, and model submission. Greg started the process off by helping with some in-depth EDA, data transformation, and problem wireframing, then We submitted modeling in Kaggle using Hunter’s logistic regression model (0.59), Tom’s h2o and lime model to do a matrix statistic analysis (0.68), and Hari’s XGBoost modeling (0.78). The XGBoost resulted in the highest Kaggle score (0.78), and is the model we settled on leveraging.


The business value of the solution
Recommendations from our analysis. As we delve into Home Credit’s data and operations, we uncover insights highlighting their commitment to empowering consumers, particularly those entering the credit system for the first time.
Looking at Home Credit’s loan application, we found that simplifying this process is crucial. Imagine a system where applying for a loan is as easy and transparent as online shopping. By integrating advanced technologies, Home Credit can make this a reality, ensuring that applications are straightforward, quick, and secure. This enhances efficiency and builds trust – a vital component when dealing with first-time borrowers who might be intimidated by complex financial procedures. Another recommendation that will help first-time borrowers. Focus on customer support and transparency to enhance the customer experience.
After looking at their website, we found they plan to enter more global markets and new customer bases. This offers tremendous opportunities for growth and increase to the bottom line. But, this increases the amount of risk Home Credit ability to adapt and understand local needs. One way we recommend Home Credit to mitigate this risk is strategic partnerships with local know businesses. Partnerships can provide insights and brand recognition to help customers feel safer. As a lender, Home Credit needs to make global customers not view them as a scam before they can fully develop their brand in that area. Partnerships aren't just gateways into new markets; they are opportunities for cross-cultural learning and innovation, which can open doors to additional markets.
In conclusion, we recommend that Home Credit simplify the loan application and transparency for new borrowers, balancing operational efficiency with customer empowerment. Next should seek strategic partnerships with local businesses, when seeking to enter a new global market.


Results
Model Effectiveness: Our model enhances Home Credit’s predictive capability for identifying potential loan defaults. This improvement positively influences Home Credit’s financial performance by increasing the approval rate for creditworthy applicants while decreasing approvals for those who may not meet creditworthiness criteria.

Model Exploration and Selection: Exploring a range of models allowed us to gain valuable insights into their strengths, weaknesses, and performance within the context of our task. This exploration played a pivotal role in our model selection, maximizing performance, understanding feature importance, assessing robustness, and leveraging model diversity for improved predictions and insightful information.

Optimal Model Selection: Given the classification nature of the problem and the abundance of available classification models, we initiated our search by evaluating different options. We experimented with Gradient boosting, H20 and lime, and logistic regression models.

Performance Evaluation: Comparing the performances of these models was crucial in identifying the most suitable one. We also considered Kaggle scores to ensure alignment with the model’s performance. However, we had to address overfitting issues. While the H20, Lime, and Gradient Boosting Machine models demonstrated similar performance, we opted for the Gradient Boosting Machine due to its faster training capabilities.

Overall, our process consisted of forming a group strategy together, taking time to understand the data we were working with, and then creating various models of complexity to evaluate performance. After finalizing and submitting various models, we found that the XGBoost machine learning method produced the highest Kaggle Score, even though it required the highest computing cost. This methodology produced great results and helped all of us in the team learn more about the types of predictive analysis available to us in R.


Group Members and Contributions
Collaboratively, we operated as a team using R Studio, where we conducted the modeling process. Using different R packages, we successfully consolidated various code segments into a single notebook.

Harichandana Gonuguntla: Data preprocessing, missing data calculation, and imputation. Feature Engineering, different datasets(bureau, bureau balance, previous application) aggregation for predictions, Modeled using XGBoosting multiple times using different parameters and datasets. Hunter Harmer: Logistic regression modeling, compiling the whole code into one notebook, error resolution, adding content such as introduction, business problem, and summarising the model’s results into the notebook. Tom Kingston: h20 and lime modeling, data cleaning, error resolution. Greg Francom: Initial data analysis, data aggregation, troubleshooting.

Through this project, I learned to concentrate and focus on the results, not the process. Speak to the "decision makers" and provide evidence and confidence to support your findings.  
