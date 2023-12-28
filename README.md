# DecisionTree


In this analysis, I utilized Titanic dataset to predict passenger survival based on provided values. Initially, I thoroughly examined the data, addressed unused values, removed them, converted 'Sex' and 'Embarked' columns into numeric values using the 'replace' and 'get_dummies' functions, and conducted a check for null values. While inspecting for null values, I identified only one null entry in the 'Fare' column, which I subsequently eliminated. This solitary data point did not significantly impact our dataset.

However, upon scrutinizing the 'Age' column for null values, I discovered 86 missing entries. I refrained from dropping these entries as doing so would have adversely affected the accuracy of my models. Consequently, I divided my data and employed the Linear Regression algorithm to predict the null values in the 'Age' column. Once I resolved these issues and ensured that my dataset contained no null, non-numeric, or extraneous data, I partitioned it again and applied the Decision Tree algorithm.

I evaluated the model's performance using accuracy score and classification reports, obtaining a 100% accuracy score.
