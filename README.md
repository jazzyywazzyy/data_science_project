# Data Exploration

***Data Types***
The following columns contain integers 
- Diabetic
- HeartRate
- Age
- Cognitive_Test_Scores
- Dementia

The following columns contain floats 
- AlcoholLevel
- BloodOxygenLevel
- BodyTemperature
- Weight
- MRI_Delay
- Dosage in mg

The following columns are objects 
- Prescription
- Education_Level
- Dominant_Hand
- Family_History
- Smoking_Status
- APOE_e4
- Physical_Activity
- Depression_Status
- Mediation_History
- Nutrition_Diet
- Sleep_Quality
- Chronic_Health_Conditions
--- 
***General information*** 
The dataset contains 1000 entries 
Null values can only be found in the columns Prescription & Dosage in mg (515 null values) -> the Na values in Prescription were changed to "No Prescription" 

***Demographic Data** 
Age, Weight, Gender, Dominant hand 
- Age ranges from 60 to 90 with a mean of 74.91
- Weight ranges from 50 t0 90kg with a mean of 74.32kg
- 504 women (50.4%)
- 496 men (49.6%)
- 519 left-handed (51.9%)
- 481 right-handed (48.1%)

***Health Data***
Diabetic, heart rate, alcohol level, blood oxygen level, body temperature 
- 513 suffer from diabetes (51.3%)
- 487 with no diabetes (48.7%)
- heart rate ranges from 60 to 100 with a mean of 79.383 beats per minute
- alcohol level ranges from 0.00 to 0.1999 with a mean of 0.0984
- blood oxygen level ranges from 90.01 and 99.999 with a mean of 95.23
- body temperature ranges from 36.00 to 37.5 with a mean of 36.76

***Prescription data***
- 11.3% or 113 individuals take Donepezil
- 12.5% or 125 individuals take Galantamine
- 12.8% or 128 individuals take Memantine
- 11.9% or 119 individuals take Prvastigmine
- 51.5% or 515 individuals take no medication

***Genetics***
History of medication, chronic diseases, APOE_e4 allel, family history 
- 514 or 51.4% have history of medication
- 486 or 48.6% have no history of medication
- 513 or 51.3% have diabetes
- 155 or 15.5% have heart disease
- 153 or 15.3% have hypertension
- 179 or 17.9% have no chronic disease

APOE_e4 Allel 
- 694 or 69.4% with allel
- 306 or 30.6% without allel

Family history of dementia 
- 520 or 52% with family history
- 480 or 48% without family history

Lifestyle choices 
Physical activity, smoking status, nutrition diet, sleep quality 

physical activity
- sedenary: 331 = 33.1%
- mild activity: 351 = 35.1%
- moderate activity: 318 = 31.8%
  
smoking status 
- former smoker: 458 = 45.8% 
- never smoked: 452 = 45.2%
- current smoker: 90 = 9%
  
diet
- mediterranean diet: 338 = 33.8% 
- balanced diet: 332 = 33.2% 
- low-carb diet: 330 = 33%
  
sleep quality
- good sleep: 446 = 46.6% 
- bad sleep: 534 = 53.4%

***cognitive*** 
Dementia, depression, cognitive test scores, education level 

dementia
- no dementia: 515 = 51.5% 
- dementia: 485 = 48.5%
  
depression
- depression: 245 = 24.5% 
- no depression: 755 = 75.5%
  
education level
- primary school: 389 = 39.9% 
- secondary school: 304 = 30.4% 
- no school: 155 = 15.5% 
- dimploma / degree: 152 = 15.2% 
