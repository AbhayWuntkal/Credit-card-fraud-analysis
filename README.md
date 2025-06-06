# Credit Card Fraud Detection

<p> With millions of credit card transactions being processed, financial fraud is increasing, putting the company at high risk. Traditional rule-based fraud detection systems are failing to adapt to new fraud techniques. Companies might seeks a machine learning model that can accurately identify fraudulent transactions in real time, with minimal false positives.<p/>

•	Data pre-processing and cleaning for each dataset. <br>
•	Exploratory Data Analysis (EDA) using Python(Jupiter notebook) and Numpy, Matplot Lib, Seaborn.<br>
•	Implementation of machine learning models (Random Forest, Logistic Regression, etc.)<br>
•	Testing same models on Hyperparameter tuning for improving results.<br>
•	Evaluating models using metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.<br>
•	Testing final best model on unseen dataset (test dataset).<br>

# Result & Conclusion 

# Random Forest After Hyperparameter Tuning.

![image](https://github.com/user-attachments/assets/1704ab91-aa8d-4327-9246-21101d3cd9ee)

![image](https://github.com/user-attachments/assets/d4ff5070-fcc2-49ca-a081-1b7791e7ab3c)

| ![Image 1](https://github.com/user-attachments/assets/1704ab91-aa8d-4327-9246-21101d3cd9ee) | ![Image 2](https://github.com/user-attachments/assets/d4ff5070-fcc2-49ca-a081-1b7791e7ab3c) |
|----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|

# Random Forest on Unseen Data (Test Dataset)

![image](https://github.com/user-attachments/assets/10df9155-9228-4265-9a3e-646231125fc6)

![image](https://github.com/user-attachments/assets/7872838c-a201-4500-9505-5d13abf12c85)

# Results

<p>The Random Forest classifier, especially after hyperparameter tuning, achieved exceptionally high performance on the test dataset with a 99.96% accuracy and ROC-AUC score of 0.9996, effectively distinguishing between fraudulent and non-fraudulent transactions.<p/> 

<p>While performance on the unseen dataset was slightly lower (ROC-AUC of 0.9224), it still confirmed the model's robustness and real-world applicability. This solution significantly reduces potential financial losses and improves transaction security.<p/>

# Conclusion

### Top Performing Models:
•	Random Forest <br>
•	Decision Tree <br>
•	KNN Classifier <br>
•	LightGBM <br>

**Why they performed well:** 

•	These models can super good at figuring out complicated patterns and non-linear relationships very well. <br>
•	Tree-based models are particularly excellent for tabular data with mixed types (categorical + numerical).<br>
•	KNN which stands for K-Nearest Neighbors leverages a similarity metric, performing optimally when instances of fraud are distinctly separable based on their defining characteristics. <br>
•	LightGBM is gradient-boosted decision trees, optimized for speed and performance. <br>
•	It handles categorical and numerical features efficiently.<br>
•	Slightly lower precision/recall than Random Forest due to underfitting or limited iterations before tuning. <br>

