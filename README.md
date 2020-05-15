# Chulalongkorn University's AI Academy 2020
## 2nd round screening exam

---

# IMPORTANT NOTICE
Due to technical issue, the column descriptions were not included with the data files. So we are providing them here:

## Problem 1:
* **ELISpot_Control** is the ELISpot test result for the POSITIVE CONTROL (i.e., we expect to see strong response)
* **ELISpot_Result** is the ELISpot test result for SUSPECTED DRUG (i.e., this is the result that indicate whether the patient would be allergic to that drug)
* **NARANJO_Category** is ORDINAL.
* **Exposure_Time** is the amount of times since the patient has taken the drug until the ELISpot test date
* **Suspicion_Score** is the suspicion level of the drug (1 = suspected drug, 2 = similar to suspected drug, 3 = negative control). This is ORDINAL.
* **Allergic_Reaction_Group** is the severity of patient's allergic reaction. This is ORDINAL.
* **Drug_Group** is CATEGORICAL.
* **Drug_Rechallenge_Result** is the ground truth of this dataset that we want to predict.

## Problem 2:
* **Time to Event** is the amount of time from the date of data collection until a patient's day of death or until his/her last check-up
* **Patient Status** is the patient's latest status (0 = alive, 1 = dead)
* **Patient Status at 3-Year** is the patient's status at 3-year mark (0 = alive, 1 = dead, -1 = unknown)
* **v_n**'s are radiomics features extracted from ROI drawn by radiologists

### To clarify, **Time to Event** is the information used to generate **Patient Status at 3-Year** and should NOT be considered as part of the input to your prediction model.

---
This exam intends to mimic a real project situation where you have to clean the data yourself and validate your model’s performance without relying on specified test sets as in normal Kaggle competitions.

Your work will be evaluated on multiple criteria. The final model performance is NOT the most important consideration, but we rather want to see how you approach the tasks and justify design choices made along the way.

You are not expected to understand the meaning of all features. In fact, the names of many features have been anonymized to prevent examinees with domain knowledge from getting advantage over others.

This exam consists of 3 problems, each testing you on different aspects of data analysis and machine learning model development. Given the short amount of time, we DO NOT expect you to complete or even attempt all 3 problems. 

### Plan your time wisely and show us what you can do!

---
## **Problem 1: Drug Allergy Prediction**

Find the dataset and description [here](https://www.kaggle.com/dataset/164839c70ca43c870151479e85f496daa3b68be24a93c44fa1cd153c66049bf5)

## **Problem 2: Cancer Survival Prediction**

Find the dataset and description at [here](https://www.kaggle.com/dataset/b830860b3bd50fbe6d2f9448dcb1fd18da025a4ae41208cf4bd557292cac6eab)

## **Problem 3: The Tale of Two Wat**

For this problem, you are tasked to develop a machine learning model that takes a photo as input and classify whether that photo contains Wat Prakaew or Wat Po. Gather your dataset from photos on the internet. [Here](https://drive.google.com/open?id=1mdZLeiG0NSR6idRFCs9k_1GAsJ59riDK) are some example photos that you should try to handle.

---

### If you have a question, post a new issue here rather than emailing our staff. That way everyone will be able to get the same information. 
### Please read the Q&A policy before posting.
### Hand in your answers by May 21st, 2020 at 9pm Bangkok time via email to utc [at] chula.ac.th
