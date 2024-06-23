# Machine Learning Projects

Welcome to my collection of machine learning projects! This repository contains several projects where I explore different machine learning techniques to solve various problems. Each project includes data preprocessing, model building, and evaluation.

## Table of Contents

- [Projects](#projects)
  - [Breast Cancer Prediction](#breast-cancer-prediction)
  - [Fetal Health Classification](#fetal-health-classification)
  - [House Price Prediction](#house-price-prediction)
  - [Wine Quality Prediction](#wine-quality-prediction)
  - [CIFAR-10 Image Classification](#cifar-10-image-classification)
  - [Postoperative Classification](#postoperative-classification)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Projects

### Breast Cancer Prediction

This project aims to classify whether a breast cancer tumor is malignant or benign based on the features extracted from a digitized image of a fine needle aspirate (FNA) of a breast mass.

- **Dataset**: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Algorithms Used**: Logistic Regression, SVM, Random Forest, K-Nearest Neighbors
- **Notebook**: [breast_cancer_prediction.ipynb](./breast_cancer_prediction.ipynb)

### Fetal Health Classification

This project involves classifying the health status of fetuses using cardiotocographic data.

- **Dataset**: [Fetal Health Classification Data](https://www.kaggle.com/andrewmvd/fetal-health-classification)
- **Algorithms Used**: Logistic Regression, Random Forest, K-Nearest Neighbors
- **Notebook**: [fetal_health_classification.ipynb](./fetal_health_classification.ipynb)

### House Price Prediction

Predicting house prices in Boston using various features such as the number of rooms, crime rate, etc.

- **Dataset**: [Boston Housing Data](https://www.kaggle.com/c/boston-housing)
- **Algorithms Used**: Linear Regression, Decision Trees, Random Forest
- **Notebook**: [house_price_prediction.ipynb](./house_price_prediction.ipynb)

### Wine Quality Prediction

Classifying wine quality based on its chemical properties.

- **Dataset**: [Wine Quality Data](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- **Algorithms Used**: Decision Trees, Random Forest, SVM
- **Notebook**: [wine_quality_prediction.ipynb](./wine_quality_prediction.ipynb)

### CIFAR-10 Image Classification

Classifying images into 10 different classes using the CIFAR-10 dataset.

- **Dataset**: [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
- **Algorithms Used**: SVM, Random Forest, K-Nearest Neighbors
- **Notebook**: [cifar10_classification.ipynb](./cifar10_classification.ipynb)

### Postoperative Classification

Classifying the postoperative life expectancy of patients after surgery based on various health metrics.

- **Dataset**: [Postoperative Patient Data](https://archive.ics.uci.edu/ml/datasets/Post-Operative+Patient)
- **Algorithms Used**: Logistic Regression, Random Forest, SVM
- **Notebook**: [postoperative_classification.ipynb](./postoperative_classification.ipynb)

## Installation

To run these projects locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/beura-chirantan/ML-Projects.git
   cd ml-projects
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Each project is contained within its own Jupyter notebook. To run a specific project, start Jupyter Notebook:
```bash
jupyter notebook
```
Then open the notebook of the project you are interested in and run the cells.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please submit a pull request or open an issue.

## License

This repository is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.
