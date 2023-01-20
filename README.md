># *Analysis of District courts in India*

## *Name: Meghana Tedla*
### *Roll No: 2021102002*


```
|_Meghanatedla
    |_ Codes
        |_acts-sections-merged.ipynb
        |_disp-trend.ipynb
        |_judges.ipynb
        |_last-5yrs-cases-merged.ipynb
        |_states-and-courts.ipynb
        |_years-and-state-wise.ipynb
    

    |_Results
        |_Analysis_1
            |_num_cases_year_state_wise.jpg
            |_num_cases_year_wise.jpg
            |_states_and_courts.jpg

        |_Analysis_2
            |_avg_time_taken_to_solve_a_case.jpg
            |_trend_of_disposition_for_2014.jpg
            |_trend_of_disposition_for_2015.jpg
            |_trend_of_disposition_for_2016.jpg
            |_trend_of_disposition_for_2017.jpg
            |_trend_of_disposition_for_2018.jpg
            |_trend_of_top_5_disp.jpg

        |_Analysis_3
            |_Active female judges.jpg
            |_Active male judges.jpg
            |_Inactive female judges.jpg
            |_Inactive male judges.jpg
            |_avg_years_exp_state_wise.jpg

        
    |_ Report.pdf
    |_ README.md
    
```

***There are 6 notebooks.***\
***Run them in the following order.***

### *last-5yrs-cases-merged.ipynb*
    - Merges the cases data from 2014 to 2018.
    - Converts the data frame into a .csv file which will be imported into other notebooks.

### *years-and-state-wise.ipynb*
    - Reads 'cases_last_5yrs.csv' into a dataFrame that was created in another notebook.
    - Creates a data frame which has shows the number cases filed per year from 2014 to 2018.
    - Creates a data frame that shows the number od cases filed year wise and state wise.
    - Plots a line graph for each state over the years of 2014 to 2018.

### *disp-trend.ipynb*
    - Reads 'cases_last_5yrs.csv' into a dataFrame that was created in another notebook.
    - Merges the cases data and the disposition keys.
    - Creates a data frame that has the number of cases for each disposition year wise in decsending order.
    - Creates a data frame and plots a bar graph that gives the number of cases filed for 5 common dispositions.
    - Creates a data frame and plots a line graph for the trend of average time taken to solve a case of a disposition.

### *judges.ipynb*
    - Merges the data of judges and courts to form a bigger data set
    - Tabulates the number of male and female judges state wise.
    - Tabulates the number of male and female judges district wise.
    - Tabulates the number of male and female judges court wise.
    - Creates a table based on gender of judges.
    - Tabulates and creates a pie chart showing the percentage of working and retired, male and female judges.

### *states-and-courts.ipynb*
    - Tabulates the number of courts and percentage per state.
    - This data is presented by a pie chart.

### *acts-sections-merged.ipynb*
    - Merges the data about cases and the acts and sections.

