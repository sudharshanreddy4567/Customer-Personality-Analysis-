# Customer-Personality-Analysis-
📋 Project Description
🗂 Dataset Overview
📁 File: marketing_campaign.csv
📊 Rows: 2,240
📋 Columns: 31
I Have used Numpy,pandas, matploatlib,seaborn in python to made this project.
In this project, I worked with a customer marketing campaign dataset to prepare it for further analysis and modeling. The dataset contained information about customers, their demographic details, purchasing behavior, and their response to various marketing campaigns.

The first step was to import the dataset into Google Colab using the file upload method. Once the data was loaded, I performed an initial exploration to understand the structure, check for missing values, identify duplicates, and get a feel for the overall data quality.

I identified and handled missing values, particularly in the Income column, by replacing them with the median income value. This ensures that missing data does not distort any future analysis.

Next, I checked for and removed duplicate rows and duplicate columns to avoid redundancy and ensure clean data.

Since some columns were stored as object types (text-based), I converted them into proper string types for easier handling and consistency. I then standardized all text values across the dataset — this involved removing extra spaces, converting all text to lowercase, and ensuring uniform formatting. This step was especially important for columns like Gender, Education, and Marital Status to avoid inconsistencies like “Single” vs “single”.

I also cleaned the column names by making them lowercase and removing special characters or unnecessary underscores to make them more consistent and easier to reference in code or analysis.

The date column Dt_Customer, which records when each customer joined, was formatted into a standard datetime format to allow for future time-based analysis such as customer tenure or segmentation based on joining date.

Overall, the goal of this phase was to ensure that the dataset is clean, consistent, and analysis-ready. By carefully preprocessing the data, I've set a solid foundation for further exploration, visualization, or building predictive models.

Let me know if you'd like help writing a follow-up section once you do EDA or modeling!









Done
