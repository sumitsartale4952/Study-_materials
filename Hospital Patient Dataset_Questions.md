## Below are 30 practice questions for the Hospital Patient Dataset (hospital\_patient\_500.csv).





Divided into Easy (10), Medium (10), and Hard (10).

### **EASY LEVEL (Data Cleaning + Basic Insights)**



1. Check if there are any missing values in the dataset.
   
2. Convert Admission\_Date and Discharge\_Date into datetime format.
   
3. Create a new column Length\_of\_Stay = Discharge\_Date - Admission\_Date (in days).
   
4. Find average bill amount.
   
5. Count number of patients per diagnosis.
   
6. Find how many patients are covered by insurance.
   
7. What is the maximum and minimum bill amount?
   
8. Find number of patients treated by each doctor.
   
9. List patients whose bill amount is greater than 40,000.
   
10. Find average age of patients.



### **MEDIUM LEVEL (Healthcare KPI + Conditional Analysis)**



1. Calculate average length of stay per diagnosis.
   
2. Find which doctor generates highest total bill amount.
   
3. Calculate insurance claim ratio:
   (Number of insured patients / total patients) × 100
   
4. Identify top 5 highest billing patients.
   
5. Find monthly admission trends (extract month from Admission\_Date).
   
6. Compare average bill amount between insured and non-insured patients.
   
7. Find diagnosis with highest average bill per day (Bill\_Amount / Length\_of\_Stay).
   
8. Identify patients admitted for more than 7 days.
   
9. Create age group categories:

   Child (0–18)

   Adult (19–60)

   Senior (60+)
   Then count diagnosis distribution per age group.
   
10. Find doctors who treated more than 50 patients.



### **HARD LEVEL (Advanced Cleaning + Business Intelligence)**



1. Detect outliers in Bill\_Amount using IQR method.
   
2. Identify cases where Length\_of\_Stay is unusually long (> 95th percentile).
   
3. Calculate readmission risk proxy:
   Patients with same Diagnosis and same Doctor occurring more than once.
   
4. Create hospital revenue growth month-over-month.
   
5. Find which diagnosis contributes highest percentage to total revenue.
   
6. Build a patient risk score:
   Risk\_Score = (Age factor) + (Length\_of\_Stay factor) + (Bill factor)
   Then rank top 10 high-risk patients.
   
7. Compare average length of stay between male and female patients for each diagnosis.
   
8. Detect possible data errors:

   Discharge\_Date earlier than Admission\_Date

   Negative length of stay

   Extremely low bill amount (< 1000)
   
9. Calculate revenue efficiency per doctor:
   Total Revenue / Total Patients handled.
   
10. Create a hospital performance summary table including:

    Total Patients

    Total Revenue

    Average Bill

    Average Length of Stay
    

&nbsp;  Insurance Coverage %

