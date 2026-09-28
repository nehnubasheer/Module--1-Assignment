# Module--1-Assignment
Data Cleaning	
Check for the number of missing values marked with '?' in each column of the “Medical Examinations” Table and "Hospitalization Details" Table.	Medical examination table:2 values and Hospitalization Details:15 values (Highlighted in Yellow colour)
Fill in the missing values of ‘month’ with Sep and ‘year’ with its average rounded to the nearest integer.	Month updated in Col:C  of Hospitalisation sheet and Year is 1982 (Highlighted in Yellow colour)
Determine the most frequently occurring values in the ‘smoker’, 'Hospital tier' and 'City tier' columns, and fill in the missing values accordingly.	Smoker:NO, Hospital tier :tier - 2, City tier:tier - 2 (Highlighted in Yellow colour)
If any 'State ID' values are missing, consider filling them with 'Unknown' or using another appropriate strategy.	Missing values renamed as :Unknown
Data Transformation	
Split the ‘names’ column in the “Customer Names” Table into 3 meaningful columns: ‘Title’, ‘First Name’, and ‘Last Name’	Col:C, D and E in Customer Names sheet
Convert the "NumberOfMajorSurgeries" column in the “Medical Examinations” Table to numerical data by replacing non-numeric characters with meaningful numerical values.	No major surgery are replaced by numerical value as "0"
Check for inconsistencies in the 'Heart Issues' and 'smoker' columns and propose corrective actions if necessary.	yes are replaced by "Yes"
Create a new column named “Weight Status” that categorizes BMI into different categories	Added new col:C in Medical Examinations sheet (Highlighted with green) 
Create a new column named “Diabetes Status” and fill it as per the information given below:	Added new col: E in Medical Examinations sheet (Highlighted with blue) 
Merge ‘year’, ‘month’ and ‘date’ columns in the “Hospitalization Details” Table into one column named ‘Date of Birth’ and format it in ‘DD-MMM-YYYY’ custom format.	Added new col: E in Hospitalization Details sheet (Highlighted with Orange) 
Calculate the ‘Age’ of each customer based on their ‘Date of Birth’ and the date of collection of the dataset, which is 8th June 2023.	Added new col: F in Hospitalization Details sheet (Highlighted with Red) 
Format ‘charges’ column as currency ($).	col: H in Hospitalization Details sheet (Highlighted with Green)
Data Exploration, Analysis & Visualization:	
Create a new sheet named “Healthcare", combine all three tables into one, using Customer ID as the common column, utilizing VLOOKUP.	Added in the sheet "Healthcare"
Retain the following necessary columns: Customer ID, First Name, BMI, HBA1C, Heart Issues, Any Transplants, Cancer history, NumberOfMajorSurgeries, smoker, Weight Status, Diabetes Status, Date of Birth, charges, Hospital tier, City tier, State ID, Age.	Added in the sheet "Healthcare"
Analysis using Pie/Donut Chart:	Added in the sheet "Pivot Charts"
Analysis using Column/Bar Chart:	Added in the sheet "Pivot Charts"
Analysis using Line/Scatter Plot:	Added in the sheet "Dashboard"
Dashboard Creation:	Added in the sheet "Dashboard"
<img width="1256" height="1345" alt="image" src="https://github.com/user-attachments/assets/cfc8e1d8-7bb1-45fc-ad14-5a6ff9dc5437" />

