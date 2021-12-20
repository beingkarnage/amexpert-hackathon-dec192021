### AmExpert Hackathon - Credit Card fraud detection

#### Performed the simplest EDA
1.checking of null vals, duplicates
2. checking of corelations
#### Feature selection 
1. discarding useless columns according to EDA(variance threshold)
	1.cutomer_id
	2.name
	3.total_family_members
	4.credit_limit
#### Feature engineering
1.In terms of feature engineering, I did nothing

#### Model Training, Encoding, Imputing
1. used pretty much every model, encoing(ordinal, One hot), imputing(mean,mode), there is no need for data imbalance handling because the scoring metrics is f_score(macro)
2. tried AutoML also (TPOT)

#### Conclusion : Only able to archeive the 92% f_score (without featurer selection) online test, for testing i consider the train.csv as whole data set to get a grasp of how my model is doing (99% f_score when train.csv considered as whole dataset).
