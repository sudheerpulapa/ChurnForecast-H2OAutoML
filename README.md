# PredictiveBankChurn: Automated Customer Attrition Forecasting with H2O AutoML

![Project Banner](https://github.com/sudheerpulapa/ChurnForecast-H2OAutoML/blob/main/customerchurn.png)

## Project Overview

### Context
Churn, a measure of customer inactivity or disengagement over time, is evident through various data facets such as the recency of account actions or shifts in the account balance.

### Aim
This study seeks to achieve the following objectives:

- **Identify and Visualize Factors Influencing Customer Churn:**
  Explore and visually represent the factors contributing to customer churn.

- **Build a Predictive Model:**
  Develop a predictive model with the following goals:

  - Classify customers into churn or non-churn categories.
  - Ideally, select a model that assigns a probability to churn, facilitating targeted customer service efforts.

### Approach
Utilizing Artificial Neural Network (ANN) models and H2O AutoML, we aim to leverage advanced techniques for accurate predictions.

### Project Timeline
1. **Data Analysis:**
   Thoroughly analyze the dataset to gain insights into the underlying patterns and characteristics.

2. **Feature Engineering:**
   Enhance the dataset by extracting meaningful features to improve model performance.

3. **ANN Model Building:**
   Develop and train Artificial Neural Network models to classify customer churn.

4. **H2O AutoML Model Building and Prediction:**
   Employ H2O AutoML for comprehensive model exploration and prediction, considering its automation capabilities.

This structured approach ensures a systematic progression from data exploration to advanced model building, providing valuable insights into customer churn dynamics.

## Understanding the Sequential Model

The Sequential model is well-suited for a straightforward stack of layers in which each layer possesses precisely one input tensor and one output tensor.

### When to Use the Sequential Model:

- **Single Input and Single Output:** The Sequential model is appropriate when your neural network architecture follows a linear stack structure with a single input tensor and a single output tensor.

### When Not to Use the Sequential Model:

- **Multiple Inputs or Outputs:** Avoid using the Sequential model when dealing with neural networks that have multiple inputs or multiple outputs.
- **Layers with Multiple Inputs or Outputs:** The Sequential model is not suitable if any of your layers involves multiple inputs or outputs.
- **Layer Sharing:** If you require layer sharing within your model architecture, the Sequential model may not be the best choice.
- **Non-Linear Topology:** For models with non-linear topology, such as those involving residual connections or multi-branch structures, it's advisable to explore other model architectures beyond the Sequential model.

## Model Building and Evaluation

### Used H2O AutoML

Assessment of Model Performance: The stacked ensemble model demonstrates promising performance based on the provided details. It achieves competitive metrics on both training and cross-validation data, with relatively low error values and a reasonable R-squared value. Further evaluation using domain-specific criteria and additional analysis tools is recommended for a comprehensive understanding of its effectiveness.

## File Structure

- `notebooks/`
  - [`basic_eda.ipynb`](https://nbviewer.org/github/sudheerpulapa/ChurnForecast-H2OAutoML/blob/main/1.Bank_Customer_Churn_Prediction_EDA.ipynb): Contains data ingestion and basic EDA
  - [`advanced_eda_feature_engineering_model.ipynb`](https://nbviewer.org/github/sudheerpulapa/ChurnForecast-H2OAutoML/blob/main/2.Churn_Pred_Feature_Eng_Model_Build.ipynb): Covers data ingestion, advanced EDA, feature engineering, model building, training, prediction, and evaluation using H2o AutoML

## Author

**Sudheer Chowdary Pulapa**
- [LinkedIn](https://www.linkedin.com/in/sudheer-chowdary-a2530a150/)
- [GitHub]([https://github.com/yourgithubusername](https://github.com/sudheerpulapa))

---

Feel free to customize the structure and content according to your project's specifics. This is a general template to help you present your work effectively.
