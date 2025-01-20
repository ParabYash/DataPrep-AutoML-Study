# An Integrated Approach to Data Preprocessing and Model Building in Machine Learning
## Project Overview
This repository contains the implementation and analysis of the dissertation project titled "An Integrated Approach to Data Preprocessing and Model Building in Machine Learning". The study explores the impact of combining data preprocessing techniques with model building workflows to enhance machine learning performance. Two distinct approaches—manual workflows and AutoML—are compared for binary classification and regression problems.

The project emphasizes the significance of preprocessing strategies tailored to specific machine learning algorithms and provides a comprehensive evaluation of their effectiveness.

### Project Objectives
- Evaluate whether integrating preprocessing with model building yields better results than handling them independently.
- Investigate the correlation between specific preprocessing techniques and the performance of Decision Trees (binary classification) and Neural Networks (regression).
- Compare manual preprocessing workflows with automated AutoML pipelines to assess strengths and limitations.

### Project Structure
The repository is organized into the following sections:

#### Data Description
The datasets used in this project include synthetic and real-world data, tailored for:

- Decision Trees: Binary classification tasks.
- Neural Networks: Regression tasks.
The datasets are processed to demonstrate the application of various preprocessing techniques and their impact on model performance.

#### Data Preprocessing and Feature Engineering:

- Handling missing values.
- Encoding categorical variables.
- Scaling numerical features.
- Creating and selecting features.

#### Machine Learning Workflows:

- Manual Workflow: Custom preprocessing and feature engineering for Decision Trees and Neural Networks.
- AutoML Workflow: Automated preprocessing and model building using AutoML pipelines.

#### Model Evaluation:

- Binary classification metrics: Accuracy, AUC, and confusion matrix.
- Regression metrics: MSE, RMSE, R², and scatter plots (e.g., predicted vs. actual).

#### Results and Findings:

- Comparison of manual and AutoML workflows.
- Insights into the limitations of AutoML with complex algorithms like Neural Networks.
- Recommendations for combining manual preprocessing with automated pipelines.

### Research Paper:

- Detailed documentation of the project methodologies, findings, and conclusions.


### Key Findings
- Integrated workflows consistently outperform independent preprocessing and model building approaches.
- Manual workflows allow for greater optimization with complex algorithms like Neural Networks, especially for handling skewed target variables (e.g., using log transformations).
- AutoML provides a strong baseline for efficient preprocessing and modeling but may require manual adjustments for specific challenges.

### Technologies Used
- Programming Languages: Python
- Libraries: Scikit-learn, TensorFlow, Auto-sklearn, Pandas, NumPy, Matplotlib, Seaborn
- Evaluation Metrics: Accuracy, AUC, MSE, RMSE, R²
- Automation Tools: AutoML pipelines

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ParabYash/Integrated-ML-Workflows.git
   ```

2. **Install Required Packages**:
   Ensure you have the necessary libraries installed, including PySpark:
   ```bash
   pip install r- requiremnts.txt
   ```

3. **Run the Notebooks**:
   - Open the Jupyter notebooks (`Twitter_Sentiment_Analysis.ipynb` and `Data_Preprocessing_and_Model_Building.ipynb`) in your preferred environment (JupyterLab, Jupyter Notebook, or any other IDE).
   - Execute the cells to replicate the data analysis, preprocessing, model building, and sentiment classification.

## Repository Contents
- Jupyter Notebooks for manual and AutoML workflows.
- Sample datasets used in the analysis.
- Research paper


## Contact Information

For any questions or suggestions, feel free to contact me:

- **Email**: yashparab05@gmail.com
- **LinkedIn**: [Yash Parab](https://linkedin.com/in/yash-parab-9a5a6a209)
