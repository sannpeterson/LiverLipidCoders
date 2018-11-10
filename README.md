# LiverLipidCoders
The focus of this project is to develop a machine learning algorithm using the plasma lipid data provided to provide staging for a patient’s liver disease diagnosis. 

## Introduction
There are four main stages of liver disease:
  1. Normal: Healthy condition.
  2. Steatosis: Liver is fatty. Reversible. Can be diagnosed via a blood test.
  3. Steatohepatisis: Liver is fatty and inflamed. Reversible. Can only be diagnosed via a biopsy.
  4. Cirrhosis: Liver is dying. Non-reversible.
  
Through machine-learning-based staging of disease and identification of relevant biomarkers in plasma, patients can avoid the process of an intrusive biopsy (for stage 3) and still receive an accurate diagnosis of the disease. Our team conducted statistical analyses on a small sample of patient data to determine whether further investigation of similar techniques is beneficial.


![Stages of Liver Disease](./pix/Slide1.PNG "Stages of Liver Disease")

![The Cohort](./pix/Slide2.PNG "The Cohort")

## Exploratory Analysis
We created a correlation matrix for all 1846 lipids. Only about 400 of these are known and labeled, but all of them can potentially contribute to the staging of the disease.
![The Correlation Matrix of 1846 Lipids](./pix/cormat_all.png "The Correlation Matix of 1846 Lipids")
