# Predicting Life Expectancy with Neural Networks

Embark on a journey into global health insights as we explore the factors influencing life expectancy across countries. The World Health Organization's (WHO) Global Health Observatory (GHO) dataset, spanning 2000 to 2015, provides a rich tapestry of indicators encompassing immunization, mortality, economic, social, and other health-related factors.

### Project Context

In the quest to enhance life expectancy predictions, this project undertakes the task of designing, training, and evaluating a neural network model using regression. Traditionally studied variables such as demographic factors, income composition, and mortality rates are considered, alongside often-overlooked elements like immunization and human development index.

### Dataset Overview

- **Temporal Coverage:** 2000 to 2015
- **Indicators:** Immunization, Mortality, Economic, Social, Health-related Factors
- **Target Variable:** Life Expectancy (Years)

### Initial Data Exploration

To lay the groundwork, the dataset is loaded and explored. Columns are appropriately formatted, and an initial inspection provides an overview of the data's structure and statistical summary.

### Data Preprocessing

Understanding the importance of a unified approach, the 'Country' column is dropped to focus on learning general patterns applicable across countries. The data is then split into labels and features, and numerical features are standardized/normalized for consistent modeling.

### Building the Neural Network Model

With TensorFlow and Keras, a neural network model is crafted. The architecture includes an input layer, a hidden layer with 64 neurons and a ReLU activation function, and an output layer with a single neuron for regression predictions.

### Model Compilation

The model is compiled using the Mean Squared Error (MSE) loss function and Mean Absolute Error (MAE) as a metric. The Adam optimizer with a learning rate of 0.01 is employed.

### Model Training and Evaluation

The model undergoes training with 50 epochs and a batch size of 1. The validation split aids in assessing performance during training. Subsequently, the model is evaluated on the test set, and the MSE and MAE on the test data are reported.

### Key Findings

As we unravel the mysteries of life expectancy prediction, the project aims to uncover patterns that contribute significantly to this vital health indicator. Stay tuned for in-depth insights into the factors that shape the life expectancy landscape globally.

