
# Shedding Light on Cancer Clinical Trials: Eligibility Criteria 

### Summary

Eligibility criteria are the specifications that determine who is eligible to participate in a clinical trial. Outlined in the study protocol, criteria may be inclusive or exclusive based on characteristics such as type and stage of disease, previous treatment history, age, and other medical or non-medical attributes. Restrictive criteria have not only been a significant hurdle for many patients who have wanted to participate in trials, but they have also limited the generalizability of study findings. Recently, there have been initiatives to re-examine and modernize eligibility criteria for oncology clinical trials. To assess current eligibility requirements for cancer clinical trials, I plan to analyze eligibility criteria for commercial investigational new drug clinical trial applications submitted to the FDA Office.


### Motivation

Common exclusion criteria have developed over time and grown in complexity with clinical trials. An analysis of Investigational New Drug applications for 2015 found that, of 250 study protocols only five (1.7%) allowed enrollment of HIV-positive patients with stable disease and/or adequate CD4+ T-cell counts and less than half (140 or 47.1%) allowed participation of patients with treated or stable brain metastases. It also found only 11 protocols (3.7%) included pediatric patients younger than 16 years of age. 
Restrictive eligibility criteria can create barriers for patients to access clinical trials and may contribute to prolonging the accrual process or early closure of studies struggling with patient accrual. An analysis of cancer studies found that ineligibility was the cause of 18% of patients with cancer not participating in a clinical trial. American Society of Clinical Oncology (ASCO) and Friends of Cancer Research launched a joint project in 2016 to promote more inclusive eligibility criteria in cancer clinical trials.


### Data Question

Analysis of eligibility criteria protocols from cancer clinical trials that were available in ClinicalTrials.gov to guide unbiased future patient selection.

The documents available at Clinical trials site have information called condition where it is written for what conditions the clinical trials were designed and a text description about patient eligibility/ineligibility criteria. I plan to perform ML analysis on condition and criteria to predict what company should list for eligibility/ineligibility requirements while designing a future clinical trial for a certain cancer type/condition.


### Data Sources

http://clinicaltrials.gov/


### Step 1 : Download individual clinical trial xml files from Data Source
On ClinicalTrials.gov site the following search keyword was used to select dataset:

Condition or disease: 'Cancer' 

Study type: 'Interventional Studies' 

or follow the link: https://clinicaltrials.gov/ct2/results?cond=Cancer&age_v=&gndr=&type=Intr&rslt=&Search=Apply

### Setp 2: Data processing 
    
Follow the guide on ' clinicalTrial-xml_to_DataFrame' notebook to convert to pandas data frame withch was later saven as csv files for future usage


### Setp 3: Exploratory analysis and Model building

To visualize Exploratory analysis follow: 'clinicalTrial_EDA' notebook

And for model building: 'Clinical_Trial_Model'


```python

```
