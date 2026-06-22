## **Project Overview**

**Customer retention is a critical challenge for subscription-based digital platforms, especially in the highly competitive video streaming industry. Acquiring new customers is significantly more expensive than retaining existing ones, making early identification of potential churners essential for business sustainability and growth.**



**In this project, we focus on predicting customer churn for a video streaming service provider. Customer churn refers to users who decide not to renew their subscription after the current plan period ends. Accurately predicting churn allows companies to proactively design retention strategies, offer personalized incentives, and optimize customer engagement efforts.**



**The dataset used in this project contains approximately 2,000 customer records with 16 features, including demographic details, subscription behavior, and service usage patterns. The objective is to build a robust and interpretable classification model that determines whether a customer is likely to churn or continue their subscription.**



**Throughout this project, we emphasize not only model performance but also interpretability, data imbalance handling (using SMOTE and class weights), and modular feature selection, ensuring that the results can be confidently used for real-world business decision-making.**

### Steps for running the notebook locally

This project has been heavily refactored and modernized into a production-ready, modular engineering structure. It is fully optimized for Python 3.12+ and utilizes uv as the modern, fast package and environment manager.



1\. Create and Activate the Virtual Environment

Make sure you are in the root directory (/churn\_project). Use uv to initialize a virtual environment with Python 3.12:



uv venv --python 3.12



source .venv/bin/activate



2\. Install Project Dependencies

Install the exact, clean project requirements generated automatically based on code imports:



uv pip install -r requirements.txt

## **Execution Instructions**

To execute the entire machine learning pipeline including data preprocessing, categorical encoding, handling data imbalance, feature selection, and model training simply run the main modular engine script:



uv run python src/Engine.py



Project Structure

src/: Contains core modular Python scripts (Data preprocessing, Feature Selection, Model Training, and Engine execution).



lib/: Shared utility modules and notebooks.



input/: Raw and processed dataset files.



requirements.txt: Clean, minimal dependency list generated via static code analysis.

