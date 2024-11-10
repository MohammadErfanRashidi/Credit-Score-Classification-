# Credit Score Prediction

This project aims to predict credit scores using machine learning. It utilizes a Random Forest Classifier to classify credit scores into three categories: Poor, Standard, and Good.

## Dataset

The project uses a dataset named "train.csv" containing various financial features of individuals. The features include:

- **Annual_Income:** Annual income of the individual.
- **Monthly_Inhand_Salary:** Monthly in-hand salary of the individual.
- **Num_Bank_Accounts:** Number of bank accounts held by the individual.
- **Num_Credit_Card:** Number of credit cards owned by the individual.
- **Interest_Rate:** Interest rate on loans taken by the individual.
- **Num_of_Loan:** Number of loans taken by the individual.
- **Delay_from_due_date:** Average number of days delayed by the person in making payments.
- **Num_of_Delayed_Payment:** Number of delayed payments made by the individual.
- **Credit_Mix:** Credit mix of the individual (Bad, Standard, Good).
- **Outstanding_Debt:** Outstanding debt of the individual.
- **Credit_History_Age:** Age of the individual's credit history.
- **Monthly_Balance:** Monthly balance maintained by the individual.
- **Credit_Score:** Credit score of the individual (Poor, Standard, Good).

## Methodology

1. **Data Loading and Preprocessing:**
   - The dataset is loaded using pandas.
   - Missing values are handled (if any).
   - Categorical features like Credit_Score and Credit_Mix are encoded using label encoding.

2. **Data Splitting:**
   - The dataset is split into training and testing sets using `train_test_split` from scikit-learn.

3. **Model Training:**
   - A Random Forest Classifier is used for prediction.
   - The model is trained using the training data.

4. **Model Evaluation:**
   - The model's accuracy is evaluated on the training data.

5. **Prediction:**
   - The trained model is used to predict credit scores for new data inputs.
   - Users can input their financial information, and the model predicts their credit score category.

## Usage

1. Ensure that the required libraries are installed: pandas, numpy, matplotlib, seaborn, scikit-learn.
2. Upload the "train.csv" dataset to your Colab environment.
3. Run the code cells in the notebook sequentially.
4. To predict your credit score, provide the required financial information when prompted.

## Results

The accuracy of the model on the training data is printed in the output. The predicted credit score category (Poor, Standard, or Good) is displayed for user inputs.

## Contributing

Feel free to contribute to this project by improving the model, adding new features, or enhancing the user interface.

## License

This project is licensed under the MIT License.
