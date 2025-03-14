# Candy Defect Detection Using RNN

## Project Overview
This project aims to develop a **predictive model** that classifies candies as defective or non-defective based on time-series sensors data from the production line. Additionally, a **root cause analysis** will identify patterns in the data responsible for defects.

## Goals
1. **Defect Classification**  
   - Predict whether a candy has zero, one, or multiple defects.
2. **Root Cause Analysis**  
   - Identify specific patterns in sensor data that contribute to defects.

## Challenges & Requirements
- **Patterns vary in length** across different defects.
- **Some defects are linked to simultaneous patterns** at two sensors.
- **A recurrent neural network (RNN) is required** for both classification and root cause analysis.
- **Generalization is key** – the model should work for unseen datasets after retraining.

## Approach
1. **Data Preprocessing**  
   - Handle missing values, normalize time series, and extract relevant features.
2. **Neural Network Model**  
   - Use an RNN (e.g., LSTM, GRU) for classification and pattern recognition.
3. **Explainable Predictions**  
   - Highlight portions of the time series responsible for detected defects.
4. **Postprocessing & Visualization**  
   - Provide insights on defect causes and suggest process improvements.

## Extra Considerations
- A full solution **must explain defect causes** for a top score.
- Some logic **can be outside the neural network** for better interpretability.

## Technologies Used
- **Python**
- **TensorFlow** (RNN implementation)
- **NumPy, Pandas** (Data preprocessing)
- **Explainable AI Techniques** (Pattern identification)

## Usage Instructions
1. Load (actaully synthetically generate) time-series data from sensors.
2. Train the RNN-based model on labeled data.
3. Evaluate classification accuracy on test data.
4. Visualize detected patterns contributing to defects.

---
**Authors**: Piotr Balewski 156037, Mateusz Bernart 156072 
**Date**: January 2025
