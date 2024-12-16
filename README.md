# Spark Data Processing: User Log Analysis Practice

This repository contains a practice notebook where I explored **Apache Spark** and **PySpark** for processing and analyzing a user log dataset. The notebook demonstrates various data processing techniques using Spark, including data cleaning, transformations, and aggregations.

> **Note**: This notebook is based on a Kaggle notebook that I used to practice **Apache Spark**. It serves as a hands-on practice environment to familiarize myself with Spark's functionalities.

## Key Operations Performed

1. **Data Loading**:
   - Loaded the dataset using both `pandas` and `pyspark` for data exploration.
   - Displayed a sample of the dataset to inspect its structure.

2. **Data Cleaning**:
   - Removed rows with missing values in critical columns like `userId` and `sessionId`.
   - Filtered out rows where the `userId` column had empty strings.

3. **Data Transformation**:
   - Applied **Spark DataFrame** transformations such as `select()`, `dropDuplicates()`, `filter()`, and `sort()`.
   - Used **User Defined Functions (UDFs)** to extract the hour from timestamps.

4. **Data Aggregation**:
   - Grouped and aggregated data by `userId`, `hour`, and `page` to analyze user activity.

5. **Data Visualization**:
   - Converted the Spark DataFrame to a Pandas DataFrame for easier visualization.
   - Created a **scatter plot** to show the number of songs played per hour.

## Technologies Used

- **Apache Spark** (PySpark)
- **Pandas**
- **Matplotlib** (for data visualization)

## Files in the Repository

- **`spark_user_log_analysis.ipynb`**: The practice notebook that demonstrates the use of Spark for data processing and analysis.
- **`user_log.csv`**: A sample of the user log dataset used in the notebook (optional if shared).

