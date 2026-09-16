# Predicting heart disease using machine learning

This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning modle capable of predicting whether or not someone has heart disease based on their medical attributes.

#### The following approaches are about to be applied
* Problem defination
* Data
* Evaluation
* Features
* Modeling
* Experimentation
## 1.Problem Defination
In a statement,
> Given clinical parameters about a patient, can we predict whether or not they have heart disease or not?

## 2. Data
The original data came from the Cleavland data from the UCI Machine Learning Repository:- https://archive.ics.uci.edu/dataset/45/heart+disease 

## 3. Evaluation
* Cross-validated precision: 82%
* Cross-validated recall: 93%
* Cross-validated f1-score: 87%


## 4. Features
* age: Age in years
* sex: Sex (1 = male; 0 = female)
* cp: Chest pain type (0 = typical angina; 1 = atypical angina; 2 = non-anginal pain; 3 = asymptomatic)
* trestbps: Resting blood pressure (in mm Hg on admission to the hospital)
* chol: Serum cholesterol in mg/dl
* fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
* restecg: Resting electrocardiographic results (0 = normal; 1 = ST-T wave abnormality; 2 = left ventricular hypertrophy)
* thalach: Maximum heart rate achieved
* exang: Exercise induced angina (1 = yes; 0 = no)
* oldpeak: ST depression induced by exercise relative to rest
* slope: The slope of the peak exercise ST segment (0 = upsloping; 1 = flat; 2 = downsloping)
* ca: Number of major vessels (0–3) colored by fluoroscopy
* thal: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
* target: Heart disease diagnosis status (1 = yes; 0 = no)
