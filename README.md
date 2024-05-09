# Customer churn prediction using Tensorflow

Using the Bank Customer Data, we can develop a ML Prediction System which can predict if a customer will leave the Bank or not, In Finance this is known as Churning.
Such ML Systems can help Bank to take precautionary steps to ensure the customer stays with the Bank.

## objective
* Finding the % of Churn Customers and customers that keep in with the active services.
* Analysing the data in terms of various features responsible for customer Churn
* Finding a most suited machine learning model for correct classification of Churn and non churn customers.

  ## Data Source

  https://github.com/alnxha7/Customer_churn_prediction_using_Tensorflow/blob/main/WA_Fn-UseC_-Telco-Customer-Churn.csv
  
### The data set includes information about:
* Customers who left within the last month – the column is called Churn
* Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
* Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
* Demographic info about customers – gender, age range, and if they have partners and dependents.

## Modeling approach

* The model uses a simple neural network architecture with TensorFlow and Keras.
* Layers include dense (fully connected) layers with ReLU activation, dropout layers for regularization, and a sigmoid output layer for binary 
  classification.
* The model is trained with binary cross-entropy loss and optimized with Adam.

## Results and Analysis
* The model achieved an accuracy of 79 % and an F1-score of 0.85 on the test set.
* Important features included contract type, monthly charges, and tenure.
* The notebooks/ directory contains additional analysis and visualizations.

## Contact
If you have questions or need support, please contact alns4rha@gmail.com

## Future Work
* Experiment with more complex neural network architectures.
* Implement hyperparameter tuning to optimize model performance.
* Create a simple web-based interface for real-time predictions.

## The Confusion_matrix of the final result is given below
  
![figure](https://github.com/alnxha7/Customer_churn_prediction_using_Tensorflow/assets/129566733/92496593-1c39-4f32-a5f4-56c941d983e1)




