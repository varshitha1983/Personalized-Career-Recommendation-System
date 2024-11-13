# Personalized Career Recommendation System

## Project Overview
The **Personalized Career Recommendation System** is a machine learning project designed to recommend career paths based on user data. This system analyzes input features such as skills, interests, and educational background to predict suitable career choices. The project involves data generation, preprocessing, and modeling using a Random Forest classifier to deliver accurate career recommendations.

## Dataset
For this project, we created a custom dataset containing features relevant to career recommendation. To reflect real-world data irregularities, we added controlled noise to the dataset. Key data generation and preprocessing steps include:

- **Noise Addition**: Artificial noise was added to simulate real-world inaccuracies and variations.
- **Data Splits**: The dataset was divided into training and testing sets to evaluate model performance.

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
We performed a thorough EDA to understand data distributions, identify patterns, and detect outliers. Key EDA steps include:
- Statistical summaries
- Data visualization for feature distributions and relationships
- Correlation analysis to understand relationships between variables

### 2. Data Preprocessing
Data preprocessing steps were critical to clean and prepare the data for modeling:
- **Encoding**:
  - One-hot encoding for categorical variables with no inherent order.
  - Ordinal encoding for categorical variables with a defined order.
- **Feature Scaling**: Applied where necessary to ensure consistency in model inputs.

### 3. Dimensionality Reduction
- **Principal Component Analysis (PCA)** was applied to reduce dimensionality while retaining essential information. This step improved model efficiency and minimized overfitting risks.

### 4. Model Development
- **Model Selection**: A Random Forest Classifier was chosen due to its effectiveness in handling diverse feature types and reducing overfitting.
- **Training**: The model was trained using the preprocessed dataset.

### 5. Evaluation Metrics
- **Accuracy**: Calculated to provide a general measure of prediction correctness.
- **Classification Report**: Includes precision, recall, and F1-score for each class, providing a comprehensive view of model performance.
- **Confusion Matrix**: Visualized to reveal correct vs. incorrect predictions and insights into model strengths and weaknesses.

## Results
The model achieved a high accuracy, indicating its effectiveness in predicting career recommendations. Detailed performance metrics, including the classification report and confusion matrix, demonstrate its ability to handle diverse data with noise.

## Project Files
- `dataset/`: Folder containing the custom dataset.
- `Dataset_creation/`: Code file for custom dataset creation.
- `EDA and model/`: Code file for model implementation and evaluation.
- `README.md`: Project overview and instructions (this file).

## License
This project is licensed under the MIT License.
