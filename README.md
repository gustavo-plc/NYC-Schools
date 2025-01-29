# Analyzing NYC Public School SAT Scores: Insights for Policy Makers, Researchers, and Parents

## **Overview**

Every year, school test results impact the college admissions fate of millions of students. In this project, standardized test performance data from NY C's public schools will be used to identify the schools with top math results, analyze how performance varies by borough, and find the city's top ten performing schools!

![image.png](https://github.com/user-attachments/assets/a2f07165-ba40-49d7-a365-8a5610c13693)


Skills involved: data cleaning, data analysis, data visualization, and insights generation.

## **Problem Statement**

### This project aims to properly answer these questions:

**a**) Which NYC schools have the best math results?

**b**) What are the top 10 performing schools based on combined SAT scores?

**c**) Which borough has the largest standard deviation in SAT scores, and what insights can we derive from it?

## **Dataset**

File name: schools.csv

Description: Includes SAT performance data of NYC public schools (as image below).


<div style="text-align: center;">
  <figure>
    <img src="https://github.com/user-attachments/assets/14c2dfab-5369-4b2e-bf77-2c4363a2270c" alt="Original Dataset">
    <figcaption style="font-size: 0.6em;"> </figcaption>
  </figure>
</div>



Source: Publicly available.

Size and structure: Share the number of rows, columns, and any key details about the data.

![Dataset structure](https://github.com/user-attachments/assets/9d8b5bde-c15d-485e-9560-4658ce74a5ed)



## Approach and Methodology

### Data Cleaning:

The data in the csv file was already clean and fully populated.

### Exploratory Data Analysis (EDA):

To better understand the data some methods were applied to the data frame. Subsetting and sorting were essential to manipulate data and extract the information needed.

### Analysis:

The results were obtained from the data frame manipulation, using methods like groupby() and sort_values() as well as visualization methods like .iloc[].

The combined SAT Score and thus the Top 10 Schools were calculated through the sum() method. The mean() and the standard deviation - std_dev() - were used in order to calculate the Borough with the largest Standard Deviation.

### Insights:

The last question opens up space for discussions on how to reduce the discrepancy between school scores, which reflect the quality of education.

## Results

Provide summaries and key findings for each question:

Best Math Results: List of schools that meet the criteria, with their math scores.

![Schools sorted by math average scores](https://github.com/user-attachments/assets/412fe726-976e-4852-aab1-044ab364bbd3)



Top 10 Schools by Combined SAT: The top 10 schools and their combined SAT scores.

![Top 10 schools sorted by total score](https://github.com/user-attachments/assets/041e4bb7-a5a5-4512-b8bf-1ba3099de03a)



Borough with Largest Standard Deviation: Name of the borough, number of schools, average SAT score, and standard deviation.

![Borough with the largest standard deviation in total score](https://github.com/user-attachments/assets/a5954ae8-8bf5-4f55-90a7-2abd5de58db3)



## Technologies Used

**Languages**: Python

**IDE**: Jupyter Notebook on Google Colab

**Libraries**: Pandas, NumPy and Matplotlib.

**GitHub** **repo**: https://github.com/gustavo-plc/NYC-Schools

## Skills Demonstrated

Data preprocessing.

Exploratory data analysis and visualization.

Statistical analysis.

Problem-solving and insights generation.

Reproducibility with clean code and well-documented processes.

## Future Improvements

Additional datasets, like schools budget and academic background of teachers, can be combined with the existing data to generate further analysis and insights.

Machine learning could predict future test performance, classify schools by their results to identify the top ten, and analyze performance variations across boroughs to identify influential factors.

Interactive visualizations or dashboards to improve visualization.

## Contact

Feel free to reach out to me through my LinkedIn profile or GitHub repository for any inquiries, feedback, or further discussion.

**LinkedIn**: https://www.linkedin.com/in/gustavo-plc/

**GitHub**: https://github.com/gustavo-plc

I welcome the opportunity to connect with recruiters and others in the industry to discuss potential opportunities or to receive constructive feedback. Let’s stay in touch!
