## Installation and Usage

Follow these steps to set up the project environment and run the analysis.

### 1. Setup

First, clone the repository to your local machine and navigate into the project directory:

```bash
git clone <your-repository-url>
cd <repository-name>
```

Next, it is recommended to create a virtual environment to keep the project dependencies isolated.

```bash
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies

Install all the required Python libraries using the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

The `requirements.txt` file should contain:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

*(**Note**: If you don't have a `requirements.txt` file, you can create one in your activated virtual environment by running `pip freeze > requirements.txt`)*

### 3. Running the Analysis

The entire analysis is contained within the Jupyter Notebook: `Netflix_churn_prediction.ipynb`.

1.  Ensure you have Jupyter Notebook or JupyterLab installed (`pip install notebook`).
2.  Launch the notebook server from your terminal:
    ```bash
    jupyter notebook
    ```
3.  Your web browser will open a new tab. Navigate to and open the `Netflix_churn_prediction.ipynb` file.
4.  Run the cells sequentially from top to bottom to execute the data processing, model training, and see the evaluation results and graphs.