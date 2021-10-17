# Blog-Post
The kaggle data set is based on [housing prices in Ames, Iowa](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). It is a modernized alternative to the well-known Boston Housing dataset. 

The Boston housing dataset contains housing prices with over 63 usable types of housing attributes. We wanted to explore the feasibility of using the attributes to predict pricing of houses using regression machine learning techniques. Before that, we require to identify the attributes with high association with housing prices. Out of the 63 attributes, 36 are numerical features and 29 are categorical features. The relationship of each attribute to pricing were ranked by applying the correlation to housing prices. 

## Questions of Interest:
1. What are the top associated and non-associated features of housing attributes with the pricing of Boston houses?
2. Select and explore in plots the top associated and non-associated features of housing attributes with the pricing of Boston houses.
3. Fit a linear regression model to the training data of selected features and calculate the MSE of the model.
4. How does the model performance differ using all categorical features?

## Conclusion:
The Boston housing dataset contains housing prices with over 63 usable types of housing attributes. We wanted to explore the feasibility of using the attributes to predict pricing of houses using regression machine learning techniques. Before that, we require to identify the attributes with high association with housing prices. Out of the 63 attributes, 36 are numerical features and 29 are categorical features. 

By applying correlation method to housing prices, the relationship of each attribute to pricing were ranked. Then it was verified in plots of the top associated and non-associated attributes which clearly showed increasing trend with pricing for associated attribute only. 

Finally, a comparison of linear regression model metric was made on using all categorical features and using categorical feature selection by Chi Square. Indeed using all categorical features pull downs the performance of the model. The method of categorical feature selecton by correlation method is comparable to the Chi Square method. 

## Python libraries requirements:
1. Pandas
2. Numpy
3. Seaborn
4. Matplotlib

## Reference:
Kaggle Boston Housing Dataset
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

## Blog link: 
https://medium.com/@hanboon82/having-more-is-better-certainly-not-for-categorical-features-8929a85a89c3
