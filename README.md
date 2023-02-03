# Anaconda_Titans

# Purpose of Analysis: To Develop a Prediction Algorithm to Identify Key Diabetes Indicators

## Presentation
https://docs.google.com/presentation/d/1qGy2-b1SRxSEkdzDkbmghH16_rVRwgC2FQhMx59UZbI/edit#slide=id.g200cf861361_0_0

## Contributors
### Harriet Hammond
### Rachel Helmich
### Erasmus Quaye

## Background:
Diabetes occurs mainly in three main types: Type 1 (autoimmune disease, ~5-10% of people with diabetes), Type 2 (90-95% of people with diabetes), and Gestational (occurs only in women during pregnancy, known to increase risk for Type 2 diabetes later in life). Prediabetes is an additional condition in which blood sugar levels are higher than normal, but not high enough to count as Type 2 diabetes (~1 in 3 US adults have prediabetes). Lifestyle changes are known to be successful methods to reverse prediabetes [1]. 

For this analysis, all diabetes types will be collectively treated as diabetes occurrences together. We do recognize that Type 1 diabetes isn’t known to be preventable, as its main risk factors are genetic-based rather than lifestyle. However, 90-95% of diabetes, in addition to prediabetes cases, occur due to lifestyle risk factors. Examples of lifestyle risk factors include: amount of weekly physical activity, diet (amount of fresh fruits/vegetables), weight (overweight/obesity), ethnicity, age, number of close family members with diabetes, and other co-occurring diseases (eg. hypertension, high cholesterol, etc…) [2]. Inspiration for our 2021 analysis has been taken from a 2015 dataset analysis from Kaggle [4].

The purpose of this analysis is to review the 2021 Behavioral Risk Factor Surveillance System survey data information dataset [3]. This dataset contains 438,693 records that we have cleaned and analyzed to look at how well known risk factors indicate the occurrence of diabetes/prediabetes from our questions noted below:

1) What are the top 3-5 indicators/comorbities are found with diabetes patients?

2) How does the occurence of diabetes differ between races, genders, and both combined?

3) How well can future diabetes cases be predicted by the top indicators by training a model? 

### Sample ETL output dataset

#### 1st 40 Cleaned_Row Data Sample

![image](https://github.com/ras52017/Anaconda_Titans/blob/main/Images/1st%2040%20Cleaned_Row%20Data%20Sample.jpg)

#### Sample original binary dataset before split

![image](https://github.com/ras52017/Anaconda_Titans/blob/main/Images/Sample%20original%20binary%20dataset%20before%20split.jpg)

#### diabetes_binary_5050split_healt_Sample

![image](https://github.com/ras52017/Anaconda_Titans/blob/main/Images/diabetes_binary_5050split_healt_Sample.jpg)

#### Tableau Image

![image](https://github.com/ras52017/Anaconda_Titans/blob/main/Images/Anaconda_Titans%20Tableau%20Image.jpg)

## Resources:
[1] https://www.cdc.gov/diabetes/basics/diabetes.html 

[2] https://www.cdc.gov/diabetes/basics/risk-factors.html 

[3] https://www.cdc.gov/brfss/annual_data/annual_2021.html 

[4] https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

[5] https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5298897/#:~:text=Diabetes%20is%20a%20well%2Destablished,stroke%20with%20uncontrolled%20glucose%20levels. 

#### Visualization

##### Survey responses by States
![image](https://user-images.githubusercontent.com/112135658/216492957-7f6fb115-2135-4b5c-9378-774cfa86a7ae.png)

#### Racial makeup of Survey responders

![image](https://user-images.githubusercontent.com/112135658/216493805-aeebd276-da25-42ed-a8fb-7b7bb69df160.png)

#### Gender (male) diabetes count by state
![image](https://user-images.githubusercontent.com/112135658/216494368-4a330a3a-b4b1-4096-8bd4-2cdc8dd02044.png)
 
#### Gender (female) diabetes count by state
![image](https://user-images.githubusercontent.com/112135658/216494773-6c5d6674-44d8-4ca4-b39f-30e2181e11a0.png)

#### Diabetes_Indicators

![image](https://user-images.githubusercontent.com/112135658/216495917-9a3bdd49-e7d7-44ec-8fa9-761b486f8a3d.png)

