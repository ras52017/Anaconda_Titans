# Anaconda_Titans

# Purpose of Analysis: To Develop a Prediction Algorithm to Identify Key Diabetes Indicators

## Presentation
https://docs.google.com/presentation/d/1qGy2-b1SRxSEkdzDkbmghH16_rVRwgC2FQhMx59UZbI/edit#slide=id.g200cf861361_0_0

### Tableau public Link
https://public.tableau.com/app/profile/harriet.oppong/viz/Anaconda_Titans1__/Diabetes_Prediction?publish=yes

## Contributors
### Harriet Hammond
#### GitHub: https://github.com/HarrietHammond
#### LinkedIn:https://www.linkedin.com/in/harrietoppong

### Rachel Helmich
#### GitHub: https://github.com/midwestbotanist
#### LinkedIn: https://www.linkedin.com/in/rachel-helmich-809293ba/

### Erasmus Quaye
#### GitHub: https://github.com/ras52017
#### LinkedIn: https://www.linkedin.com/in/erasmusquaye

## Background:
Diabetes occurs mainly in three main types: Type 1 (autoimmune disease, ~5-10% of people with diabetes), Type 2 (90-95% of people with diabetes), and Gestational (occurs only in women during pregnancy, known to increase risk for Type 2 diabetes later in life). Prediabetes is an additional condition in which blood sugar levels are higher than normal, but not high enough to count as Type 2 diabetes (~1 in 3 US adults have prediabetes). Lifestyle changes are known to be successful methods to reverse prediabetes [1]. 

For this analysis, all diabetes types will be collectively treated as diabetes occurrences together. We do recognize that Type 1 diabetes isn’t known to be preventable, as its main risk factors are genetic-based rather than lifestyle. However, 90-95% of diabetes, in addition to prediabetes cases, occur due to lifestyle risk factors. Examples of lifestyle risk factors include: amount of weekly physical activity, diet (amount of fresh fruits/vegetables), weight (overweight/obesity), ethnicity, age, number of close family members with diabetes, and other co-occurring diseases (eg. hypertension, high cholesterol, etc…) [2]. Inspiration for our 2021 analysis has been taken from a 2015 dataset analysis from Kaggle [4].

The purpose of this analysis is to review the 2021 Behavioral Risk Factor Surveillance System survey data information dataset [3]. This dataset contains 438,693 records that we have cleaned and analyzed to look at how well known risk factors indicate the occurrence of diabetes/prediabetes from our questions noted below:

1) What are the top 3-5 indicators/comorbities are found with diabetes patients?

2) How does the occurence of diabetes differ between and within races, genders, and both combined?

3) How well can future diabetes cases be predicted by the top indicators by training a model? 

## Conclusion
-  Features looked at include: 
    - Cholesterol levels
    - High blood pressure
    - Physical activity
    - Smokers
    - Race/gender differs on diabetes occurrences, demographics play a significant role
- Logistic Regression model has a 73% accuracy at predicting diabetes
- Diabetes is a disease that can occur due to a variety of genetic, environmental, and lifestyle factors, limiting the level accuracy a model can reach

## Future Recommendations
- Potential improvement upon the logistic regression model could be to review original dataset and seek out additional features known to be risk factors/comorbidities of diabetes
- Expand the analysis to look at more diseases captured within the larger CDC dataset
- Expand the analysis to look at the larger CDC dataset for disease-prevention indicators, leading to predicting behaviours diabetic patients can utilize to prevent/reverse diabetes (under doctor supervision)


## ETL
### Sample ETL output dataset

#### 1st 40 Cleaned_Row Data Sample

![image](https://github.com/ras52017/Anaconda_Titans/blob/main/Images/1st%2040%20Cleaned_Row%20Data%20Sample.jpg)

#### Sample original binary dataset before split

![image](https://github.com/ras52017/Anaconda_Titans/blob/main/Images/Sample%20original%20binary%20dataset%20before%20split.jpg)

#### diabetes_binary_5050split_healt_Sample

![image](https://github.com/ras52017/Anaconda_Titans/blob/main/Images/diabetes_binary_5050split_healt_Sample.jpg)

## Visualizations

![image](https://user-images.githubusercontent.com/112135658/216868954-d5cd1860-1418-40d2-80f9-b22b9a01675d.png)

## Machine Learning
![diabetes_logistic_regression_model](https://user-images.githubusercontent.com/101941048/216856428-0023d8d8-9096-46ec-9006-adef497dcadf.png)
![diabetes_neural_network_accuracy_loss](https://user-images.githubusercontent.com/101941048/216856429-c2294731-d327-43a7-ae69-6d6641c2832f.png)
![diabetes_confusion_matrix](https://user-images.githubusercontent.com/101941048/216856430-897c2ddc-8b30-428f-9e68-e30d02169deb.png)


## Languages/Tools/Algorithms
### Languages:
- Python (for ETL and Machine Learning)
    - from sklearn:
        - sklearn.model_selection (import train_test_split)
        - sklearn.preprocessing (import StandardScaler,OneHotEncoder)
        - sklearn.linear_model (import LogisticRegression)
        - sklearn.metrics (import accuracy_score)
    - Pandas
    - Numpy
    - OS
    - Random 
    - Tensorflow


### Tools:
- Visual Studio Code

- Tableau

- GitHub

- Google Slides

- Google Sheets

### Algorithms:
- Logistic Regression

- Neural Networking


## Resources:
[1] https://www.cdc.gov/diabetes/basics/diabetes.html 

[2] https://www.cdc.gov/diabetes/basics/risk-factors.html 

[3] https://www.cdc.gov/brfss/annual_data/annual_2021.html 

[4] https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

[5] https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5298897/#:~:text=Diabetes%20is%20a%20well%2Destablished,stroke%20with%20uncontrolled%20glucose%20levels. 
