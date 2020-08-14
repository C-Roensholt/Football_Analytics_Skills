# Football Analytics Skills
This is my repository for some of the technical skills which I find useful for Football (Soccer) Analytics. This is e.g. extracting data, building models and visualising our results.

## Content
- `1_DataExtraction.ipynb` is a data extraction and preperation of different events (shots, passes, etc.) from the StatsBomb free data (https://github.com/statsbomb/open-data)
- `2_LinearRegression.ipynb` we build a basic LinearRegression model and look at how __Pass Completion%__ correlates with __number of passes__. Moreover we discovers that __carries__ and __meters passed the ball__ have a positive linear relationship.
- `3_LogistricRegression.ipynb` we build a logistic model which can predict the probability of a shot resulting in a goal (i.e. `xg model`). This model is trained on with __features__ like distance to goal, shot angle and if the shot were a header and evaluated using `accuracy`, `log loss` and compared to StatsBomb xG model.
