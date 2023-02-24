# Pewlett_Hackard_Challenge

## Background

  Pewlett-Hackard(PH) is a business firm that currently has 300,024 hired employees. The management at PH has informed us that many of their employees are reaching retirment age which will create many new job openings within the firm. PH wants to be prepared for this and make sure that the employees that are retiring can act as mentors to train the new generation of workers who would take the place at the firm.
  
## Overview of the Analysis

  The goal of the analysis is to gather data persisting to the employees that are reaching retirment age. PH has given us a date range of employees born between January 1st, 1952, to December 31, 1955. 
  
  The DB given by PH cinsists of 6 CSV files:
    -Employees 
    -Departments
    -Dat_emp
    -Dept_manager
    -Titles
    -Salaries
  
  ![PH_ERD](https://user-images.githubusercontent.com/119640010/218569173-a53359e4-8d4d-49bc-b73d-dc1fa5d1d0dd.PNG)

## Results

### Number of retiring employees by title.

### Code used to create table:
![image](https://user-images.githubusercontent.com/119640010/221254567-e0d5dad8-1c60-4be0-9c55-34ebf2c60562.png)


The image below shows the names of the employees that were born between 1952 and 1955. Note that there are some duplicates. This is because some of the employees titles have changed over the years and further filtering of the data is needed. 

![PH_Retiring_by_title](https://user-images.githubusercontent.com/119640010/218589652-95b544e1-63d4-4541-a6fa-db0b35b8c658.PNG)


### Unique Titles

The table below shows the same thing as the table before, but without the duplicates. This table is still very large with over 90,000 lines and will need to be refined further.

![PH_Unique_titles](https://user-images.githubusercontent.com/119640010/218589753-5466d950-70ec-4438-b52b-e4b9afcc2d64.PNG)



