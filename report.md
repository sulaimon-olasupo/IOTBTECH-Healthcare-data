# Healthcare Data Analytics Report  
**IOTB TECH Hospital**  


## Introduction  

This report presents an analytical review of the healthcare dataset provided by IOTB TECH Hospital. The analysis was conducted using **Microsoft Excel** tools such as **Pivot Tables**, **Pivot Charts**, and data summarization techniques to uncover meaningful insights related to:

- Patient admissions  
- Hospital revenue  
- Medical conditions  
- Medication usage  
- Insurance contributions  

The objective of this analysis is to help hospital management make informed **operational** and **financial** decisions by identifying patterns, trends, and areas requiring improvement.

> ![alt text](<Charts and tables/Full_dataset.png>)  
> *Figure 1: Full healthcare dataset used for analysis.*


## Data Preparation & Cleaning  

Before analysis, the dataset was inspected and cleaned to ensure data accuracy and consistency.

### Data Cleaning Performed  

The following checks were conducted:

- Blank rows inspection  
- Duplicate records identification  
- Missing value verification  
- Incorrect data entry validation  
- Data type verification  

### Findings from Data Cleaning  

- No blank rows were found.  
- No missing values were detected.  
- Data entries were consistent across categorical fields.  
- **Billing Amount**, **Admission Date**, and **Discharge Date** were properly formatted.  
- A total of **534 duplicate records** were identified and removed.  

### Additional Column Created  

A new column named **Length of Stay** was created using:

```excel
=Discharge Date - Admission Date
```

This was used to analyze average hospital stay duration across medical conditions.

>   ![alt text](<Charts and tables/Cleaned_data.png>)
> *Figure 2: Cleaned dataset with the new Length of Stay column.*



## Key Findings  

### 1. Diabetes Generated the Highest Revenue  

The analysis revealed that **Diabetes** contributed the highest total billing amount among all medical conditions.

>  ![alt text](<Charts and tables/Revenue by condition.png>)
> *Figure 3: Pivot table showing total billing amount by medical condition.*

> ![alt text](<Charts and tables/Revenue by condition chart.png>)
> *Figure 4: Pivot chart visualizing revenue by medical condition.*


### 2. Aged Patients Had the Highest Admissions  

The aged group recorded the largest number of hospital admissions.

> ![alt text](<Charts and tables/Age group table.png>)  
> *Figure 5: Pivot table showing admissions by age group.*

> ![alt text](<Charts and tables/Age group chart.png>)  
> *Figure 6: Pivot chart visualizing admissions by age group.*


### 3. Cigna Was the Highest-Contributing Insurance Provider  

Among all insurance providers, **Cigna** generated the highest billing contribution.

> ![alt text](<Charts and tables/Insurance table.png>)  
> *Figure 7: Pivot table showing total billing by insurance provider.*

> ![alt text](<Charts and tables/Insurance chart.png>) 
> *Figure 8: Pivot chart visualizing revenue by insurance provider.*


### 4. Elective Admissions Were the Most Common  

**Elective admissions** accounted for the largest share of total hospital admissions.

> ![alt text](<Charts and tables/Admission type table.png>)  
> *Figure 9: Pivot table showing admissions by admission type.*

> ![alt text](<Charts and tables/Admission type chart.png>)  
> *Figure 10: Pivot chart visualizing admissions by admission type.*


### 5. Asthma Recorded the Longest Average Hospital Stay  

Patients diagnosed with **Asthma** had the highest average length of stay in the hospital.

> ![alt text](<Charts and tables/Length of stay table.png>)  
> *Figure 11: Pivot table showing average length of stay by medical condition.*

> ![alt text](<Charts and tables/Lenght of stay chart.png>)
> *Figure 12: Pivot chart visualizing average length of stay by condition.*


### 6. Arthritis Was the Most Common Medical Condition  

**Arthritis** appeared most frequently among patient diagnoses.

> ![alt text](<Charts and tables/Admission by condition table.png>)  
> *Figure 13: Pivot table showing frequency of medical conditions.*

> ![alt text](<Charts and tables/Admission by condition chart.png>)
> *Figure 14: Pivot chart visualizing frequency of medical conditions.*


### 7. Lipitor Was the Most Frequently Prescribed Medication  

**Lipitor** emerged as the medication with the highest prescription frequency.

> ![alt text](<Charts and tables/Medication use table.png>)  
> *Figure 15: Pivot table showing prescription frequency by medication.*

> ![alt text](<Charts and tables/Medication use chart.png>)  
> *Figure 16: Pivot chart visualizing medication prescription frequency.*



### 8. August Recorded the Highest Number of Admissions  

