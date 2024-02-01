# airline_analysis
I found a dataset that covered 30 years' worth of passenger and flight information. Using pandas, I cleaned it, analyzed it, added features, merged it with external data, used Random Forest to identify the important features, and then built a Polynomial Regression model that predicts the number of monthly passengers based on a few varying features.

Given the Polynomial Regression model's scores of Mean Squared Error: 8462548582684.90, R-squared: 0.92, and CV Scores: [0.15864568, 0.77822757, 0.39640414, 0.92945577, 0.86030124], and given the input features Dom_ASM, during_pandemic, and Total Injuries, I could predict the number of Passengers with approximately 92% accuracy.

However, if Dom_ASM were unavailable, using Int_LF, NumberOfEvents, Int_Flt, Month, Dom_Flt would yield a less impressive but statistically significant r2 score of 0.79 with a MSE of 23288307747977.16 and cross variation scores of [ 0.83241679 0.44597674 -0.8331624 0.56630284 0.48873578].
