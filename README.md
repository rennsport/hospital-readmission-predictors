# How to Use This Project

1. Install requirements via pip and requirements.txt
2. Place `anxiety_disorder_admission_data.csv` into the Data folder
3. Run the notebooks in the following order: EDA -> Data Cleaning/Feature Engineering -> Modeling

My write-up can either be read in the markdown file or the pdf

Thanks!

# Data Science Take-Home Assignment: Predicting Hospital Readmissions

### Introduction & Business Context
When patients leave the hospital, some are readmitted within 30 days. You need you to analyze a dataset of patient hospital stays to figure out the main reasons why this happens. We need more than just a predictive model. We want you to provide insights that can help us identify high-risk patients early so we can offer them more support.
### The Dataset

You'll use a dataset called "anxiety_disorder_admission_data." It contains 10 years of data from over 100,000 hospital stays for patients with anxiety. See the data fields details at the end of this document.
### The Core Task 
Please walk us through your process. Your analysis should answer these key questions.

- First Look at the Data (EDA):
  - What were the biggest data quality problems you found (like missing information), and how did you decide to fix them?
  - Before building any models, what were the 2 or 3 most interesting things you learned just by exploring the data?
- Creating New Features:
  - The data has many columns. Tell us about two new, useful features you created from the existing data. Why did you think they would be helpful for predicting readmission?
- Building a Model:
  - What kind of model did you choose and why was it a good fit for this problem?
  - How did you measure your model's performance, and how well did it do?
- Finding the "Why":
  - Based on your model, what are the top 5 factors that predict a patient will be readmitted?
  - Can you describe a "high-risk patient profile"? What do these patients typically look like in the data?

- Your Recommendation:
  - Patient Priority: A doctor's time is limited. If they could only make three extra follow-up call today to prevent a readmission, what kind of patients should they call? Use your analysis and risk score to describe the most important patients profile to target
  - Imagine we have a limited budget for a new support program. Based on your analysis, what one or two areas should we focus on to help prevent readmissions? (For example, should we focus on patients with a certain number of past visits, or those taking specific drugs?) Please explain your reasoning.

### Bonus (Optional Challenge)
If you have extra time and want to show more, you can briefly describe:

- How would you build a data pipeline if you were given raw data tables (diagnoses, labs, meds) instead of one flat file?

- How you might use a time-series model (like an RNN) if you had the full history of each patient's visits over time.

### Submission

- Notebook (.ipynb) or script (.py)
- A short write-up (PDF or Markdown) including:
  - EDA insights
  - Modeling summary and interpretation
  - Limitations and suggestions
- (Optional) any visualizations
