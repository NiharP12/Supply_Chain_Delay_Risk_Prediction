# Supply_Chain_Delay_Risk_Prediction

# Project Objective

The primary objective of this project is to predict whether a shipment will be delayed based on key supply chain parameters. By identifying the risk of delivery delays early, the model helps:

- Reduce supply chain disruptions

- Improve customer satisfaction

- Optimize logistics and planning

- Enable data-driven decision-making in shipment operations

The focus is on building a reliable and interpretable classification model using Decision Tree and Random Over Sampling to handle class imbalance. Key business variables such as shipping time, manufacturing cost, weight, and batch rating are used to train the model for accurate predictions.


# Python and ML Role

This project leverages Python and Machine Learning (ML) to automate the prediction of delivery delays in a supply chain setting. Here's how each played a role:

🔹 Python
- Data Handling: Used pandas and numpy to clean, merge, and process the data efficiently.

- Visualization: Libraries like matplotlib and seaborn were used to generate KPIs, charts, and to understand patterns in the delay data.

- Evaluation: scikit-learn provided functions to calculate model accuracy, F1-score, confusion matrix, precision, and recall.

🔹 Machine Learning
- Model Used: A Decision Tree Classifier was trained to classify whether a shipment would be delayed or not.

- Hyperparameters:

  - class_weight="balanced" — to address class imbalance.

  - random_state=42 — to ensure consistent results.

- Sampling Technique: Random Over Sampling (ROS) was applied only to the training data to increase the representation of delayed shipments and improve recall.

- Goal: Reduce false negatives (undetected delays) while maintaining high precision.

✅ Model Performance:
- Accuracy: 99.99607187594111%

- F1 Score: 99.99607793577403

- Precision: 99.99302765406706

- Recall: 99.99912840358401

This model is highly effective at predicting potential delays, helping businesses take proactive actions in the supply chain.

# Conclusion

This project used a Decision Tree model with Random Over Sampling to predict delivery delays in the supply chain. The final model achieved:

- Accuracy: 99.99%

- F1 Score: 99.99

- Precision: 99.99

- Recall: 99.99

The model is highly effective in identifying delays, helping businesses reduce risks and improve logistics efficiency.


