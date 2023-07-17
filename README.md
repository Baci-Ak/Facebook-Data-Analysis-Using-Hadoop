# Facebook-Data-Analysis-Using-Hadoop
<img width="889" alt="Screenshot 2023-07-17 at 1 17 53 AM" src="https://github.com/Baci-Ak/Facebook-Data-Analysis-Using-Hadoop/assets/134199508/e0fe68a2-c40b-4eae-8efb-f1a8aeab9dc0">


## 📝 Description
* The aim of this project is to leverage the capabilities of the Hadoop ecosystem to gain valuable insights from Facebook data. The project aims to analyze user behavior, engagement patterns, and social network dynamics within the Facebook platform. By utilizing the distributed processing and storage capabilities of Hadoop, the project seeks to handle the large-scale Facebook data and perform in-depth analysis to extract meaningful information.

  ### 📙 Dataset
* link to the dataset [facebook_dataset](https://github.com/Avani10/Facebook-Data-Analysis/blob/master/pseudo_facebook.csv)

#### 💻 Installation
* configuration and setup for hadoop ecosystem [Hadoop conf](https://github.com/Baci-Ak/Hadoop_conf)

##### 🛠️ Requirement
* Hadoop
* Apache Hive
* Apache Nifi
* python3

###### 🪜 Steps:
* Data Collection: located the representative dataset of Facebook data, including user profiles, posts, comments, likes, shares, and friend connections.
    
* Data Ingestion and Storage: Utilized Apache Nifi to ingest the Facebook data from the source into Hadoop. Stored the data in Hadoop Distributed File System (HDFS) for efficient and scalable storage.
    
*  project structure onto the data stored in the hdfs using apache hive.
* Connect Apache hive with python to access hive tables for preprocessing
* Data Preparation: Preprocess the data by cleaning and transforming it into a structured format suitable for analysis. removed null values using linear interpolation cleaning.
* export the cleaned data to hdfs and updated hive table with the clean data, ready for analysis
* Data Exploration and User Behavior Analysis: Utilized Apache Hive to explore the data and perform user behavior analysis. Write queries  to understand user engagement patterns and other aspects of user behavior to answer key project questions.

###### 🚠* Key Qestions
1.	Find out how many users there are in the dataset overall?
2.	the total number of Facebook users who are over 18?
3.	Do male users have more friends on average than female users
4.	How many more likes do young individuals get on Facebook than do older users?
5.	Do youthful members use their mobile phones or laptops to browse Facebook?
6.	Find out the number of Facebook users for each birthday month.
7.	Do adult Facebook users browse the site on their phones or computers?





   





    
