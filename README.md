# Impact Analysis of Mobile Phone Usage on Academic Performance and Health Outcomes in Students
# Team Name: Project Group3
# Team Members: 
1.Maneesh Varma Mynam<br>
2.Tanishq Mahajan<br>
3.Nishit Saraf<br>

# Project Introduction:
The "Students Health & Academic Performance" dataset explores the complex relationship that links the health behaviors—specifically, the use of mobile phones—of students and their academic performance. This dataset consists of multiple rows, each of which represents a student, and has columns that included personal data, mobile phone usage patterns, impact on education, health awareness, and symptoms associated with it. The purpose of this study is to investigate the relationship between students' use of mobile phones and their health and academic performance.

As the data is of this kind, our study aims to be both predictive and diagnostic. Our goals are to identify existing trends and connections in the dataset and estimate the potential effects of particular actions on academic achievement. This study will discover important determinants of academic achievement and health by using supervised learning techniques, including classification and logistic regression. In order to distinguish between various student groups based to their usage habits and health effects, we will also look into clustering.
# Research Question: 
How does mobile phone usage affect students' academic performance and health outcomes, and which specific usage patterns and health symptoms are most closely linked to changes in perceived academic performance?

# Relevant Domain Information
<b>Article:</b><a href=https://courses.lumenlearning.com/readinganthology/chapter/the-relationship-between-cell-phone-use-and-academic-performance-in-a-sample-of-u-s-college-students-by-andrew-lepp-jacob-e-barkley-and-aryn-c-karpinski>The Relationship Between Cell Phone Use and Academic Performance</a><br>
Above article study examines how mobile phone usage affects academic performance among university students, analyzing patterns and outcomes related to mobile phone habits and academic achievement. <br>

<b>Article:</b><a href=https://www.semanticscholar.org/paper/The-effects-of-mobile-phone-use-on-academic-A-Kates-Wu/593c59df1d77f700a8b469c9712f321b2889be8e>The effects of mobile phone use on academic performance</a><br>
This article review examines how using technology, especially mobile phones, affects students' academic performance and overall well-being. It combines results from various studies to give a clear picture of how mobile phone use impacts students' education and health.
# Data Source and Description

Our initial review of the dataset reveals comprehensive details on students’ mobile phone usage, academic performance, and health outcomes. The dataset includes attributes such as demographic information, mobile phone ownership, usage patterns for educational purposes, health symptoms, and academic performance metrics.

Key observations from the dataset include:

<b>Demographic Distribution:</b>
The dataset encompasses a diverse age range and gender distribution, providing a representative sample of the student population.<br>
<b>Mobile Phone Ownership and Usage Patterns:</b>
Almost all students own mobile phones, with varied usage frequencies for educational purposes. Some use their phones frequently for learning activities, while others use them less often.
The types of activities include online research, educational apps, and email, highlighting the multifaceted ways students integrate mobile phones into their academic routines.<br>
<b>Perceptions of Academic Impact:</b>
Students have varied opinions on whether mobile phone use benefits or detracts from their academic performance. This variation suggests that the impact of mobile phones on academic success may differ based on usage patterns and individual circumstances.<br>
<b>Health Symptoms and Precautions:</b>
A range of health symptoms related to mobile phone use, such as sleep disturbances, headaches, and anxiety, are reported by students. The frequency of these symptoms varies, with some students experiencing them regularly.
Precautions taken to mitigate health risks include using blue light filters, limiting screen time, and taking breaks, though not all students adopt these measures.

# Exploratory Data Analysis (EDA)
Below are some key visualizations and insights obtained from the data:<br>
<b> Impact of Mobile Phone Use on Academic Performance:
</b><br>
<b>Observation:</b>Analyze the distribution of responses regarding how mobile phone use affects academic performance (e.g., Positive, Neutral, Negative).<br>
<b>Visualization:</b>
Bar chart showing students' perceptions of how mobile phone use impacts their academic performance.

<img width="879" alt="image" src="https://github.com/user-attachments/assets/53e07c61-fde5-4959-a6bc-9490a58f01e0">






<b>Health Precautions Taken:</b><br>
<b>Observation:</b>The pie chart shows the different health precautions students take to mitigate the risks associated with mobile phone use, such as using blue light filters and limiting screen time.<br>
<b>Visualization:</b>
The pie chart indicates the extent to which students are aware of and take precautions against health risks associated with mobile phone use, with some taking proactive measures and others not.
<img width="814" alt="image" src="https://github.com/user-attachments/assets/0bc764ab-9ba2-41a7-aae8-0982d1be0005">




<b>Health Symptoms and Their Relationship with Academic Performance:</b><br>
<b>Observation:</b>Bar chart showing the frequency of various health symptoms and their association with perceived academic performance<br>
<b>Visualization:</b>
Determine if students experiencing more frequent symptoms (e.g., sleep disturbances, anxiety) report different impacts on academic performance.
<img width="903" alt="image" src="https://github.com/user-attachments/assets/5bbb6035-d709-45f3-8e65-6f6b8c12aa0e">



<b>Relationship Between Mobile Phone Usage Patterns and Academic Performance</b><br>
<b>Observation:</b> Identify if more frequent usage is associated with better or worse academic performance.<br>
<b>Visualization:</b>
Scatter plot or box plot to analyze how different patterns of mobile phone usage for educational purposes (e.g., Sometime, Frequently, Rarely) correlate with perceived academic performance.
<img width="923" alt="image" src="https://github.com/user-attachments/assets/547d584b-9523-41d3-a6c8-099ade28833e">




