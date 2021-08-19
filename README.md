# iowa-house-prices-prediction
 Predicting house prices in Iowa, USA using different Machine Learning Models and compared their accuracies
 
 **Libraries**: pandas, sklearn

## Project overview and details 

- Developed a tool to predict house prices in Iowa to help investors, real-estate professionals and potential house owners.
- Initial explored dataset to get an insight into their properties.
- Optimised Decision Tree models (at multiple lead nodes) and Random Forest models to get the best model and lowest Mean Absolute Error (MAE).
- Trained and validated the models on training and test dataset respectively to evaluate their accuracy. 
- This project also covers:
   - dealing with missing data (e.g. with SimpleImputer)
   - dealing with categoral variables (ordinal encoding and one-hot encoding)
   - cross validation techniques with cross_val_score
   - improving the models
   - concept of pipelines, xgboost and data leakage
    
    
## Metrics
Validation MAE when not specifying max_leaf_nodes for Decision Tree: 29,653

Validation MAE for best value of max_leaf_nodes for Decision Tree: 27,283

Validation MAE for Random Forest Model: 21,857

