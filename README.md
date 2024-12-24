<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
<h1 align="center">Diabetes SVM Model</h1>
<h3 align="center">A simple SVM model for predicting diabetes based on patient data.</h3>

<p align="center" style="display:flex; gap:16px; justify-content:center; align-items:center">
<a href="https://www.python.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original-wordmark.svg" alt="python" width="80px" height="80px"/></a>
<a href="https://jupyter.org/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="80px" height="80px"/></a>
</p>

## Project Description

This project implements a Support Vector Machine (SVM) model to predict the presence of diabetes in patients based on various health parameters. The model is trained on a dataset containing patient information such as pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age.

## Prerequisites

-   Python 3.11
-   Jupyter Notebook
-   Required Python libraries: scikit-learn, pandas, numpy, matplotlib

## Setup

1.  Clone the repository:

    ```bash
    git clone https://github.com/tareqWpy/diabetes-svm-model.git
    ```

2.  Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

3.  Activate the virtual environment:

    For Windows:

    ```bash
    venv\Scripts\activate
    ```

    For macOS and Linux:

    ```bash
    source venv/bin/activate
    ```

4.  Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to the **diabetes.ipynb** notebook file in the Jupyter interface.<br>
Run the notebook cells sequentially to train the SVM model and evaluate its performance.<br>
You can also use the trained model to make predictions on new patient data by modifying the input values in the notebook.<br>

## Data

The dataset used in this project is sourced from the UCI Machine Learning Repository: Pima Indians Diabetes Database. It contains information about female patients of Pima Indian heritage and their diabetes status.<br>
Results
The SVM model achieves an accuracy of approximately 77% on the test set. The precision and recall scores are also reported in the notebook.<br>

## License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, feel free to contact the project maintainer:<br>
Email: taregh.khaleghi1381@gmail.com<br>
GitHub: [tareqWpy](https://github.com/tareqWpy)<br>
