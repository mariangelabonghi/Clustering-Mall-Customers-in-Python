# Clustering Mall Customers in Python

## Project Overview

This notebook presents a **Cluster Analysis** project in Python focused on the well-known **"Mall Customers" dataset** available on Kaggle.  

This project is part of a 3-part series published on [Towards AI](https://towardsai.net/). 
For detailed theoretical explanations and business context, please refer to the articles:  

- [Part 1](https://medium.com/towards-artificial-intelligence/the-outlier-and-feature-selection-dilemma-preparing-data-for-clustering-ebf228b5810c) : Exploratory Data Analysis, handling outliers, and feature selection using Mutual Information;
- [Part 2](https://medium.com/towards-artificial-intelligence/3-algorithms-and-4-configurations-for-customer-segmentation-4a6b244bb3c1): Identifying optimal parameters for K-Means, GMM, and Linkage methods;
- [Part 3](https://medium.com/towards-artificial-intelligence/from-math-to-marketing-validating-clusters-and-extracting-actionable-insights-264d4443ee3b): Validation, Selection, and Visualization: Evaluating metrics and extracting actionable business insights-- 



## Dataset

- **Source:** [Mall Customer Segmentation Data on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data)
- **Features:** Gender, Age, Annual Income (k$), Spending Score (1-100)

## Notebook structure:

**1. EDA, outliers and feature selection**  
**2. K-Means, Agglomerative Clustering and GMM: Looking for the Best Configuration**  
**3. Clustering Validation: assessing the quality and consistency of the identified models**  
**4. Final Evaluation and Business Insights**

Code is written in Python using pandas, numpy, matplotlib, seaborn, scipy and scikit-learn.

## Prerequisites

Before running this Jupyter Notebook, ensure you have the following installed on your system:

* **Python:** A stable version of Python (e.g., Python 3.8 or newer).
* **Git:** To clone the repository.

### Environment Setup

It is highly recommended to use a **virtual environment** to manage the dependencies for this project.

1.  **Clone the repository:**
    ```bash
    git clone the repository [https://github.com/mariangelabonghi/Clustering-Mall-Customers-in-Python.git]
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
    Your browser will open to the Jupyter interface. Navigate to the project directory and click on the main file `Mall-Customers-Dataset-Cluster-Analysis.ipynb`.

3.  **Run the Analysis:**
    Once the notebook is open, you can run the cells sequentially (e.g., using **Cell > Run All**) to:

**Note:** Ensure your data file is located in the root directory of the project.

## License

This project is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).  
See the LICENSE file for details.
