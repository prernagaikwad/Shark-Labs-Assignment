# Shark-Labs-Assignment
Completed the assignment of Shark Labs.
1.Predict the price of a house
2.Product matching
Predict the price of a house 
Objective:The goal is to understand the relationship between house features and how these variables affect the house price
Libraries And Framework:Pandas, Numpy, Matplotlib,Scipy,Scikit-learn,scipy,XGBoost,LightGBM
Machine Learning Model Performance by using HyperparameterTuning

Model	                                                       R2Score
RandomForestRegressor	                                      0.766867
LGBMRegressor	                                              0.757788
XGBRegressor	                                              0.750871
<catboost.core.CatBoostRegressor object at 0x7f0690ed5400>	0.749946
HistGradientBoostingRegressor	                              0.74873
ExtraTreesRegressor	                                        0.748688
GradientBoostingRegressor	                                  0.746872
BaggingRegressor	                                          0.737747
DecisionTreeRegressor                                     	0.636332
LinearRegression                                          	0.621219
SVR	                                                        -0.00303
MLPRegressor	                                              -0.013072
KNeighborsRegressor                                        	-0.162472



Product Matching
Objective:Using ML/DL techniques, match similar products from the Flipkart dataset with the Amazon dataset. Once
similar products are matched, display the retail price from FK and AMZ side by side
For example:
FDT Women's Leggings from Flipkart should be matched with FDT WOMEN'S Leggings Pants from Amazon
Libraries And Framework: Pandas ,Numpy ,FuzzyMatcher
A Python package that allows the user to fuzzy match two pandas dataframes based on one or more common fields.
Fuzzymatches uses sqlite3's Full Text Search to find potential matches.It then uses probabilistic record linkage to score matches.
Finally it outputs a list of the matches it has found and associated score.
It then uses probabilistic record linkage to score matches.

