# Pre Interview Acceptance

## Overview

This project aims to predict the likelihood of an individual being accepted for an interview based on various features using machine learning techniques. The model is built using logistic regression, and the dataset is analyzed for insights and visualizations.

## Dataset

The dataset used in this project can be found [here](https://www.kaggle.com/code/raneemrefaie/pre-inerview-acceptenes/data).

## Requirements

To run this project, you'll need the following Python libraries:

- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the necessary packages using the provided `requirements.txt` file.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/AndranikAdyan/pre_inerview_acceptenes
   cd pre_inerview_acceptenes
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from the provided Kaggle link and save it as `logatta.csv` in the project directory.

## Usage

### Google Colab

1. Go to [Google Colab](https://colab.research.google.com/).

2. Click on `File` > `Upload notebook` and upload the notebook file (`.ipynb`) from the repository. 

3. To access the dataset, use the file upload interface in Colab:
   - Click on the folder icon on the left sidebar.
   - Click the upload button and select `logatta.csv` from your local machine.

4. Execute the code cells in the notebook. Follow the instructions within the notebook to run the analysis and model training.

5. Optionally, you can use Google Drive to store and access the dataset:
   - Click on `Files` in the left sidebar, then `Mount Drive` to connect your Google Drive.
   - Move or copy the dataset to a folder in your Drive and update the file path in the notebook.

### Jupyter Notebook

1. Install Jupyter Notebook if you haven't already:
   ```bash
   pip install notebook
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open the notebook file (`.ipynb`) from the Jupyter interface.

4. Ensure that the dataset (`logatta.csv`) is in the same directory as the notebook file.

5. Execute the code cells in the notebook. Follow the instructions within the notebook to run the analysis and model training.