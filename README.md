# Python-for-data-analysis
### Project of python for data analysis regarding the Seoul Bike Rental dataset

## Table of Contents
- Introduction
- Features
- Installation
- Usage
- Examples
- Contributing
- License
  
## Introduction
We are using the Seoul Bike Rental dataset which contains data about the number of bikes rented between 2018 and 2022 in Korea.
The goal of this project is to create a machine learning model able to predict the number of bikes rented in Korea, given certain parameters.
The dataset has a total of 18 columns :
- Rented Bike Count : Number of bikes rented at a specific day and hour
- Hour : 1 to 24 for each hour of the day
- Temperature(°C) : Temperature at a specific hour in °C
- Humidity(%)
- Wind speed (m/s)
- Visibility (10m)
- Dew point temperature (°C)
- Solar Radiation (MJ/m2)
- Rainfall(mm)
- Snowfall (cm)
- Seasons
- Holiday : Is this day a holiday
- Functioning day

## Features
The notebook is split in mainly 3 sections : the data pre processing in which we scaled and encoded our data, the data visualization used to analyse it and better understand the problem, and finally the modeling section where we created our machine learning model.

Installation
Libraries used :
sklearn : pipeline, svm, preprocessing, linear_model, isotonic, tree, discriminant_analysis, neural_network, ensemble, model_selection, metrics,
scipy : stats
pandas
numpy
seaborn
matplotlib : pyplot

Example:

bash
Copy code
pip install your_package_name

Usage
Explain how to use your machine learning model or application. Include code snippets, examples, or sample commands to demonstrate usage.

Example:

python
Copy code
from your_package_name import YourModel

# Create an instance of YourModel
model = YourModel()

# Train the model
model.fit(X_train, y_train)

# Make predictions
predictions = model.predict(X_test)
Examples
Provide additional examples or use cases that showcase the functionality of your project. This could include visualizations, sample outputs, or demonstrations.

Contributing
Explain how others can contribute to your project. Include guidelines for submitting issues, feature requests, or pull requests.

License
Specify the project's license information. This informs users about how they can use, modify, and share your project.
