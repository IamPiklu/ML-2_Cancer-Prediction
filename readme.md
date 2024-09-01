# Breast Cancer Prediction using Logistic Regression

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Latest-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Latest-red.svg)

This project demonstrates the use of logistic regression to predict breast cancer diagnoses based on tumor characteristics. It utilizes the Breast Cancer Wisconsin (Diagnostic) Data Set from scikit-learn.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Overview

The project aims to classify breast cancer tumors as either benign or malignant using logistic regression. It includes data exploration, model training, and evaluation steps, providing insights into the effectiveness of using mean radius and mean texture as predictive features.

## Features

- Data loading and exploration using pandas and seaborn
- Logistic regression model implementation with scikit-learn
- Model evaluation using various metrics:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC-AUC Score
- Visualization of the ROC curve
- Function to predict cancer diagnosis for new patients

## Installation

To run this project, you need Python 3.x and the following libraries:

```bash
pip install scikit-learn pandas seaborn matplotlib
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/breast-cancer-prediction.git
   cd breast-cancer-prediction
   ```

2. Open and run the Jupyter notebook:
   ```bash
   jupyter notebook cancer\(logisticReg\).ipynb
   ```

3. To predict cancer for a new patient, use the `predict_cancer` function:
   ```python
   mean_radius = 14.0  # Replace with actual values
   mean_texture = 10.0  # Replace with actual values
   diagnosis, probability = predict_cancer(mean_radius, mean_texture)
   print(f"Diagnosis: {diagnosis}")
   print(f"Probability of being malignant: {probability:.2f}")
   ```

## Model Evaluation

The model's performance can be assessed through various metrics provided in the notebook:

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- ROC-AUC Score
- ROC Curve Visualization

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

For any questions or issues, please open an issue on the GitHub repository.