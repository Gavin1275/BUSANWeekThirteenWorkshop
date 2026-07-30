# Week 13 Workshop

## Scenario

The success of an organisation often depends on the quality of its employees and employee retention. Employee attrition refers to the gradual reduction of an organisation's workforce due to retirement, resignation, or layoffs occurring at a rate faster than new hires or replacements. Unwanted attrition is problematic because of the loss of experienced personnel, adverse effects on productivity, and substantial time and expenditure required to recruit and train new hires.

You have been tasked with exploring factors that influence employee attrition and developing a classification model to predict employee attrition. Management intends to use the model to identify potential cases of unwanted attrition early, enabling timely implementation of intervention strategies to retain valuable employees. Management expressed the need for high certainty that the potential cases identified are at risk of attrition, as they do not want to subject falsely identified employees to unwanted attention or unwarranted interventions nor direct resources to areas that may not be necessary.

## Data

The data used in this exercise is based on synthetic data created by IBM that mimics data on employee attrition and performance. It comprises various demographic information and job-related metrics for employees.

Download the `week13_employee.csv` file from the `data/` folder.

## Documents

Additional notes and data definitions are included in the `document/` folder:

- document/Notes.md
- document/Data_Dictionary.md

## Student Process and Submissions

1. Log into GitHub and `Fork` the repository (i.e., save a copy of the course repository to your own GitHub account). Select `Fork > Create fork`. You will be downloading and uploading all files from this forked repository.
2. Download the CSV file and review available documentation.
3. Use R and RStudio to conduct analysis on factors that influence employee attrition.

    1. In RStudio, select `File > New File > R Markdown...` and `Create Empty Document` in the bottom-left corner. Can click on the cog icon beside `Knit` and select `Chunk Output in Console` to return output in the console window.
    2. Save the RMD file and give it a unique name (e.g., your name or student)
    3. Access the `studentRMD/` folder forked to your GitHub account and select `Add file > Upload files > Drag or choose the file > Commit changes`.
    4. Request to push the changes through to the course repository by selecting `Contribute > Open Pull Request > Submit`.
   
4. Continue your analysis and create the best classification model you can to predict employee attrition.
