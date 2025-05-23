# Geospatial-Analysis-of-Credit-Card-Fraudulent-Transactions


Project Description
-----------
This project aims to enhance the detection and prevention of credit card fraud by integrating geospatial analysis with traditional and advanced machine learning techniques.

System Requirements
-------------------
Core Platform: Databricks - Unified analytics platform integrating data processing, machine learning, and collaborative workflows.​

Tools: Spark with Python (PySpark) for distributed computing and efficient data transformations.​

Machine Learning: Spark MLlib used for regression, Random Forest, and Gradient Boost tasks.​




How To Run
------------
Requirements

Before starting the set up and run the system, ensure you have access to the following:

- A web browser (Chrome, Firefox, Safari, etc.) to access Databricks.
- An internet connection, as Databricks is a cloud-based platform.

Step 1: Setting Up Databricks

1. Create a Databricks Account:

- Visit Databricks and sign up for an account. You may choose a trial or an appropriate subscription depending on your needs.
- Follow the on-screen instructions to complete the account setup.

2. Create a Workspace:
- Once logged in, create a new workspace from the Databricks dashboard.
- Provide a name for your workspace and configure any additional settings as necessary.

Step 2: Configuring the Databricks Environment
1. Create a Cluster:
- In your Databricks workspace, navigate to the "Clusters" section and click "Create Cluster."
- Choose a cluster name and select the appropriate Databricks runtime that supports PySpark and Spark MLlib.
- Configure the cluster's hardware settings as required and start the cluster.
- 13.3 LTS ML Cluster is recommended.

2. Install Libraries:
- While your cluster is running, go to the "Libraries" tab within the cluster configuration.
- Install the necessary Python libraries by searching for them in the library repository or uploading them directly. 
- Key libraries might include numpy, pandas, matplotlib, and scikit-learn for data processing and visualization. Ensure that pyspark and spark-mllib are also included.

Step 3: Accessing and Running Notebooks
1. Create a Notebook:
In your workspace, click "Create" and select "Notebook."
Assign a name to your notebook and connect it to your cluster by selecting the cluster from the drop-down menu.

2. Import Project Files:
Import our pre-existing notebooks file to the project. This can be done by uploading files directly to the workspace.

3. Running the Notebook:
Open your notebook and run the cells sequentially to begin processing data, visualizing results, and training machine learning models using PySpark and Spark MLlib.


Dataset
-------
Link: https://www.kaggle.com/datasets/kartik2112/fraud-detection/code.
Download the dataset from this link, then upload in databrick database.

