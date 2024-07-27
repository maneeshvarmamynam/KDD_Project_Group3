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

<img width="1018" alt="image" src="https://github.com/user-attachments/assets/e4cad6ee-c3b8-4ab3-8bac-21ff284ccd29">


<b>Health Precautions Taken:</b><br>
<b>Observation:</b>The pie chart shows the different health precautions students take to mitigate the risks associated with mobile phone use, such as using blue light filters and limiting screen time.<br>
<b>Visualization:</b>
The pie chart indicates the extent to which students are aware of and take precautions against health risks associated with mobile phone use, with some taking proactive measures and others not.
<img width="831" alt="image" src="https://github.com/user-attachments/assets/e472a1b2-9b37-4773-ad5f-26952d7447e3">


<b>Health Symptoms and Their Relationship with Academic Performance:</b><br>
<b>Observation:</b>Bar chart showing the frequency of various health symptoms and their association with perceived academic performance<br>
<b>Visualization:</b>
Determine if students experiencing more frequent symptoms (e.g., sleep disturbances, anxiety) report different impacts on academic performance.
<img width="1035" alt="image" src="https://github.com/user-attachments/assets/e78869f9-689f-44d4-8d58-59b0cc256c4f">

<b>Relationship Between Mobile Phone Usage Patterns and Academic Performance</b><br>
<b>Observation:</b> Identify if more frequent usage is associated with better or worse academic performance.<br>
<b>Visualization:</b>
Scatter plot or box plot to analyze how different patterns of mobile phone usage for educational purposes (e.g., Sometime, Frequently, Rarely) correlate with perceived academic performance.
<img width="1159" alt="image" src="https://github.com/user-attachments/assets/7099076b-1689-4767-82fd-ea82b79ab803">


# Data Preparation
<b>1.Data Import:</b><br>
Loaded the dataset from a CSV file into a DataFrame to make it ready for analysis.<br>
<b>2.Handling Missing Values:</b><br>
Checked for and addressed missing data by either filling in gaps with default values or removing incomplete rows to ensure a complete dataset.<br>
<b>3.Data Transformation:</b><br>
    <b>Categorical Encoding:</b> Converted text-based categories (e.g., mobile phone usage patterns) into numerical values for easier analysis.<br>
    <b>Age Data Normalization: </b>Changed age ranges into average values to simplify the analysis.<br>


The data preparation involves importing and cleaning the dataset, converting categorical and numerical data into usable formats, creating new features for better analysis, and handling outliers. These steps made the dataset ready for detailed exploration and modeling.




                   







