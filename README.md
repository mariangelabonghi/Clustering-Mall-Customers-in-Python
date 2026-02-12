# Clustering Mall Customers in Python

## Project Overview

This notebook presents a **Cluster Analysis** project in Python focused on the well-known "Mall Customers" dataset available on Kaggle.

## Dataset

- **Source:** [Mall Customer Segmentation Data on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data)
- **Features:** Gender, Age, Annual Income (k$), Spending Score (1-100)

## Notebook structure:

1. EDA, outliers and feature selection
2. K-Means, Agglomerative Clustering and GMM: looking for the best configuration
3. Model Selection & Validation
4. Business Insights & Final Interpretation

Code is written in Python using pandas, numpy, matplotlib, seaborn, scipy and scikit-learn.

## Prerequisites

Before running this Jupyter Notebook, ensure you have the following installed on your system:

* **Python:** A stable version of Python (e.g., Python 3.8 or newer).
* **Git:** To clone the repository.

### Environment Setup

It is highly recommended to use a **virtual environment** to manage the dependencies for this project.

1.  **Clone the repository:**
    ```bash
    git clone the repository [https://github.com/mariangelabonghi/Clustering_Mall_Customers_in_Python.git]
    cd your-k-means-repo-name
    ```
2.  **Create and activate the virtual environment:**
    * **Windows:**
        ```bash
        python -m venv venv
        .\venv\Scripts\activate
        ```
    * **macOS/Linux:**
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```
3.  **Install dependencies:**
    The project relies on libraries listed in the `requirements.txt` file. Install them using pip:
    ```bash
    pip install -r requirements.txt
    ```
	
## Usage

Follow these steps to open and run the notebook:

1.  **Launch Jupyter:**
    Make sure your virtual environment is activated (see Prerequisites). Then, start the Jupyter Notebook server:
    ```bash
    jupyter notebook
    ```

2.  **Open the Notebook:**
    Your browser will open to the Jupyter interface. Navigate to the project directory and click on the main file `Mall_Customer_segmentation_K_means.ipynb`.

3.  **Run the Analysis:**
    Once the notebook is open, you can run the cells sequentially (e.g., using **Cell > Run All**) to:

**Note:** Ensure your data file is located in the root directory of the project.

## License

This project is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).  
See the LICENSE file for details.
