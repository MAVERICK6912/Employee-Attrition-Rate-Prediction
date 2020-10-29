# Employee Attrition rate prediction

>Employee attrition is a gradual but deliberate reduction in the number of employees in a company or business organization. Employees will at some point in time look to change their job places for a number of reasons. It might be for professional or personal reasons but it does happen.

So, an organisation need to keep in check the attrition rate so as to have a high performant workforce at all times.

This problem was a part of a hackathon organized by HackerEarth, I was able to get a **rank in the top 2%** of the participants.

My approach was as follows:
- EDA.
- Imputing missing values using a predictive model(KNN).
- Encoding categorical features.
- Scaling numerical features.
- Modeling using Decission Tree(RMSE: 81.40)
- Modeling using XGBoost(RMSE: 80.89)
- Getting feature importance.
- Hyper parameter tuning Decission tree model.
- Submission using hyper parameter tuned DT(**RMSE: 81.434**)


Future scope
- Use KNN to predict missing feature values.
- Group categorical data to check improve in evaluation metric score.
- Use CATBoost.


