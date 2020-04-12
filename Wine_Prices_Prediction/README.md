Predict the price of a product based on a collection of over one hundred thousand reviews and other product features.

The data summarize 171936 wine reviews:
• 131250 are the training set, the data on which to train your models;
• the remaining 40686 observations constitute the validation set (or score set), or the data on which you must make the estimate for the submission. The validation set at your disposal obviously does not contain the variable price, the price of the bottle of wine that the goal of your forecast.

#Data fields

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

TARGET: price (Numeric) The cost for a product
