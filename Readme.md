# Home Credit Default Risk - Predicting how capable an applicant is of repaying a loan

Problem
Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.
Home Credit is currently using various statistical and machine learning methods to make these predictions. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.

Link:
https://www.kaggle.com/c/home-credit-default-risk


1. EDAHomeCredit file shows the data analysis part of the code
   - File and Filesize of the data
   - Data Analysis  - Visualizing distribution of data like types of loan, family status of applicant's, occupation of applicant's, education of applicat's
2. MergeHomeCredit file contains the code of merging all the data files to one single file. The merged file of application train data is in output/trainMerge file and applicationtest data is in output/testMerge file
3. TrainAndPredictHomeCredit file contains the code of data cleansing, splitting data, model fitting and predicting
4. The output of the application test is in output/testResult file