Patient admissions peaked during the month of **August**.

> ![alt text](<Charts and tables/Admission by month table.png>)  
> *Figure 17: Pivot table showing admissions by month.*

> ![alt text](<Charts and tables/Admission by month chart.png>)  
> *Figure 18: Pivot chart visualizing admissions by month.*


## Observations  

### Chronic Diseases Dominate Hospital Operations  

Conditions such as:

- Diabetes  
- Arthritis  
- Hypertension  
- Asthma  

contributed significantly to patient admissions and billing revenue.  
This indicates a growing burden of **chronic diseases** among patients.

### Elderly Patients Require More Healthcare Services  

The high admission rate among older adults suggests increasing healthcare demand from aging populations.  
This places additional pressure on:

- Bed occupancy  
- Long-term care  
- Medication usage  
- Specialist consultations  

### Emergency Cases Continue to Strain Resources  

Although elective admissions were more common, **emergency admissions** remained significantly high and resource-intensive.  
Emergency cases often require:

- Immediate attention  
- More healthcare personnel  
- Intensive monitoring  

### Medication Demand Reflects Cardiovascular Trends  

The frequent prescription of **Lipitor** suggests high rates of cholesterol-related and cardiovascular conditions.  
This indicates the need for continuous **cardiovascular disease management**.


## Insights  

### Revenue Is Strongly Linked to Chronic Disease Management  

The hospital’s revenue structure depends heavily on long-term disease treatment and management.  
Patients with chronic illnesses typically require:

- Multiple hospital visits  
- Continuous medication  
- Repeated laboratory testing  

This makes **chronic care** a major financial driver for the hospital.

### Insurance Partnerships Are Critical to Financial Stability  

The high financial contribution from **Cigna** highlights the importance of strong insurance-provider relationships.  
Insurance-supported treatments play a major role in sustaining hospital revenue.

### Seasonal Admission Patterns Affect Hospital Workload  

The spike in admissions during **August** suggests possible seasonal health trends or environmental influences affecting patient volume.  
Such patterns can affect:

- Staffing needs  
- Medical inventory  
- Bed availability  

### Long Hospital Stay Increases Operational Costs  

Conditions associated with extended hospital stays increase:

- Resource consumption  
- Bed occupancy duration  
- Staffing requirements  

Reducing unnecessary stay duration can improve hospital efficiency.


## Recommendations  

1. **Expand Chronic Disease Management Programs**  
   The hospital should invest more in:  
   - Diabetes care  
   - Hypertension monitoring  
   - Asthma management  
   - Arthritis treatment programs  

   This will improve patient outcomes and reduce severe complications.

2. **Strengthen Preventive Healthcare Campaigns**  
   Public health awareness initiatives should focus on:  
   - Healthy lifestyle education  
   - Early disease screening  
   - Routine medical checkups  

   Preventive healthcare can reduce emergency admissions and long-term treatment costs.

3. **Improve Elderly Care Services**  
   Given the high admission rate among elderly patients, management should:  
   - Expand geriatric care units  
   - Improve rehabilitation services  
   - Increase specialist support for aging-related conditions  

4. **Enhance Insurance Collaboration**  
   The hospital should maintain strong partnerships with high-performing insurance providers such as **Cigna** by:  
   - Improving claims processing  
   - Negotiating favorable reimbursement agreements  
   - Enhancing patient insurance support services  

5. **Improve Emergency Preparedness**  
   The hospital should strengthen emergency care systems through:  
   - Better staffing allocation  
   - Faster triage processes  
   - Improved emergency equipment availability  

6. **Improve Resource Planning During Peak Months**  
   Since admissions peak during **August**, management should:  
   - Increase staffing during high-demand periods  
   - Maintain adequate medication stock  
   - Improve forecasting and scheduling systems  



## Conclusion  

The healthcare data analysis revealed that **chronic diseases**, **elderly patient care**, and **insurance-supported treatments** are major drivers of hospital operations and revenue generation at **IOTB TECH Hospital**.  

The findings highlight the importance of:

- Preventive healthcare  
- Efficient resource allocation  
- Strong insurance partnerships  
- Chronic disease management strategies  

Using data analytics through **Pivot Tables** and **Pivot Charts** provided meaningful business intelligence that can support better healthcare planning, operational efficiency, and improved patient care delivery.

>![alt text](<Charts and tables/Table1.png>)
![alt text](<Charts and tables/Table2.png>)
![alt text](<Charts and tables/Chart1.png>) 
![alt text](<Charts and tables/Chart2.png>) 
> *Figure 19: Summary dashboard combining key metrics from the analysis.*