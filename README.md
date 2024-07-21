# bank-marketing-prediction
A machine learning project to predict whether a client will subscribe to a term deposit based on data from direct marketing campaigns of a Portuguese banking institution. The project includes data preprocessing, feature engineering, model training, evaluation, and error analysis using PyTorch and Scikit-Learn.

## Dataset
The dataset is sourced from [UCI Machine Learning Repository](https://data.world/data-society/bank-marketing-data) and includes information on clients' attributes and the outcome of direct marketing campaigns.

## Model
The model is implemented using PyTorch and includes the following key steps:
- Data standardization and encoding
- Custom neural network architecture
- Training loop with logging of loss and accuracy
- Model evaluation using accuracy, confusion matrix, and other relevant metrics

## Results
The model's performance is evaluated on the test dataset, and the results are summarized in terms of accuracy, precision, recall, F1-score, and confusion matrix. Detailed analysis and visualizations are included in the notebook `SubscribeToTermDeposit.ipynb`.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
