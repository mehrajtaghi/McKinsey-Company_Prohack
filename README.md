# McKinsey_Company_Prohack
Prediction &amp; Optimization

McKinsey&Company Prohack
This is an anonymized dataset provided by the one of the most prestigious consulting companies around the
world that operate in many countries including Azerbaijan. In this task, you need to predict the target value
(“y”) given all the other features. At the end of this task, you will be ready for your first data science job as
this task encomposes all of the necessary phases a top-notch data scientist in the finance industry passes
through to successfully build an in-house prediction model. This task is composed of 2 components:

1)Prediction (Regression)
2) Optimization

You must show your authentic work in all of the following sections:
1.- Data cleaning
2.- Data Preprocessing
3.- EDA (Exploratory Data Analysis)
4.- Feature Engineering and Feature
Selection5 - Modeling
6 - Performance Evaluation
7 - Optimization


1)Index predictions are evaluated using RMSE metric

2) Energy allocation is also evaluated using RMSE metric and has a set of known factors
thatneed to be taken into account.
Every galaxy has a certain limited potential for improvement in the index described by the
following function:

Potential for increase in the Index = -np.log(Index+0.01)+3

Likely index increase dependent on potential for improvement and on extra energy availability is
described by the following function:

Likely increase in the Index = extra energy * Potential forincrease in the Index **2 / 1000

There are also several constraints:
• In total there are 50000 zillion DSML available for allocation and no galaxy at a point in time
• no galaxy should be allocated more than 100 zillion DSML or less than 0 zillion DSML.
• Galaxies with low existence expectancy index below 0.7 should be allocated at least 10% of
thetotal energy available in the foreseeable future

3) Performance is based on a combined scaled metric:

80% prediction task RMSE + 20% optimization task RMSE * lambda

where lambda is a normalizing factor

