# Predicting-Arrests-Following-Terry-Stops: Analyzing Factors Influencing Police Decision-Making

## **Introduction**

In the realm of law enforcement, Terry Stops have been a subject of ongoing debate and scrutiny since their inception following the 1968 Supreme Court case Terry v. Ohio. These brief detentions, based on reasonable suspicion rather than probable cause, have become a common policing practice but have also raised concerns about potential biases and the fine line between public safety and individual rights. This project aims to delve into the complex dynamics of Terry Stops by leveraging data analytics and machine learning techniques. Our goal is to develop a predictive model that can determine the likelihood of an arrest following a Terry Stop, based on various factors such as the presence of weapons, time of day, and potentially sensitive demographic information like race and gender.  

By analyzing this data, we seek to uncover patterns and insights that could help law enforcement agencies refine their practices, address potential biases, and strike a balance between effective policing and fair treatment of all individuals. This analysis is particularly timely given the current national discourse on police reform and racial equity in the justice system. Our approach will involve careful consideration of ethical implications, transparent methodology, and a commitment to presenting findings in a way that contributes constructively to the ongoing dialogue about fair and effective law enforcement. Through this project, we aim to provide data-driven insights that can inform policy decisions, enhance police training, and ultimately contribute to building trust between law enforcement and the communities they serve. As we embark on this analysis, we recognize the sensitivity of the subject matter and the potential impact of our findings. Our objective is not to pass judgment but to illuminate patterns and trends that can lead to more informed, equitable, and effective policing practices in the context of Terry Stops. 

## **Business Understanding**

### Problem Statement

Law enforcement agencies are facing scrutiny over their stop-and-frisk practices, particularly regarding potential biases in arrest decisions. There's a need to understand the factors that influence whether an arrest is made following a Terry Stop to ensure fair and effective policing. This project aims to use data analysis and machine learning to shed light on the factors influencing arrest decisions during Terry Stops, potentially uncovering patterns that could help improve police practices and address concerns about bias in law enforcement.

### Objectives

- Develop a machine learning model to predict whether an arrest will be made after a Terry Stop.  
- Identify key factors that contribute to arrest decisions.  
- Analyze if and how demographic factors (race, gender) correlate with arrest outcomes.  
- Provide insights to help law enforcement agencies improve their decision-making processes and address potential biases.  

### Stakeholders

- Law enforcement agencies
- Police officers
- Policy makers
- Community leaders and civil rights organizations
- General public

### Data Sources

Dataset was obtained from Seattle Government which can be accessed using this [link](https://data.seattle.gov/Public-Safety/Terry-Stops/28ny-9ts8/data_preview)  
Terry Stops dataset containing information on:  

- Presence of weapons  
- Time of day of the call  
- Demographic information (race, gender) of subjects and officers  
- Arrest outcomes  

### Ethical Considerations

- Handling sensitive demographic data responsibly  
- Addressing potential biases in the dataset and model  
- Ensuring transparency in methodology and findings  
- Considering the broader societal implications of the analysis  

### Success Criteria 

- Develop a classifier with high accuracy in predicting arrests  
- Provide actionable insights for improving police practices  
- Contribute to the ongoing dialogue about fair policing and potential biases in law enforcement  

### Methodology

1. **Data Collection and Inspection**: Gathering the necessary data from the provided dataset.
2. **Data Cleaning and Preparation**: Cleaning the data to handle missing values, outliers, and incorrect data types.
3. **Exploratory Data Analysis (EDA)**: Analyzing the data to find patterns, relationships, and insights.
4. **Data Preprocessing**: This includes `Feature Selection`, `Target Variable Encoding`, `Time Conversion` and `Categorical Encoding`.
5. **Data Splitting**: Splitting data into Training and Testing sets using the **70/30** ratio.
6. **Model Selection and Training**: Come up with model choice and model training.
7. **Model Evaluation**: Check on Accuracy and Classification Report
8. **Discussion and Next Steps**: Model Performance Analaysis and Future work