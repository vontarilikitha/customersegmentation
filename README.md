**Customer Segmentation and Analysis Using Clustering**
**Project Overview**
This project focuses on analyzing customer data from a marketing campaign to understand customer behavior and segment them into clusters using machine learning techniques. The data analysis involves data cleaning, feature engineering, visualization, and clustering using algorithms like K-Means and Agglomerative Clustering.

The dataset used in this project is the "Customer Personality Analysis" dataset, which includes various attributes related to customer demographics, purchase behavior, and response to marketing campaigns.

**Dataset**
**Name**: Customer Personality Analysis (Marketing Campaign)
**Source**: Kaggle Dataset
**Description**: The dataset contains information on customers such as their demographics, purchase behaviors, and responses to various marketing campaigns.
**Files**
**marketing_campaign.csv**: The main dataset file used for analysis.
**script.py**: The Python script containing the code for data analysis, preprocessing, clustering, and visualization.
**README.md**: This file providing an overview and instructions for the project.
**Installation**
To run this project locally, you'll need to have Python installed along with several Python libraries. Follow the steps below to set up your environment:

**1. Clone the Repository**
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
**2. Install Python and Required Libraries**
Make sure you have Python installed. You can download Python from the official website: https://www.python.org/downloads/.
Install the required Python libraries using pip:
pip install numpy pandas matplotlib seaborn scikit-learn yellowbrick
**3. Run the Script**
Once the dependencies are installed, you can run the script using:
python script.py
Make sure the marketing_campaign.csv file is in the correct path as mentioned in the script or update the path accordingly.

**Code Structure**
**1. Importing Libraries**
The script begins by importing necessary libraries such as numpy, pandas, matplotlib, seaborn, and various modules from scikit-learn for data manipulation, visualization, and machine learning.
**2. Data Loading and Cleaning**
The data is loaded from marketing_campaign.csv using pandas.
Missing values are removed to ensure data quality.
Date columns are converted to datetime objects for better handling.
**3. Feature Engineering**
New features are created to enhance the dataset, such as:
Age: Calculates the current age of the customer.
Spent: Computes the total spendings on various products.
Customer_For: Calculates how long the customer has been with the company.
Family_Size: Determines the number of family members in the customer's household.
Is_Parent: Flags whether the customer has children.
**4. Data Visualization**
The script uses matplotlib and seaborn to visualize various aspects of the data, such as the distribution of features and the relationships between them.
A correlation matrix is plotted to understand the relationships between features.
**5. Data Preprocessing**
Categorical variables are encoded using LabelEncoder.
Features are scaled using StandardScaler to normalize the data for clustering.
**6. Dimensionality Reduction**
Principal Component Analysis (PCA) is used to reduce the dimensionality of the dataset for visualization and clustering purposes.
**7. Clustering**
The script uses the K-Means algorithm and Agglomerative Clustering to segment the customers into different clusters.
The Elbow Method is employed to determine the optimal number of clusters.
**8. Evaluation and Visualization of Clusters**
Clusters are visualized in a 3D scatter plot to assess their separability and characteristics.
Count plots and scatter plots are used to further analyze the properties of the clusters.
**Conclusion**
This project provides insights into customer behavior and segments them into distinct clusters based on their demographic and purchasing patterns. This can help the company to better target its marketing strategies and improve customer retention.
