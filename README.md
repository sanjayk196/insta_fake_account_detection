# Instagram Fake Account Detection

## Overview
This repository contains code for detecting fake Instagram accounts using machine learning algorithms. The project aims to classify Instagram profiles as real or fake based on various features such as follower count, following count, biography length, and media count.

![Fake Account Detection](fake_account_detection.png)

## Dataset
The dataset used for this project is stored in the file [`instagram_fake_detection.csv`](link_to_dataset). It consists of a collection of Instagram profiles labeled as either real or fake. The dataset has been preprocessed and cleaned, ready for use in the machine learning models.

## Data Preprocessing
Before applying machine learning algorithms, the dataset is preprocessed to handle missing values, remove unnecessary columns, and perform feature scaling. Descriptive statistics and correlation analysis are performed to gain insights into the data. You can find the preprocessing code in the [`data_preprocessing.ipynb`](link_to_data_preprocessing) notebook.

## Machine Learning Models
Several machine learning models are implemented for classifying fake Instagram accounts. These models include:

- XGBoost Classifier
- AdaBoost Classifier
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM) Classifier

The models are trained on the preprocessed dataset and evaluated using accuracy, precision, and recall scores. Cross-validation is used to assess their performance. You can find the code for training and evaluating the models in the [`fake_account_detection.ipynb`](link_to_fake_account_detection) notebook.

## Usage
To use this code, follow these steps:

1. Clone the repository: `git clone [repository_url]`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the code in a Python environment such as Jupyter Notebook or Anaconda.
4. Make sure the dataset file [`instagram_fake_detection.csv`](link_to_dataset) is in the same directory as the code file.
5. Execute the code step by step to preprocess the data, train the models, and evaluate their performance.

## Results
The performance of each model is evaluated using accuracy, precision, and recall scores. The results are visualized using bar plots to compare the performance of different models. You can find the results and visualizations in the [`results.ipynb`](link_to_results) notebook.

![Model Comparison](model_comparison.png)

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- The dataset used in this project is obtained from [source](link_to_dataset_source).
- The [scikit-learn](https://scikit-learn.org/) library was used for implementing the machine learning models.
- The [Pandas](https://pandas.pydata.org/) library was used for data preprocessing and analysis.
- The [Matplotlib](https://matplotlib.org/) library was used for data visualization.

Contributions to this project are welcome. Please feel free to suggest improvements or submit pull requests.

![Contributions Welcome](contributions_welcome.png)
