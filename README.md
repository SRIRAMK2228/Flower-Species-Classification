# 🌸 Flower Species Classification

<img width="1000" height="447" alt="cD6ccKKMJJW8rENfe_51518iris img1" src="https://github.com/user-attachments/assets/35f2f6a3-aaf5-4f23-b756-58c38d431df4" />


## Tools used🛠: Python, Machine Learning, Scikit-learn, Seaborn, Matplotlib

## 🎯 Objective

- The goal of this project is to build a machine learning model that classifies flowers into Setosa, Versicolor, or Virginica species using their sepal and petal measurements. This classic Iris dataset is a benchmark problem in pattern recognition and classification.

## 💡 Why We Use It

- Flower classification plays an important role in:

- Botanical research and taxonomy

- Automated plant recognition systems

- Agriculture and biodiversity monitoring

- Building baseline models for supervised classification tasks

- This project provides a strong foundation for beginners to understand data preprocessing, feature engineering, and supervised machine learning classification.

## ✅ Step-by-step Approach
### 📥 Importing Libraries & Dataset

- Imported essential libraries such as NumPy, Pandas, Seaborn, Matplotlib, and Scikit-learn.

- Loaded the Iris dataset from Seaborn’s built-in datasets.


### 🧹 Data Cleaning

- Verified dataset shape and column values.

- Checked for missing/null values (none found).

- Explored class distribution of species (Setosa, Versicolor, Virginica).

### 🔍 Exploratory Data Analysis (EDA)

- Visualized sepal length vs. sepal width and petal length vs. petal width using scatter plots.

- Used boxplots to study feature distributions.

- Identified clear separation patterns:

- Setosa is easily distinguishable due to smaller petals.

- Versicolor and Virginica overlap but can be separated with petal width/length.

### 🧠 Feature Engineering

- Converted species (categorical target) into numerical labels (0 = Setosa, 1 = Versicolor, 2 = Virginica).

### 📊 Model Training

- Split dataset into training (75%) and testing (25%) using train_test_split.

- Scaled features with StandardScaler for normalization.

- Trained a Logistic Regression model on the training data.

### 🧪 Model Testing & Evaluation

- Predicted flower species on the test set.

- Evaluated using:

- Classification Report (precision, recall, F1-score)

- Accuracy Score

- Confusion Matrix (visualized using heatmap)

#### ✅ Achieved high accuracy in classifying the three flower species.

## Output 


<img width="222" height="633" alt="1" src="https://github.com/user-attachments/assets/9697f1fb-2852-4950-aa67-44447a52fb3f" />


<img width="680" height="252" alt="2" src="https://github.com/user-attachments/assets/e6f1c0ae-000c-4d8f-8261-e4d9260d9583" />


<img width="312" height="136" alt="3" src="https://github.com/user-attachments/assets/db54005b-8fbf-4bc5-9136-31016558bd2d" />


<img width="842" height="446" alt="4" src="https://github.com/user-attachments/assets/33b05de5-59ae-4511-b81f-eb27c6c62a00" />


<img width="842" height="444" alt="5" src="https://github.com/user-attachments/assets/507ab63a-26b3-46bb-bd91-13ca9023d6b9" />


<img width="216" height="172" alt="6" src="https://github.com/user-attachments/assets/05444ae5-89a6-43a2-83b4-e24bbbe1b159" />


<img width="842" height="425" alt="7" src="https://github.com/user-attachments/assets/df88d778-de23-4d37-9c82-dae090d303be" />

<img width="830" height="425" alt="8" src="https://github.com/user-attachments/assets/f29f89f2-3145-4c89-a15a-7a7665e335ab" />


<img width="842" height="425" alt="9" src="https://github.com/user-attachments/assets/a9f8d0e0-53ec-4e3a-97fb-c21ce6c943c0" />


<img width="842" height="425" alt="10" src="https://github.com/user-attachments/assets/b7d8c257-6745-4c86-80f9-cbf1a0324afb" />


<img width="1136" height="890" alt="11" src="https://github.com/user-attachments/assets/b9f23613-b2bc-42e5-96a9-0500571282cb" />


<img width="261" height="887" alt="12" src="https://github.com/user-attachments/assets/9f5b3254-085e-4469-8f6f-7b45b20a9d04" />


<img width="235" height="550" alt="13" src="https://github.com/user-attachments/assets/722a1836-c60c-4484-8c6b-eb6f5b2c7189" />
