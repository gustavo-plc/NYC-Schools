# Analyzing NYC Public School SAT Scores: Insights for Policy Makers, Researchers, and Parents


1. **Overview**

    Every year, school test results impact the college admissions fate of millions of students. In this project, standardized test performance data from NYC's public schools will be used to identify the schools with top math results, analyse how performance varies by borough, and find the city's top ten performing schools!


    ![New York City schoolbus](schoolbus.jpg)


    Skills involved: data cleaning, data analysis, data visualization, and insights generation.
   


2. **Problem Statement**


    This project aims to properly answer these questions:

    a) Which NYC schools have the best math results?

    b) What are the top 10 performing schools based on combined SAT scores?

    c) Which borough has the largest standard deviation in SAT scores, and what insights can we derive from it?
   


3. **Dataset**
   

    File name: schools.csv
   
    Description: Includes SAT performance data of NYC public schools (as image below).

    ![image](https://github.com/user-attachments/assets/14c2dfab-5369-4b2e-bf77-2c4363a2270c)


    Source: Publicly available.
   
    Size and structure: Share the number of rows, columns, and any key details about the data.


    ![image](https://github.com/user-attachments/assets/9d8b5bde-c15d-485e-9560-4658ce74a5ed)



4. Approach and Methodology

    
    Data Cleaning:
   
       The data in the csv file was already clean and fully populated.
   
    Exploratory Data Analysis (EDA):
   
        To better understand the data some methods were applied to the data frame. Subsetting and sorting were essential to manipulate data and extract the information needed.
   
    Analysis:
   
        The results were obtained from the dataframe manipulation, using methods like groupby() and sort_values() as well as visualization methods like .iloc[].
   
        The combinated SAT Score and thus the Top 10 Schools were calculated through the sum() method. The mean() and the standard deviation - std_dev() - were used in order to calculate the Borough with the largest Standard Deviation.
   
    Insights:
   
        The last question opens up space for discussions on how to reduce the discrepancy between school scores, which reflect the quality of education.



6. Results

    Provide summaries and key findings for each question:
        Best Math Results: List of schools that meet the criteria, with their math scores.
        Top 10 Schools by Combined SAT: The top 10 schools and their combined SAT scores.
        Borough with Largest Standard Deviation: Name of the borough, number of schools, average SAT score, and standard deviation.
    Include links to view the DataFrames (e.g., best_math_schools, top_10_schools, largest_std_dev) or a preview of their outputs.





7. Technologies Used


   Languages: Python
   
   IDE: Jupyter Notebook on Google Colab
   
   Libraries: Pandas, NumPy and Matplotlib.
   
   GitHub repo: https://github.com/gustavo-plc/NYC-Schools



9. Skills Demonstrated

    
   Data preprocessing.
   
   Exploratory data analysis and visualization.
   
   Statistical analysis.
   
   Problem-solving and insights generation.
   
   Reproducibility with clean code and well-documented processes.




10. Future Improvements



    Additional datasets, like schools budget and academic background of teachers, can be combined with the exisiting data to generate further analysis and insights.

    Machine learning could predict future test performance, classify schools by their results to identify the top ten, and analyze performance variations across boroughs to identify influential factors.

    Interactive visualizations or dashboards to improove visualization.




11. Contact

    Feel free to reach out to me through my LinkedIn profile or GitHub repository for any inquiries, feedback, or further discussion.
    
    LinkedIn: https://www.linkedin.com/in/gustavo-plc/
    
    GitHub: https://github.com/gustavo-plc
    
    I welcome the opportunity to connect with recruiters and others in the industry to discuss potential opportunities or to receive constructive feedback. Let’s stay in touch!
