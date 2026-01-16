Task 2: Data Cleaning and Missing Value Handling

Project Overview
In this task, I focused on the essential first step of any machine learning pipeline: Data Preprocessing. I worked with two different datasets—the "House Prices Dataset" and the "Medical Appointment No Shows"—to identify, visualize, and resolve missing data issues.

The goal was to transform "messy" raw data into a high-quality format suitable for analysis while ensuring that no critical information was lost.

Tools Used

Python: Core programming language.


Pandas: Used for data manipulation and loading datasets.


NumPy: Used for handling numerical operations.


Matplotlib/Seaborn: Used for visualizing the patterns of missing data.

My Workflow
Following the internship guidelines, I implemented the following steps for both datasets:


Data Assessment: I loaded the CSV files and used .isnull().sum() to pinpoint exactly which columns had missing information.


Visualization: I created bar charts to see the distribution of missing values, which helped me decide whether to drop or fill data.

Smart Imputation:


Numerical Columns: I used Median Imputation to fill missing values, as it is more robust against outliers than the mean.
+1


Categorical Columns: I applied Mode Imputation (most frequent value) to fill in text-based data.


Handling Sparse Data: I removed columns that had more than 50% missing values to prevent noise in the dataset.


Validation: I performed a final check to ensure the "Cleaned" versions of the datasets had zero missing values before saving them.

Files in this Repository
notebooks/Hospital price.ipynb: My Python notebook for the house price data cleaning.

notebooks/medicalappointments.ipynb: My Python notebook for the medical appointments data cleaning.


datasets/: Contains the original raw CSVs and the newly generated Cleaned_... versions.

Key Learnings
Through this task, I learned why missing data is harmful—it can lead to biased models or errors during the training phase. I also gained experience in choosing between dropping rows versus imputing values to maintain data quality.
