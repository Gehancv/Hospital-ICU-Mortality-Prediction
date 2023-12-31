# Hospital-ICU-Mortality-Prediction

## Introduction
In a clinical care setting, the Intensive Care Unit (ICU) is known for having one of the highest in-hospital mortality rates due to the critical nature of its patients. Monitoring the health status of patients in the ICU is crucial for their survival, and accurately assessing their level of health can significantly impact the level of care they receive.
Our final project aims to predict the mortality of patients admitted to the ICU using data from the first 24 hours after admission. The concept of predicting patient severity in the ICU is not new. The Acute Physiology and Chronic Health Evaluation (APACHE) scoring system was first introduced in 1981 by George Washington University and has since become a widely used scale for assessing acute illness. Over the years, several versions of APACHE have been developed, with the latest being APACHE IV, released in 2006. APACHE utilizes physiologic measurements, demographics, and previous health conditions from the first 24 hours to assess the severity of acute illness. While APACHE is an invaluable tool for quick severity assessment using simple body metrics, it does not provide predictions on patient mortality; instead, it aids clinical practitioners in assessing patients.
As data analytics students, our challenge is to predict patient mortality based on 24-hour vital metrics, similar to APACHE, in an attempt to explore the predictive potential of the data. By doing so, we hope to provide a broader perspective for assessing patients in clinical settings and discover the possibilities of leveraging data for mortality prediction.
The dataset encompasses over 130,000 ICU visits worldwide, offering valuable insights such as patient demographics, comorbidity status, laboratory results, and medical measurements taken within the first 24 hours of ICU admission. With a total of 186 columns, it comprises 16 binary, 12 character, and 158 numeric columns. In terms of rows, it contains 91,713 records, and the prediction target variable is the binary outcome of hospital death. The variables included some patient demographic information such as patient id, race, gender, hospital admission types, Body mass index, pre-clinical histories, etc. Vital variables such as diastolic and systolic blood pressure, body temperature, hear rate, white blood cell count, respiratory measure, oxygen, and arterial pH levels are calculated. 




