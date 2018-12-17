# Mercari-Price-Suggestion
* This project uses state of the art natural language processing techniques and other data modelling strategies on different variables of Mercari dataset to suggest the price for a listing.
* The data is available on the kaggle website. 
https://www.kaggle.com/c/mercari-price-suggestion-challenge/data
* Description of the data:
* The data used here is the train.tsv file.
* The files consist of a list of product listings. These files are tab-delimited.
* train_id or test_id - the id of the listing
* name - the title of the listing.
* item_condition_id - the condition of the items provided by the seller.
* category_name - category of the listing.
* brand_name - brand name of the listing.
* price - the price that the item was sold for. This is the target variable.
* shipping - 1 if shipping fee is paid by seller and 0 by buyer.
* item_description - the full description of the item. 

* The file mercari_price_prediction.ipnb contains the detailed data cleaning, data processing, exploratory data analysis and the model 
building steps followed to implement the model.
* suggested_price.csv files contains the suggested prices of the listings.

* Future work: More different types fo supervised learning algorithms can be used to build the model. 
These models will be added as and when they are finished building and gives more accuracy than the ridge model.

* Steps to reproduce the process:
* Download the data into a seperate folder from the provided website.
* Extract the data from the zipped file.
* Place the mercari_price_prediction.ipnb file into the folder.
* Follow the steps in the notebook to build the model.
