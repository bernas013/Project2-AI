# Binary Prediction of Smoker Status using Bio-Signals

This project applies supervised machine learning models to predict whether an individual is a smoker or non-smoker, based on physiological bio-signals. The dataset used is from the Kaggle competition [Binary Prediction of Smoker Status using Bio-Signals](https://www.kaggle.com/competitions/playground-series-s3e24).

## Requirements

Ensure you have the following installed:

- Python 3.7+
- Jupyter Notebook or JupyterLab
- pip (Python package installer)

### Required Python Libraries

You can install all dependencies using the following command:

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
```

> Optional but recommended for reproducibility:
```bash
pip install imbalanced-learn
```

## How to Run

1. **Clone this repository or download the project files.**

2. **Download the dataset**  
   Go to: https://www.kaggle.com/competitions/playground-series-s3e24  
   Download `train.csv` and place it in the same directory as the notebook.

3. **Launch Jupyter Notebook**  
   In your terminal or command prompt, run:

   ```bash
   jupyter notebook
   ```

4. **Open the `Project_AI_2.ipynb` notebook.**

5. **Run the cells step-by-step**  
   Follow the notebook in order: it covers data preprocessing (including class balancing, outlier handling, and feature scaling), training of four ML models (Decision Tree, k-NN, SVM, and Neural Network), and comparison of results.

## Models Used

- Decision Tree (Scikit-learn)
- k-Nearest Neighbors (Scikit-learn)
- Support Vector Machine (Scikit-learn)
- Neural Network (Keras / TensorFlow)

Each model is evaluated using Accuracy, Precision, Recall, F1-Score, ROC-AUC, and a Confusion Matrix.


## Authors

- Beatriz Sonnemberg - 202206098  
- Bernardo Brandão - 202207939  
- Pedro Marinho - 202205693
