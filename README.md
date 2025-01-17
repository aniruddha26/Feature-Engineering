# Feature Engineering for Data

This repository is dedicated to learning and implementing various **feature engineering techniques** essential for **Data Science**, **Machine Learning**, and **Deep Learning** projects. Each concept is demonstrated with examples in Jupyter Notebook files.

## Repository Structure
The repository is organized into the following topics:

### 1. Handling Missing Values
- **Missing Completely at Random (MCAR)**: Methods to address data points missing independently of other variables.
- **Missing at Random (MAR)**: Techniques to handle missingness dependent on observed data.
- **Missing Not at Random (MNAR)**: Strategies to handle data missing due to an unobserved reason.

Notebook: [Handling Missing Values](/Handling_Missing_Values.ipynb)

### 2. Handling Imbalanced Dataset
- **Up Sampling**: Techniques to oversample the minority class.
- **Down Sampling**: Methods to undersample the majority class.
- **Using SMOTE (Synthetic Minority Oversampling Technique)**: A powerful technique to create synthetic samples.

Notebook: [Handling Imbalanced Data](/Handling_Imbalance_data.ipynb)

### 3. Handling Outliers
Explores methods to detect and treat outliers in data to ensure robust model performance.

Notebook: [Handling Outliers](/Handling_Outlier.ipynb)

### 4. Data Encoding
- **Nominal/One-Hot Encoding**: Encoding categorical variables with one-hot vectors.
- **Label and Ordinal Encoding**: Converting categories into integers.
- **Target Guided Ordinal Encoding**: Encoding categories based on their relationship to the target variable.

Notebook: [Data Encoding](/Data_Encoding.ipynb)

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/aniruddha26/Feature-Engineering
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Prerequisites
Ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook
- Required libraries: pandas, numpy, scikit-learn (specified in `requirements.txt`)

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request with any enhancements or fixes.

## License
This repository is licensed under the MIT License.

## Acknowledgments
- Inspiration: Practical data preprocessing techniques for machine learning.
- Libraries used: pandas, numpy, scikit-learn, imbalanced-learn.

Happy Learning! 😊
