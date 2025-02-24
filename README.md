# 🚗 Car Price Prediction Model  

# 📌 Overview 

This project implements a machine learning model to predict car prices based on various features such as brand, model, year, mileage, engine capacity, power, and more. The dataset is preprocessed, transformed, and reduced using Principal Component Analysis (PCA) before training the model.  

# 🔍 Features  

The dataset contains the following features:  

* 📅 Year: The manufacturing year of the car.

* 📏 Kilometers Driven: The total distance the car has traveled.

* ⛽ Fuel Type: Categorical feature (Petrol/Diesel converted to numerical values).

* ⚙️ Transmission: Categorical feature (Manual/Automatic converted to numerical values).

* 👤 Owner Type: Categorical feature (First, Second, Third owner converted to numerical values).

* 🛢️ Mileage: Fuel efficiency of the car.

* 🔧 Engine: Engine capacity in CC.

* 🏎️ Power: Horsepower of the vehicle.

* 🚘 Seats: Number of seats.

* 🏷️ Brand & Model: One-hot encoded categorical variables.

# ⚙️ Data Preprocessing

* 🛠️ Handling Missing Values: Checked for and removed any missing values.

* 🔄 Feature Encoding:

* 🏷️ One-hot encoding for categorical variables like Brand and Model.

* 🔢 Label encoding for categorical features like Fuel Type, Transmission, and Owner Type.

* 📊 Feature Scaling: MinMaxScaler was used to normalize the dataset.

* 📉 Dimensionality Reduction: PCA was applied to retain 95% variance while reducing dimensions.

# 📚 Libraries Used

* 🐼 pandas for data manipulation

* 📊 seaborn for visualization

* ⚡ sklearn.preprocessing for feature scaling

* 🔽 sklearn.decomposition for PCA

* 🚨 warnings to ignore unnecessary warnings

# 🏃‍♂️ How to Run

* Install dependencies:

1. pip install pandas seaborn scikit-learn

2. 📂 Load the dataset (carsprediction.csv).

3. ▶️ Run the script to preprocess data and apply PCA.

4. 🤖 Train a machine learning model (not included in this file but can be implemented using regression algorithms like Linear Regression, Random Forest, or Gradient Boosting).

# 🚀 Next Steps

* 🎯 Train and evaluate different regression models for price prediction.

* 🔧 Optimize hyperparameters to improve model accuracy.

* 🌍 Deploy the model using a Flask/Django API or integrate with a web application.
