# Alzheimer-s-Disease

## Purpose and outcome

**Purpose:** identify risk factors and symptoms associated with Alzheimer's Disease

**Outcome:** evaluate effects of Alzheimer's Disease on the lives of patients and build a model to estimate the risk of having Alzheimer's Disease

## Data

**Source:** published in Kaggle

Link: https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset

### Data structure

1. Patient information

**PatientID:** Unique ID of each patient

**Age:** Age in years

**Gender:** Gender, with 0 representing Male and 1 representing Female

**Ethnicity:** Ethnic group, with 0 representing Caucasian, 1 representing African-American, 2 representing Asian and 3 representing Other

EducationLevel: Education level, with 0 representing None, 1 representing High School, 2 representing Bachelor's, 3 representing Higher

2. Lifestyle factors

**BMI:** Body Mass Index of each patient

**Smoking:** Smoking status, with 0 representing No and 1 representing Yes

**AlcoholConsumption:** Weekly alcohol consumption in units

**PhysicalActivity:** Weekly physical activity in hours

**DietQuality:** Diet quality score, evaluated on a scale of 10

**SleepQuality:** Sleep quality score, evaluated on a scale of 10

3. Medical history

**FamilyHistoryAlzheimers:** Family history of Alzheimer's Disease, with 0 representing No and 1 representing Yes

**CardiovascularDisease:** Presence of cardiovascular disease, with 0 representing No and 1 representing Yes

**Diabetes:** Presence of diabetes, with 0 representing No and 1 representing Yes

**Depression:** Presence of depression, with 0 representing No and 1 representing Yes

**HeadInjury:** History of head injury, with 0 representing No and 1 representing Yes

**Hypertension:** Presence of hypertension, with 0 representing No and 1 representing Yes

4. Clinical measurements

**SystolicBP:** Systolic blood pressure, measured in mmHg

**DiastolicBP:** Diastolic blood pressure, measured in mmHg

**CholesterolTotal:** Total cholesterol levels, measured in mg/dL

**CholesterolLDL:** Low-density lipoprotein cholesterol levels, measured in mg/dL

**CholesterolHDL:** High-density lipoprotein cholesterol levels, measured in mg/dL

**CholesterolTriglycerides:** Triglycerides levels, measured in mg/dL

5. Cognitive and functional assessment

**MMSE:** Mini-Mental State Examination score, evaluated on a scale of 30

**FunctionalAssessment:** Functional assessment score, evaluated on a scale of 10

**MemoryComplaints:** Presence of memory complaints, with 0 representing No and 1 representing Yes

**BehavioralProblems:** Presence of behavioral problems, with 0 representing No and 1 representing Yes

**ADL:** Activities of Daily Living score, evaluated on a scale of 10

6. Symptoms

**Confusion:** Presence of confusion, with 0 representing No and 1 representing Yes

**Disorientation:** Presence of disorientation, with 0 representing No and 1 representing Yes

**PersonalityChanges:** Presence of personality changes, with 0 representing No and 1 representing Yes

**DifficultyCompletingTasks:** Presence of difficulty completing tasks, with 0 representing No and 1 representing Yes

**Forgetfulness:** Presence of forgetfulness, with 0 representing No and 1 representing Yes

7. Others

**Diagnosis:** Diagnosis status for Alzheimer's Disease, with 0 representing No and 1 representing Yes

**DoctorInCharge:** The doctor in charge, with "XXXConfid" as the value for all patients. This is confidential information and will be excluded from analysis

## Conclusion

Alzheimer's Disease is greatly associated with decreased cognitive and functional abilities

From the data of this dataset, the most reliable way to diagnose Alzheimer's is through cognitive and functional assessment

While there are some interesting differences in other factors, there is little evidence to conclude they could be considered in the diagnosis

As the model only explains about 50% of the data, more research into other factors could make this model more accurate and reliable
