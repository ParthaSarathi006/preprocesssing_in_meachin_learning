#preprocesssing_in_meachin_learning
This repository contains a step-by-step walkthrough of data preprocessing techniques commonly used in machine learning workflows. The notebook demonstrates how to handle missing values, detect and treat outliers, encode categorical variables, and scale numerical features.

📁 Dataset
The dataset used in this notebook is named preprocessing_dataset.csv. It should be stored in your Google Drive for Colab access.

📋 Key Concepts Covered


🔍 1. Data Inspection
Loading the dataset using Pandas

Displaying data structure with .info() and .head()

Identifying missing values using:

data.isnull().sum()

missingno visualizations (bar, matrix)

seaborn heatmap

🛠️ 2. Handling Missing Values
Numerical columns:

Salary filled with mean

Age filled with median

Categorical column:

Gender filled with mode

Also demonstrated use of SimpleImputer for more scalable missing value handling

📦 3. Outlier Detection
IQR Method: Identify values outside 1.5 × IQR

Z-Score Method: Detect extreme values (z > 2.5)

🔄 4. Encoding Categorical Variables
Used One-Hot Encoding with pd.get_dummies() for the Department column

(Optional code commented for LabelEncoder and OneHotEncoder from sklearn)

📏 5. Feature Scaling
Standardization using StandardScaler

Normalization using MinMaxScaler

🧪 Libraries Used
numpy

pandas

seaborn

matplotlib

missingno

scikit-learn

scipy

🚀 How to Use
Clone the repo or download the notebook.

Upload the dataset to your Google Drive at the path:

bash
Copy
Edit
/content/drive/MyDrive/preprocessing_dataset.csv
Run the notebook in Google Colab or Jupyter Notebook.

🖥️ Output
Cleaned and preprocessed dataset, ready for machine learning model training.

📌 Important Notes
Ensure that Google Drive is mounted correctly when running in Colab.

You can customize the imputation or encoding techniques depending on your dataset.

Use boxplots and statistical methods to choose appropriate outlier handling techniques.

📄 License
This project is open-source and available under the MIT License.

🙌 Acknowledgements
Scikit-learn Documentation

Missingno Visualization Library

Seaborn and Matplotlib for data plotting
