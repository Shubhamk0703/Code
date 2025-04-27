
## 📋 Project Description
This project aims to predict whether a hotel booking will be canceled or not based on historical booking data.  
We used machine learning models like **Random Forest**, **XGBoost**, and **SVM** to classify cancellations.


## Importatnt libraries
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
scipy



## 📂 Dataset
- The dataset contains information about hotel bookings such as:
  - Lead time
  - Number of special requests
  - Stay duration (weekends and weekdays)
  - Customer type
  - Deposit type
  - and more.

## 🛠️ Preprocessing
- Handled missing values.
- Encoded categorical variables.
- Removed outliers using the IQR method.
- Feature scaling where necessary.

## 🔍 Models Used
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **XGBoost Classifier**

## 📊 Evaluation Metrics
- **Confusion matrix**
- **Accuracy**
- **Classification Report** (Precision, Recall, F1-Score)

## 🏆 Results
| Model         | Accuracy |
|---------------|----------|
| SVM           | 80%      |
| Random Forest | 87%      |
| XGBoost       | 89%      |

(XGBoost performed the best!)


