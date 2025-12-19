Summary- 
The project was a part of the subject business analytics where we had to take any dataset- analyse it using ML techniques and derive business insights accordingly. 
Steps:
  1. A chinese cars dataset was taken from arXiv- Main features included month-year wise sales and reviews.
  2. The chinese language reviews were converted into English language.
  3. Preprocessing was done on the dataset to handle missing values, outliers, date-time format, one-hot encoding, standardization, combined review through text processing, etc.
  4. Feature engineering was performed to focus on only the important features and eliminate others to improve accuracy of the models and optimize computational time and space.
  5. Sentiment Analysis- VADER was used to mark the reivews with their sentiment score and label.
                         Tf-IDF vectorization was performed to feed the combined review into models.
                         Truncated SVD was used for dimentionality reduction.
                         Regression- LinearRegression, LinearSVR, GradientBoosting were used to predict sentiment score.
                         Classification- LogisticRegression, LinearSVC, MultinomialNB were used to predict sentiment label.
                         Hyperparameter tuning was performed to get better accuracies.
  6. Sales Analysis and Time-Series Forecasting- ARIMA and SARIMA were used to predict and analyse sales data and its trend on factors such as series, brand, city, fuel, etc.
  7. Clustering- 4 clusters were formed to compare sales and sentiments relation and draw insights on its interconnectivity.
  8. Results- Overall all the results we got from the above steps were visulalized and presented to tell the current information we gain from the data, its future prediction and based on that we were able to draw business conclusions. 
                         
