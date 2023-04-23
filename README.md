# SC1015_A137_T2_MiniProject
Car Price Prediction
This is a machine learning project that aims to predict the prices of cars based on various features such as manufacturer, model, mileage, and engine volume. The project involves data cleaning, exploratory data analysis, feature engineering, and model selection to develop an accurate predictive model.

Dataset
The dataset used in this project is the Car Price Prediction dataset from Kaggle (https://www.kaggle.com/datasets/jahaidulislam/car-specification-dataset-1945-2020). It contains information on over 10,000 cars, including their specifications and prices.

Dependencies
The project requires the following dependencies:

Python 3.6+
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
TensorFlow
Keras

Usage
To run the project, first ensure that all dependencies are installed. Then, clone the repository and navigate to the main directory. Run the following command to train and evaluate the predictive model:

A137_Team2_TA_MOZHANFENG.ipynb
This will load the data, perform data cleaning and preprocessing, and train and evaluate the model. The results will be displayed in the console.

Results
The project resulted in the development of two predictive models: a Random Forest Regression model and a Deep Learning model using Keras. Both models were able to predict car prices with a high degree of accuracy, achieving an R-squared value of over 0.8 on the testing set.

After comparing the different models, including Random Forest Regression, Deep Learning using Keras, Gradient Boosting, XGBoost, and Linear Regression, we found that Random Forest Regression had the best results. However, it should be noted that Random Forest Regression has many hyperparameters that need to be fine-tuned, which can be challenging for beginners. Therefore, we would recommend Deep Learning models to beginners, as they have fewer hyperparameters to tune and can still achieve high R-squared values, making them easier to work with.

Conclusion
In conclusion, this project demonstrates the effectiveness of machine learning techniques in predicting car prices based on various features. The results suggest that both Random Forest Regression and Deep Learning models can be effective in this domain. We also explored the effectiveness of several machine learning models for predicting car prices based on various features.