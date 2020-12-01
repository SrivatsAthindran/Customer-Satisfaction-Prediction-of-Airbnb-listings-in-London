# Customer-Satisfaction-Prediction-of-Airbnb-listings-in-London
## Project description:
This aim of this project is to identify significant features that impact customer ratings of Airbnb London using several classification models ranging from the simple regression models to the complex deep learning models, and to evaluate the best model which is able to predict the customer rating most accurately by using ROC curve metrics and accuracy.

SHAP (SHapley Additive exPlanations) is performed on the best performing model to explain the individual predictions.

Latent Dirichlet Allocation (LDA) was performed on the textual listing review dataset to derive additional insights. 

Raw data downloaded from InsideAirbnb website for London city : http://insideairbnb.com/get-the-data.html

- Processed data is used for the prediction models and the LDA topic model (Refer to Data Preprocessing-London_v3.2.ipynb in 'Codes' folder for the preprocessing and processed_data folder for the processed data)

- Codes folder contain python codes for EDA, LDA, various prediction models and for additional resampling methods tried on the models.
