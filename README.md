# KDD_Project_Group3
# Team Name: Project Group3
# Team Members: 
1.Maneesh Varma Mynam<br>
2.Tanishq Mahajan<br>
3.Nishit Saraf<br>

# Project Description:
Project investigates the relationship between mobile phone usage, academic performance, and health among university students using a dataset of students information form Kaggle. The dataset includes detailed information on students' ages, genders, mobile phone ownership, usage patterns for educational purposes, perceptions of usefulness, reported health symptoms, and overall academic performance. The aim is to understand how mobile phone usage influences students' academic success and health outcomes, offering insights into potential areas for targeted interventions.

Our project is descriptive and diagnostic in nature. We seek to elucidate current patterns and relationships within the data and diagnose potential factors influencing students' academic and health metrics. To achieve this, we will employ both unsupervised and supervised learning techniques:

<b>Unsupervised Learning:</b> We will use clustering methods, such as K-means or hierarchical clustering, to segment students into distinct groups based on their mobile phone usage patterns and health symptoms. This will help identify common profiles within the student population, such as those with heavy mobile phone use and high levels of reported health issues.

<b>Supervised Learning:</b> We will apply logistic regression to predict the perceived impact of mobile phone usage on academic performance. This method will allow us to determine how factors such as mobile phone use frequency and reported health symptoms influence students' perceptions of their academic performance.

Additionally, we will explore association rules to uncover significant relationships between mobile phone activities and health symptoms. This approach will help identify patterns and dependencies that could inform targeted recommendations for students' mobile phone usage to improve academic and health outcomes.

Overall, the project aims to provide a comprehensive analysis of how mobile phone usage affects students' academic performance and health, facilitating the development of evidence-based strategies for enhancing student well-being and academic achievement.

# Research Question: 
How does mobile phone usage affect students' academic performance and health outcomes, and which specific usage patterns and health symptoms are most closely linked to changes in perceived academic performance?

# Relevant Domain Information

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

<img width="1181" alt="image" src="https://github.com/user-attachments/assets/32d0e0ba-4675-49b6-88b1-fedc94543f09">

<b>Health Precautions Taken:</b><br>
<b>Observation:</b>The pie chart shows the different health precautions students take to mitigate the risks associated with mobile phone use, such as using blue light filters and limiting screen time.<br>
<b>Visualization:</b>
The pie chart indicates the extent to which students are aware of and take precautions against health risks associated with mobile phone use, with some taking proactive measures and others not.
<img width="1130" alt="image" src="https://github.com/user-attachments/assets/887ad418-3448-4c01-8203-ab0752028e66">

<b>Health Symptoms and Their Relationship with Academic Performance:</b><br>
<b>Observation:</b>Bar chart showing the frequency of various health symptoms and their association with perceived academic performance<br>
<b>Visualization:</b>
Determine if students experiencing more frequent symptoms (e.g., sleep disturbances, anxiety) report different impacts on academic performance.
<img width="819" alt="image" src="https://github.com/user-attachments/assets/bb95ccc1-52c2-4fcc-9406-f807d26bf92e">

<b>Relationship Between Mobile Phone Usage Patterns and Academic Performance</b><br>
<b>Observation:</b> Identify if more frequent usage is associated with better or worse academic performance.<br>
<b>Visualization:</b>
Scatter plot or box plot to analyze how different patterns of mobile phone usage for educational purposes (e.g., Sometime, Frequently, Rarely) correlate with perceived academic performance.
<img width="1113" alt="image" src="https://github.com/user-attachments/assets/a08d39c7-bfce-411b-bf6b-80bb557c2d12">

# Data Preparation
<b>1.Data Import:</b><br>
Loaded the dataset from a CSV file into a DataFrame to make it ready for analysis.<br>
<b>2.Handling Missing Values:</b><br>
Checked for and addressed missing data by either filling in gaps with default values or removing incomplete rows to ensure a complete dataset.<br>
<b>3.Data Transformation:</b><br>
<b>Categorical Encoding:</b> Converted text-based categories (e.g., mobile phone usage patterns) into numerical values for easier analysis.<br>
<b>Age Data Normalization: </b>Changed age ranges into average values to simplify the analysis.






                   







