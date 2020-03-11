# Sparkify
### Project Overview
Sparkify is a popular digital music service where many of users stream their favorite songs everyday using either free or paid services. This project is to develop a model that predict which users are at risk cancelling their service. If we can accurately identify those users before they leave, the business can offer them incentives and discounts potentially saving millions in revenues

### Data
The underlying data used to develop the model is a two-month subeset of the whole behavioral data. It contains a total of 286,500 rows of user events and has 18 columns. 278,154 out of the 286,500 are valid records and the rest are with missing UserId. The final dataset on user level used for modelling is saved [here](saved_final_user_dataset.CSV).

### Modelling
To build our model, the modelling dataset was firstly transformed and normalised. The following three supervised learning algorithms were then considered:
- Logistic Regression (LR)
- Decision Tree Classifier (DTC)
- Gradient Boosted Tree Classifier (GBT)

The best model based on model accuracy and F1 score is saved [here](DecisionTree.model).

### More details
The code can be found at [Sparkify.ipynb](Sparkify.ipynb).

The blog post about the findings can be found at the [blog](https://tracyh0407.github.io/Sparkify---Blog/).
