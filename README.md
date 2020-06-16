# AMMI-Boot-Camp-Kaggle-Competition
This repository contains our solution that ranked 1st at AMMI Rwanda in the boot camp competition organized at the end of the 2 weeks boot camp. The random forest regressor secured an RMSE score of 17.31265 private score and 26.27123 public score. The models in the notebook attempted to predict the price of a bottle of wine based on a collection of over one hundred thousand reviews and other product features. 

## Data description
The [data][kaggle competitions download -c ammi-bootcamp-kaggle-competition] summarize 258210 wine reviews:

• 175000 are the training set, the data on which to train your models;

• the remaining 83210 observations constitute the validation set (or score set), or the data on which you must make the estimate for the submission. The validation set at your disposal obviously does not contain the variable price, the price of the bottle of wine that the goal of your forecast.

The variables present are:

country (String) The country that the wine is from

province (String) The province or state that the wine is from

region_1 (String) The wine growing area in a province or state (ie Napa)

region_2 (String) Sometimes there are more specific regions within the wine growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank

winery (String) The winery that made the wine

variety (String) The type of grapes used to make the wine (ie Pinot Noir)

designation (String) The vineyard within the winery where the grapes that made the wine are from

taster_name (String) taster name

taster_twitter_handle (String) taster twitter account name

review (String) A few sentences from a sommelier describing the wine's taste, smell, look, feel, etc.

review_score (Numeric) Number of points WineEnthusiast rated the wine on a scale of 1-100

TARGET: price (Numeric) The cost for a bottle of wine
