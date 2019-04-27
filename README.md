# Kaggle-s-Heart-Disease-UCI-Project

In this project I will overview and analyse the UCI's Heart Disease Dataset using 14 already pre-choosen features/attributes from a total of 76 that the original Database contain.

Will start by doing some features correlations, going through some quick plot visualizations, analysing them and getting some conclusions. And then will proceed to apply several ML models to see which yields better results and finishing with a basic DNN Classifier model:

- Logistic Regression
- KNN Classifier
- Decision Tree
- Random Forest Classifier
- SVM (Support Vector Machine) ( SVC() )
- Kmeans
- Some basic DNN Classifier experiment



### Context

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date. The "target" field refers to the presence of heart disease in the patient


### Data description:

- age - age in years 
- sex - (1 = male; 0 = female) 
- cp - chest pain type
    - Value 1: typical angina 
    - Value 2: atypical angina 
    - Value 3: non-anginal pain 
    - Value 4: asymptomatic     
- trestbps - resting blood pressure (in mm Hg on admission to the hospital) 
- chol - serum cholestoral in mg/dl 
- fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) 
- restecg - resting electrocardiographic results 
- thalach - maximum heart rate achieved 
- exang - exercise induced angina (1 = yes; 0 = no) 
- oldpeak - ST depression induced by exercise relative to rest 
- slope - the slope of the peak exercise ST segment
    - Value 1: upsloping 
    - Value 2: flat 
    - Value 3: downsloping 
- ca - number of major vessels (0-3) colored by flourosopy 
- thal - 3 = normal; 6 = fixed defect; 7 = reversable defect 
- target - have disease or not (1=yes, 0=no)



### Acknowledgements

#### Creators: 

1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D. 
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D. 
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D. 
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

Donor: David W. Aha (aha '@' ics.uci.edu) (714) 856-8779



source: https://www.kaggle.com/ronitf/heart-disease-uci