# Data Preparation
<b>1.Data Import:</b><br>
Loaded the dataset from a CSV file into a DataFrame to make it ready for analysis.<br>
<b>2.Handling Missing Values:</b><br>
Checked for and addressed missing data by either filling in gaps with default values or removing incomplete rows to ensure a complete dataset.<br>
<b>3.Data Transformation:</b><br>
    <b>Categorical Encoding:</b> Converted text-based categories (e.g., mobile phone usage patterns) into numerical values for easier analysis.<br>
    <b>Age Data Normalization: </b>Changed age ranges into average values to simplify the analysis.<br>
    <b>Daily usages Normalization: </b>Convert Daily usages to a numerical format:This approach makes your data ready for analysis or machine learning models by transforming qualitative descriptions into quantitative values.<br>


The data preparation involves importing and cleaning the dataset, converting categorical and numerical data into usable formats, creating new features for better analysis, and handling outliers. These steps made the dataset ready for detailed exploration and modeling.Normalization makes your data easier for machine learning algorithms to work with by putting features on the same scale. This helps in improving the model’s performance and speeds up its learning process.

# Data Splitting for Modeling
Data splitting is a critical step in getting your data ready for machine learning. It entails dividing your data into two parts: one to train the model and the other to test how well the model performs. This ensures that the model is tested on new data that it has not previously encountered, giving a better idea of how well it can handle new situations.<br>
<b>Split the Data:</b><br>
<b>Training Set:</b> This subset of data is used to train the model. It assists the model in determining the relationship between features and the target variable.<br>
<b>Test Set:</b> This portion is set aside and used to assess the model's performance. It ensures that the model can generalize to new, previously unseen data sets.<br>
Splitting your data into training and test sets is a key step in building a strong machine learning model. It allows you to check how well the model works and ensures it can handle new, unseen data effectively.

# Modeling
Using various modeling techniques, we investigated the impact of mobile phone usage on students' academic performance and health. We began with PyCaret, a tool that facilitates the testing and comparison of various machine learning models. PyCaret made it simple to set up our data and test different models to determine which one performed best. We also used <b>Logistic Regression ,GBM, DecisionTreeClassifier and Random Forest models</b>, which are well-known for their accuracy when classifying data.<br>

We first prepared the data by changing text into numbers and fixing any missing or incorrect details. After setting up and running different models, we checked how well each one worked by measuring their accuracy. PyCaret helped us by giving a clear summary of each model’s performance, allowing us to pick the most accurate one for predicting academic performance.<br>

Next, we used K-Means clustering to group students based on their phone usage and health information. This method helps us find patterns and similarities among students with similar phone habits. We then visualized these groups to see how students are clustered and to discover important trends.<br>

We compared the performance of various models to determine which one made the best predictions. We obtained a comprehensive picture of how mobile phone usage affects students by employing both classification models and clustering methods. This method assisted us in understanding phone usage patterns and their impact on students' academic performance and health. Simply put, this method allowed us to examine how various phone habits relate to students' grades and well-being.

# Evaluation
In our evaluations, both the Gradient Boosting Classifier and the Decision Tree Classifier performed admirably, with perfect accuracy and other metrics. With an accuracy of 75%, the Random Forest Classifier produced inconsistent results across classes, indicating that it may require additional adjustments. Logistic regression had the poorest performance, with an accuracy of 71% and lower precision and recall than the other models.<br>
We also used K-Means clustering to classify students based on their phone usage and health status. This clustering allowed us to identify patterns and similarities between students. The clustering visualizations revealed a correlation between students' daily phone usage and health symptoms. Overall, the Gradient Boosting Classifier made the most accurate predictions, while the clustering analysis revealed useful information about how phone usage affects students.

# Conclusion
The Gradient Boosting and Decision Tree Classifiers were very effective at predicting student outcomes with high accuracy. The Random Forest Classifier didn’t do as well and needs adjustments. Logistic Regression performed the worst, with lower accuracy and weaker results. K-Means clustering, however, showed us useful patterns in how students use their phones and its impact on their health and school performance.

# Known Issues
The analysis has limitations in certain aspects. One issue is data imbalance, which occurs when specific categories in the target variable have insufficient examples. This can reduce model accuracy for underrepresented categories and lead to biased results. <br>
Moreover, the Gradient Boosting and Decision Tree models had perfect accuracy, which could indicate that they were overfitting. This means that they may perform exceptionally well with training data but poorly with new data. The Random Forest Classifier produced inconsistent results, indicating that it may require some adjustments to function properly. Logistic regression performed poorly, most likely because its simpler design made it unable to handle the complexity of the data. <br>
K-means clustering might not find all patterns if the number of clusters isn’t right, which can affect how useful the insights are. The conversion and normalization of features may result in errors or oversimplify the data, which could affect the model's performance. The data might have biases or errors from when it was first collected, which can impact how well the models work and their results. Additionally, complex models like gradient boosting can be hard to understand, making it difficult to see why they make certain predictions.

# Instructions
<b>Python Version:</b><br>
This project is based on Python 3.10(for the use of Pycaret).<br>
<b>Platform:</b><br>
This file was developed to be used with Google Colab or Jupyter Notebooks.<br>
<b>Required Packages</b><br>
pandas: For data manipulation and analysis.<br>
scikit-learn: For machine learning algorithms and tools.<br>
matplotlib: For plotting and visualizing data.<br>
pycaret: For easy machine learning model setup and comparison.<br>
<b>Packages to be installed:</b> Seaborn, GradientBoostingClassifier, classification_report, accuracy_score, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, and KMeans.<br>
This thorough approach will help us understand how mobile phone usage affects students' academic performance and health. By using both classification models and clustering techniques, we can gain valuable insights and identify key patterns.
