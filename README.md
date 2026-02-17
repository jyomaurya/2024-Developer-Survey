<img width="1150" height="647" alt="image" src="https://github.com/user-attachments/assets/5e577ce6-2464-4528-a359-fbb78f6b334e" />

## United States:High Income Developers

<img width="1151" height="656" alt="image" src="https://github.com/user-attachments/assets/89bea6bf-4ce8-499b-a255-8715d29101b1" />

## India: High Income Developer

<img width="1155" height="637" alt="image" src="https://github.com/user-attachments/assets/9bc72e92-c40f-4e7e-abf5-cbbc6112a182" />


# Developer Salary & Experience Clustering Analysis

## Project Overview
This project uses the **2024 Stack Overflow Developer Survey** data (65,000+ respondents) to analyze the relationship between professional experience and compensation using ** Machine Learning (Clustering)**.

## Key Insights
- **Clustering Quality:** Used **Silhouette Score** to validate the grouping of developers into High and Low-income segments.
- **Salary Trends:** Visualized how 'YearsCodePro' directly impacts yearly compensation across different developer roles.
- **Educational Impact:** Analyzed the distribution of developer types based on their education levels (Bachelor's, Master's, etc.).

## Tools Used
- **Power BI:** Data Cleaning (Power Query), ETL, and Dashboarding.
- **Machine Learning:** K-Means Clustering & Silhouette Analysis.
## Conclusion & Key Findings

Based on the analysis of 65,000+ developer records:
* **Experience & Pay**: There is a strong positive correlation between 'YearsCodePro' and salary, particularly in the High-Income cluster.
* **Clustering Success**: The data naturally split into two distinct groups, with the High-Income group averaging **$151.85K** compared to **$42.48K** in the Low-Income group.
* **Education**: While a Bachelor's degree is most common, higher education levels show a higher density in the top-earning clusters.
* **Accuracy**: The **Silhouette Score** validates that the groupings created via Python are distinct and reliable.
* **Data Preprocessing**: Handled complex categorical data using ColumnTransformer and One-Hot Encoding in Python.
* **Advanced Analytics**: Implemented K-Means Clustering to segment developers into High-Income and Emerging Professional groups.
* **Model Validation**: Achieved a Silhouette Score of 0.273, validated through PCA (Principal Component Analysis) and Hierarchical Clustering to ensure statistically solid groupings.

## Major Findings:

Experience is Key: Professional maturity (YearsCodePro) and Job Role (DevType) are the primary drivers for salary growth, more so than formal education alone.

Role Density: High-income clusters show a significant density of Full-stack and Back-end developers with 2-10 years of experience.

Global Trends: Visualized clear compensation gaps between different geographical regions and clusters.
