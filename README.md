# HEALTHCARE AND LIFESTYLE DATASET (CLINICAL & BEHAVIOURAL METRICS) - PUBLIC HEALTH ANALYTICS REPORT.

## Overview:
This project studies 1,000 individuals to see how everyday habits like sleep, exercise, smoking, alcohol, calories intake, relate to health outcomes like heart rate, blood pressure, Body Mass Index (BMI), diabetes and heart disease. In summary, we looked for patterns showing which lifestyle choices are linked to higher health risk.


## Sector, Industry & Period:
>> Sector: Public Health / Healthcare Analytics

>> Industry: Preventive Medicine & Health Informatics

>> Analysis Period: July 2026

## Problem Statement:
Health authorities need to know which combinations of habits (e.g., smoking, low exercise, high BMI) put people at the greatest risk, so limited resources (staff, funding, campaigns) can be directed to the people who need help most, instead of being spread thinly across everyone.

## Tools Used:
> Tool | Purpose 
>> Python | The programming language used to run the analysis

>> Jupyter Notebook (100%) | The workspace where the code and results are shown together

>> Pandas | Organizes and manages the data, like a smart spreadsheet

>> NumPy | Handles number-crunching and calculations

>> Matplotlib & Seaborn | Creates the charts and graphs (visualization)

## Dataset:

### Size: 1,000 people, 16 variables, no missing data.

### Variables: Age, Gender, Height_cm, Weight_kg, BMI, Daily_steps, Calories_intake, Hours_of_sleep, Heart_rate, Blood_pressure, Exercise_Hours_per_week, Smoker, Alcohol_Consumption_per_week, Diabetic, Heart_Disease.

## Process:
>> I loaded the data and checked it was complete and correctly formatted.

>> Produced summary statistics (averages, ranges) to understand a "typical" person

>> Compared sleep against heart rate to check for a relationship.

>> Compared alcohol habits between diabetics and non-diabetics.

>> Filtered the data to flag "high-risk" people: smokers, low exercise (<2 hrs/week), high BMI (>30).

>> Compared the high-risk group against everyone else.

>> Built an overall correlation heatmap to see how all the health factors relate to one another.

## Key Questions & KPIs:
> Question | KPI Tracked
>> Does poor sleep raise heart rate? | Correlation: Sleep vs Heart Rate

>> Do diabetics drink less alcohol? | Median alcohol units/week by diabetic status

>> Who is most at risk? | Count & profile of high-risk group (19 of 1,000)

>> What habits travel together? | Correlation matrix across all metrics

## Visualizations:
>> Scatter plot with trend line: Sleep vs Heart Rate
>> Box plot: Alcohol consumption, Diabetic vs Non-Diabetic
>> Four-panel box plots (Subplots): Age, Heart Rate, Blood Pressure, BMI by Risk Group.
>> Correlation heatmaps: full population and high-risk subgroup

## Result Summary / Conclusion:

>> 19 out of 1,000 people (about 2%) fall into the "high-risk" category (smoker + low exercise + high BMI).

>> This high-risk group has a noticeably higher average BMI (~33 vs ~27) and higher heart rate than the rest.

>> Within the high-risk group, exercise is strongly linked to age. Younger high-risk people tend to exercise a bit more.

>> Sleep showed only a weak link to heart rate in this dataset, not a strong standalone predictor.

>> No single lifestyle factor explains health risk alone; risk comes from a combination of habits.

## Recommendations / Utilities:

>> Target the ~2% high-risk group first for check-ups and coaching, the biggest impact for least resources.

>> Combine smoking-cessation and weight-management programs rather than running them separately, since these risks overlap.

>> Use this same notebook as a template for new batches of health data, since the process is fully automated.

>> Present the heatmap to non-technical stakeholders as a quick "at a glance" risk map.


## Suggestions for Future Works:
I just started a bigger transition into applying data science and machine learning in our daily lives and specifically as a chemical engineer, and I saw that this project can further be improved by: 

>> Trying a simple prediction model (e.g. logistic regression) to estimate someone's diabetes/heart-disease risk from their habits.

>> Turn the notebook into an interactive dashboard (e.g. using Streamlit) so non-coders can explore the data themselves.

>> Spliting "Blood_pressure" into two separate numeric columns (Systolic and Diastolic) from the very start, not just for the high-risk group.

>> Adding units clearly next to every column name (e.g. Weight_kg, Sleep_hrs) to avoid confusion.





Thank you for your time.

(Q.E.D)
