# Problem statement: -
- Project includes data that having deatils of each stores sales , orders, how much discounts provided , based on region, based on location type.
- We need to find future sales using raw data that is provided. to do future prediciton given parameters help you to gather required sales details with respect to store, location and region. Data include holiday parameter that additionally used to see how holiday will affect on sales.

# Feature Engineering : -

- Deal with NAN values
- Deal with Outliers
- Standardization of data
- Validation method
# Languages Used: -
- Python 3.9.0

# Tools and Resources: -
- Google colab, Jupyter notebook

- Packages: Pandas, NumPy, sklearn, Matplotlib, seaborn.

# EDA : -

![sale1](https://user-images.githubusercontent.com/82714026/149884906-fb89178c-824a-4ac6-bf07-582c1ea581db.png)
- Sales according to store type

![sale2](https://user-images.githubusercontent.com/82714026/149884952-ae97332d-c86a-4f81-b25b-b71874ceced6.png)
- Sales according to location wise.
![sale3](https://user-images.githubusercontent.com/82714026/149884957-d7a87a94-189c-43a7-8d0d-130cde92b8c6.png)
- Sales according to region wise.

![sale4](https://user-images.githubusercontent.com/82714026/149884958-4a64021a-653c-491c-a7db-e40ed11618dc.png)
- Top ten highest sales stores.

![sale5](https://user-images.githubusercontent.com/82714026/149884961-7d37c595-711f-48bc-a7aa-728401cd356b.png)
- Top ten datewise sales.


# Model Building: -
- Linear regression
- LASSO
- SGD regressor
- Random forest regressor
- Gradient boosting regressor



# Hyperparameter Tuning: -
- Random search CV

# Metric of Evaluation: –
- Mean Squared log error[MSLE]

# Conclusion:
- While performing with multiple model It perform well on random forest. I even check with ARIMA model however normal model perfroms better.
