# Fetal Health Classification

This dataset contains fetal health records with various medical features. The goal is to analyze the data, visualize important trends, and build machine learning models to classify fetal health into **Normal**, **Suspect**, and **Pathological** categories.

## Dataset Overview
-**Number of Features:** 21

-**Target Variable:** fetal_health (1- Normal, 2- Suspect, 3- Pathological)

-**Total Samples:** 2126

-**Data Type:** all features are numerical

## Exploratory Data Analysis (EDA)
To understand the dataset better, the following EDA techniques were applied.

### Basic Inspection
-**'df.head()'**, **'df.tail()'** to examine records.

-**'df.shape'** to check dataset dimensions.

-**'df.columns'** to list all feature names.

-**'df.dtypes'** to verify data types of each column.

### Data Quality Checks
-**'df.isnull().sum()'** to check for missing values.

-**'df.describe()'** to get summary statistics of numerical features.

### Target Distribution
-**'df["fetal_health"].value_counts()'** to analyze class distribution.

### Feature Relationships
-**'df.corr()'** to compute correlation between features and identify potential dependencies.

These steps help in identifying data patterns, inconsistencies, and insights that guide feature selection and model building.
