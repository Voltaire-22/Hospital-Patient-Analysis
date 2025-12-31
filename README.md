# Hospital-Patient-Analysis

# **MASSACHUSETTS GENERAL HOSPITAL PATIENT RECORD (2011 – 2022)**

## **INTRODUCTION**
This data analysis project, examines the overall encounter volume to better understand encounter behavior and patterns. In this data includes payer coverage information and patient information to recognize financial stability / pattern over time.

<p align="center">
<img src= "https://github.com/Voltaire-22/Hospital-Patient-Analysis/blob/main/Dashboard.png?raw=true" width="700">
</p>

## **ENCOUNTERS OVERVIEW**

<p align="center">
<img src= "https://github.com/Voltaire-22/Hospital-Patient-Analysis/blob/02840dfc259d12a47298ce3149f85a7ebd47c097/Encounter%20by%20Year.png" width="700">
</p>

<p align="center")>
Total Encounter by Year (2011-2022)
</p>

Data shows that out of 27,891 encounters there’s 3,885 (13.93%) encountered patients occurred on year 2014 and 2021 with 3,530 (12.66%) encountered patients. Surprisingly it didn’t peak around year 2019 onwards considering that the Pandemic (COVID-19) happened around that time. 

*Note: Encountered patient shows the total of patient’s check-ups not the total number of individual patients.*

<p align="center">
<img src= "https://github.com/Voltaire-22/Hospital-Patient-Analysis/blob/main/Encounter%20By%20Class.png?raw=true" width="700">
</p>

<p align="center")>
*Total Encounter Class (2011-2022)*
</p>

Hospitals designate different classes to their process, designed to maximize efficiency of the overall process. In this data shows Ambulatory contributes the most with 44% encounter over the span of 11 years. Ambulatory is the type of encounter class where patients doesn’t need to be admitted and only requires minimal treatment/procedure.

## **COST & COVERAGE INSIGHTS**

<p align="center">
<img src= "https://github.com/Voltaire-22/Hospital-Patient-Analysis/blob/main/Encounter%20By%20Class.png?raw=true" width="700">
</p>

<p align="center")>
*Total Patient Assisted by Payer*
</p>

Payers refers to a government body that assist people in medical finances by programs like Medical Insurance and Hospital Insurance. In this data, there are cases that the government pays/covers a portion of the medical cost. Out of 27,891 encounters, 13,586 encounters are not covered by the payers’ program,

Upon further analysis, some of the following procedure/cases are not covered by the program:

-	Encounter for problem (procedure)
-	Patient encounter procedure
-	General examination of patient (procedure)
-	Encounter for check-up (procedure)
-	Encounter for symptom 

These are the low cost and cases that are not critical to the health of a patient. However, not all of the low-cost symptoms/cases are not covered by government, they still cover some of the cases. This could be an opportunity for government bodies to increase coverage of their program.

<p align="center")>
*Top 10 Procedure and It’s Average Base Cost*
</p>

In this figure shows the top 10 highest procedure done in the hospital in the span of 11 years ---- while Electrical cardioversion is the highest average in terms of base cost of $25,903.11, it is not the most performed procedure at the hospital. Both of the base cost for Assessment and Hospice Care averages around $400.

**Assessment of Health and Social Care Needs (28.05%):** Over 4,596 encounters are in need for basic check-ups, this includes social care, health care, mental assessment and etc.

**Hospice Care (Regime/Therapy) (25.01%):** Massachusetts General Hospital (MGH) have encountered 4,098 patients that has undergone therapy.

## **PATIENT BEHAVIOR ANALYSIS**

<p align="center")>
*Unique Patient Admitted*
</p>

Over the past 11 years, the highest admitted patient is on the 1st quarter of 2014 with 254 patients and averages at 150 patients per quarter for the following years. Basing on the above data, Massachusetts General Hospital (MGH) encounters 150 patients per quarter on average.

# **DATA MODEL**
<p align="center">
<img src= "https://github.com/Voltaire-22/Hospital-Patient-Analysis/blob/main/Data%20Model.png?raw=true" width="500">
</p>

# **CONCLUSION**

The analysis revealed that encounter volumes remained relatively stable over time, with notable peaks in 2014 and 2021, rather than during the height of the COVID-19 pandemic as initially expected. 

On a financial perspective, a significant portion of encounters were not covered by payer programs, particularly low-cost and non-critical procedures such as routine check-ups and general examinations. While these cases may not pose immediate financial risk, they present an opportunity for government and payer programs to expand coverage and improve preventive care access.

Patient behavior analysis indicated a relatively consistent admission pattern over time, averaging around 150 unique patients per quarter, suggesting steady demand for hospital services. Overall, this analysis highlights key trends in utilization, cost distribution, and coverage gaps that can support better operational planning, policy decisions, and future data-driven improvements in healthcare delivery.

# **DATA COLLECTION**

Through various sources, there’s a lot of datasets similar to this data, however I opted to choose the data from Maven Analytics website as the data from their website is completely raw/uncleaned while the datasets in Kaggle are already cleaned. This gave me an opportunity to be hands on to the whole process start to finish and become more familiar with the data.

**TOOLS:** Excel | Power BI

