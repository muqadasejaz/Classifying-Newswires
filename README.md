# Classifying Newswires: A Multiclass Text Classification Example

This project classifies Reuters newswires into 46 topics using a neural network built with Keras. It includes data preprocessing, model training, evaluation with confusion matrix, and predictions on new data.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Overview
This project demonstrates multiclass text classification using the **Reuters newswire dataset (1986)**.  
The task is to classify short news articles into **46 mutually exclusive topics** using a neural network built with **Keras**.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Features
- Preprocessing and vectorization of textual data
- One-hot encoding of class labels
- Feed-forward neural network with two hidden layers
- Training/validation accuracy and loss visualization
- Confusion matrix and classification report
- Prediction on new unseen data

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🎯 Objectives
- Learn multiclass classification with neural networks
- Implement one-hot encoding for categorical labels
- Train a dense neural network with **softmax** activation
- Evaluate model performance beyond accuracy

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tools & Technologies
- Python 3  
- Keras / TensorFlow  
- NumPy  
- Matplotlib, Seaborn  
- scikit-learn

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Dataset
- **Reuters dataset** (`keras.datasets.reuters`)  
- 8,982 training samples, 2,246 test samples  
- Each sample is a list of word indices mapped to one of **46 topics**

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Results
- Achieved **~80% test accuracy**
- Confusion matrix highlights class imbalance

- Training and Validation loss:

  <img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/038eedc2-bd08-422e-89db-39d15657c341" />

- Training and Validation Accuracy:

  <img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/cc5ad286-2d3f-467c-be02-5ea9ce40d3f0" />

- Confusion Matrix(top 10 classes):

  <img width="793" height="708" alt="image" src="https://github.com/user-attachments/assets/f40e434c-bd94-43e5-9c0c-f45ad6c7601c" />

- Prediction on test data:

  <img width="976" height="458" alt="image" src="https://github.com/user-attachments/assets/6eaa4644-6255-4e9d-b5d3-4ee1e00ae6c9" />


  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📚 References

- Chollet, F. *Deep Learning with Python*, Manning Publications, 2017  
- [Keras Reuters Dataset Documentation](https://keras.io/api/datasets/reuters/)  
- [scikit-learn Metrics](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.metrics)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧑‍🎓 Semester Assignment – Deep Learning Course(Spring 2024)

This project was submitted as part of my Deep Learning (DL) course semester assignment.
It showcased the implementation of a multiclass text classification model using the Reuters dataset

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 👤 Author

Muqadas Ejaz

BS Computer Science (AI Specialization)

AI/ML Engineer

Data Science & Gen AI Enthusiast

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)  

🌐 GitHub: [github.com/muqadasejaz](https://github.com/muqadasejaz)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).
