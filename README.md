# Indian-Tourism-Destination-Clustering-Analysis
This project analyzes Indian tourism destinations using Machine Learning and Data Visualization techniques.  The project uses K-Means Clustering to group tourist destinations based on similarities in their tourism attractions and food locations. 


🎯 Objectives
Analyze Indian tourist destinations and their characteristics.
Clean and preprocess the tourism dataset.
Combine tourist attractions and food-location information into a text feature.
Convert text information into numerical features using TF-IDF.
Apply K-Means Clustering to identify groups of similar destinations.
Determine an appropriate number of clusters using the Elbow Method.
Evaluate clustering quality using the Silhouette Score.
Visualize clusters using PCA.
Create an interactive Power BI dashboard for tourism analysis.

🛠️ Technologies Used
Programming & Machine Learning
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Machine Learning Techniques
TF-IDF Vectorization
K-Means Clustering
PCA (Principal Component Analysis)
Elbow Method
Silhouette Score
Visualization
Matplotlib
Microsoft Power BI

🔄 Project Workflow
Raw Tourism Dataset
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Text Preprocessing
        ↓
TF-IDF Vectorization
        ↓
Elbow Method
        ↓
K-Means Clustering
        ↓
Cluster Evaluation
        ↓
PCA Visualization
        ↓
Clustered Tourism Dataset
        ↓
Power BI Dashboard


🧹 Data Preparation

The dataset was cleaned before applying machine learning techniques.

The preprocessing included:

Loading the tourism dataset using Pandas.
Checking the dataset structure and columns.
Removing duplicate records.
Preparing tourism-related text features.
Combining tourist attractions and food-location information.

🤖 Machine Learning Approach
1. TF-IDF Vectorization

Tourist attractions and food-related text information were converted into numerical representations using TF-IDF (Term Frequency–Inverse Document Frequency).

This allows the text information to be used as input for the clustering algorithm.

2. Finding the Number of Clusters

The Elbow Method was used to evaluate different values of K.

The project tested cluster values from 2 to 9 and compared their inertia values.

3. K-Means Clustering

K-Means was then applied with 4 clusters:

KMeans(n_clusters=4, random_state=42)

Each tourism destination was assigned a cluster based on the similarity of its tourism-related features.

4. Cluster Evaluation

The Silhouette Score was used to evaluate how well the destinations were separated into clusters.

5. PCA Visualization

PCA was used to reduce the feature dimensions and visualize the clusters in two dimensions.

📊 Tourism Dashboard

A Power BI dashboard was created to provide an interactive view of the tourism data and clustered destinations.

The dashboard can be used to explore:

Tourist destinations
Tourism-related characteristics
Destination clusters
Cluster distribution
Tourism insights
Destination-level analysis

The Power BI .pbix file is included in this repository for interactive exploration.

📈 Key Outcomes

The project successfully demonstrates an end-to-end workflow:

Data cleaning and preprocessing
Text feature engineering
TF-IDF transformation
Unsupervised Machine Learning
K-Means clustering
Cluster evaluation
PCA-based visualization
Power BI dashboard development

The final dataset contains a Cluster column assigning each destination to its corresponding K-Means group.

📁 Project Structure
Indian-Tourism-Destination-Clustering-Analysis/
│
├── Indian Tourism System Using K-Means.ipynb
│
├── tourist Destination Dashboard.pbix
│
├── tourism_clustered_data.csv
│
└── README.md

🚀 Future Scope

The project can be further enhanced by:

Adding hotel recommendations.
Including tourist ratings and reviews.
Integrating real-time travel information.
Building a personalized tourism recommendation system.
Developing a web application for destination recommendations.
Incorporating additional factors such as budget, travel duration, seasonality, and traveler preferences.

💡 Skills Demonstrated

Python | Pandas | NumPy | Data Cleaning | Feature Engineering | NLP | TF-IDF | K-Means | PCA | Unsupervised Learning | Machine Learning | Data Visualization | Power BI | Dashboard Development

👨‍💻 Author

Mohammed Hamza Shaikh

Data Analyst | Data Science & Machine Learning

⭐ Project Highlights

Machine Learning + NLP + Data Visualization + Business Intelligence

This project demonstrates how unstructured tourism information can be transformed into meaningful clusters and presented through an interactive analytics dashboard.
