# INX-Future-Inc-Employee-Performance-Rating-Analysis-using-Power-BI

Requirement

INX Future Inc, is one of the leading data analytics and automation solutions provider with over 15 years of global business presence. In recent years, the employee performance indexes are not healthy and this has become a growing concern among the top management. The CEO Mr. Brain, decided to initiate a data science project, which analyzes the current employee data and find the core underlying causes of the performance issues.
The following insights are expected from this project:
•	Department wise performances.
•	Important Factors effecting employee performance.
•	Recommendations to improve the employee performance based on insights from analysis.

Process

The project was done with the purpose of finding out factors that affected the performance of the employees by analysing the data to provide recommendations to improve the performance and gain insights from the analysis. The following steps were carried out:

1.	Import the data provided, understand the data definitions, and identify the important features from the dataset for further analysis.
2.	The most important features selected are years since last promotion, employee job role, employee last salary hike percentage, employee hourly rate, employee job satisfaction, employee work life balance, employee department, and gender.
3.	Understand the correlation between the above-defined factors and performance rating by plotting each factor against performance rating on a line/bar graph and scatter plot.
4.	Define Key Performance Indicators (KPIs) from the dataset to derive meaningful and impactful results.

Analysis & Insights:

In contrary to the popular belief, there was no direct relationship identified between employee job satisfaction and work life balance to performance rating. There was no positive or negative correlation identified.

The important factors affecting performance rating are:
*	Years since last promotion:
 *  Employees recently promoted had the highest performance rating and decreased with the years since the last promotion. 
  -  This correlation is 98% accurate with an exception of only 2% of employees (Promoted after 13 years and still had a good performance rating).
        85.5% of employees had an average performance rating of 2.76 or higher within 5 years of last promotion.
  -    The median of average performance rating is 2.85 (as highlighted in the dashboard)	
    
* Employee last salary hike percentage:
  *	Average performance rating increased with the higher % of salary hike, i.e., employee who received a higher salary hike displayed a higher performance.  
    -  	This correlation is 82.5% accurate with an exception of 17.5% of employees (who had a salary hike of 21% or greater but still had a poor performance rating). This is highlighted in Red in the dashboard 
      using   conditional formatting.
*	Employee Job Role:
*	Business Analysts have the highest average performance rating of 3.19 followed by developer (3.11) and Technical lead (3.08)
    - 	Top 3 Departments with higher average performance rating:
         1.	Development -  3.09
         2.	Data Science - 3.05
         3.	Human Resources – 2.93
    

Dashboard
 ![image](https://github.com/Shuchitagg/INX-Future-Inc-Employee-Performance-Rating-Analysis-using-Power-BI/assets/59108428/77973739-b91d-442c-8f8b-7e7a185ccea4)

 Recommendations:

*	It is evident from the results that INX Future Inc. should identify the employees not been promoted over 5 years or given salary hikes of less than 20% and consider developing intrinsic and extrinsic ways of motivating this group to perform better. Adequate coaching is to be provided to address their learning/skills gap to upskill them to outperform.
*	Shuffling the job roles of employees and training them in different domains would help build a T-shaped skillset and increase performance rating. 
