# Car Evaluation Streamlit App

This Streamlit app predicts the *acceptability class* of a car based on user-selected features such as buying price, maintenance cost, number of doors, etc.

## Features
- Uses a Decision Tree Classifier
- Categorical feature encoding
- Interactive UI using Streamlit
- Fast, real-time prediction

## Dataset
The app uses the [Car Evaluation Dataset](https://archive.ics.uci.edu/ml/datasets/car+evaluation) from the UCI Machine Learning Repository.

### Features:
- *buying*: Buying price
- *maint*: Maintenance price
- *doors*: Number of doors
- *persons*: Capacity in terms of persons to carry
- *lug_boot*: Size of luggage boot
- *safety*: Estimated safety of the car

### Target:
- *class*: Car acceptability (unacc, acc, good, vgood)
