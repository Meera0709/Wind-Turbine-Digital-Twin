# Wind-Turbine-Digital-Twin
This project creates a digital twin for a wind turbine using a deep learning model to predict turbine performance based on SCADA data. The digital twin visualizes real-time dynamic graphs using past data, providing insights into turbine operations.

Features
Load and preprocess SCADA data from wind turbines
Train a hybrid deep learning model (CNN, LSTM, GRU, etc.)
Evaluate model performance with various metrics
Serve predictions through a Flask API
Real-time dynamic graph visualization

Model Training
The model is a hybrid deep learning architecture incorporating Conv1D, LSTM, and GRU layers.
It includes dropout and batch normalization to prevent overfitting and improve generalization.
The model is trained on historical SCADA data with features such as wind speed, theoretical power curve, and wind direction, and the target variable is the turbine's active power output.
