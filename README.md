# Mini Project 3 – Human Activity Recognition Using Machine Learning
## Author: Md Hasibul Haque Zahid
## Student ID: 2302302

## Introduction
This project aims to classify six different human activities using sensor data from smartphones. It involves applying machine learning techniques to a dataset of 3-axial linear acceleration and 3-axial angular velocity readings.

## Data Processing
The data was preprocessed through several steps:
- **Data Loading**: Ingesting the sensor data.
- **Missing Value Check**: Ensuring data completeness.
- **Standardization**: Normalizing feature scales.
- **Dimensionality Reduction**: Applying PCA to simplify the dataset.

## Steps
1. **Extracting and Loading Data**: Code provided for data extraction and loading.
2. **Missing Value Analysis**: Output for missing values and graphical representation.
3. **Data Preprocessing**: Function for preprocessing data, including PCA.
4. **Silhouette Score Analysis**: Evaluating clustering performance with silhouette scores.
5. **Clustering**: Applying K-Means and DBSCAN algorithms to the preprocessed data.

## Modeling
Two clustering algorithms were used:
- **K-Means**: With six clusters corresponding to the activities.
- **DBSCAN**: Number of clusters determined by the algorithm.

## Results
The silhouette scores indicate:
- **K-Means**: Reasonable structure with scores of 0.47 (Train) and 0.46 (Test).
- **DBSCAN**: Lack of meaningful structure with scores of -0.36 (Train) and -0.47 (Test).
## Technologies Used
- Python
- Jupyter Notebook

## Report
I have also written a detailed report based on these Project. The report provides a comprehensive overview of the Project.For more information, please refer to the report.

## Conclusion
The study provides insights into human activity recognition and demonstrates the effectiveness of machine learning techniques in classifying activities based on sensor data.

## Contact
If you have any questions or would like to discuss the project further, feel free to reach out to me.
Thank you for visiting my Project!

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
