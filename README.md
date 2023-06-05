# Instagram Fake Account Detection

## Dataset

The dataset used for this project is stored in the file `instagram_fake_detection.csv`. It contains information about various Instagram profiles, including follower count, following count, biography length, media count, and other features. The dataset has been preprocessed and cleaned.

## Data Preprocessing

Before applying machine learning algorithms, the dataset is preprocessed to handle missing values, remove unnecessary columns, and perform feature scaling. Descriptive statistics and correlation analysis are also performed to gain insights into the data.

## Machine Learning Models

Several machine learning models are implemented to classify fake Instagram accounts. The models used in this project include:

- XGBoost Classifier
- AdaBoost Classifier
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM) Classifier

The models are evaluated using accuracy, precision, and recall scores. Cross-validation is used to assess the performance of the models.

## Usage

To use this code, follow these steps:

1. Clone the repository to your local machine.
2. Install the required libraries mentioned in the code.
3. Run the code in a Python environment, such as Jupyter Notebook or an IDE like Anaconda.
4. Make sure the dataset file (`instagram_fake_detection.csv`) is in the same directory as the code file.
5. Execute the code step by step to preprocess the data, train the models, and evaluate their performance.

## Results

The performance of each model is evaluated using accuracy, precision, and recall scores. The results are visualized using bar plots to compare the performance of different models.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The dataset used in this project is obtained from [source].
- [Credits to libraries or resources used]

Please feel free to contribute to this project by suggesting improvements or submitting pull requests.
