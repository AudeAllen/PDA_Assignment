# PDA_Assignment

# Programming for Data Analysis Project

## Table of contents
* [1 Introduction project](#1-introduction-project)
    * [Problem Statement](#problem-statement)
* [2 Software needed to run the project](#2-software-needed-to-run-the-project)	
* [3 Attendances at an Emergency Department over a period of 24 hours](#3-attendances-at-an-Emergency-Department-over-a-period-of-24-hours)	
* [4 Types of Variables and Scales of Measurement](#4-types-of-variables-and-scales-of-measurement)
    * [Registration](#registration)
    * [DISCH_DEST](#dISCH_dEST)
    * [Age](#age)
    * [Hours_in_Department](#hours_in_department)
    * [TRIAGE_CATEGORY](#tRIAGE_cATEGORY)
    * [Sex](#sex)
* [5 Simulation of Dataset](#5-simulation-of-dataset)   
* [6 Correlation](#6-correlation)    
* [7 Conclusion](#7-conclusion)             
* [8 References](#8-references)   


1 Introduction project
======
### ***Problem Statement***

For this project you must create a data set by simulating a real-world phenomenon of
your choosing. You may pick any phenomenon you wish – you might pick one that is
of interest to you in your personal or professional life. Then, rather than collect data
related to the phenomenon, you should model and synthesise such data using Python.
We suggest you use the numpy.random package for this purpose.<br><br>
Specifically, in this project you should:<br><br>
    • Choose a real-world phenomenon that can be measured and for which you could
    collect at least one-hundred data points across at least four different variables.<br>
    • Investigate the types of variables involved, their likely distributions, and their
    relationships with each other.<br>
    • Synthesise/simulate a data set as closely matching their properties as possible.<br>
    • Detail your research and implement the simulation in a Jupyter notebook – the
    data set itself can simply be displayed in an output cell within the notebook.<br>



2 Software needed to run the project 
======

-	Visual Studio Code
-	Python 3 
-	Github - https://github.com/AudeAllen/PDA_Assignment
-   Jupyter Notebook

How to run PDA_Assignment project - 
- I have created my jupyter notebook in VS Code and uploaded to Github
- The link to Github is https://github.com/AudeAllen/PDA_Assignment
- My Jupyter Notebook is called PDA_Assignment.ipynb
- I have uploaded all of my project files to my github respository.  Git is a version control system that I use in this project. (See Github link above)
- Once in Github you will see my project file and links
- You can download the Jupyter notebook from this location
- I have all my images in the 'Images' folder
- I have two .csv files 1. EDAttendances24Hour.csv (Original data file that I am basing my project on) 2. SimulatedED.csv (My simulated data file)
- There are 6 variables in my dataset that I will analysis and simulate


- This will run the script and create all the graphs and visual aids for this project
- I have uploaded all of my project files to my github respository.  Git is a version control system that I use in this project. (See Github link above)


The below libraries/packages were imported to aid analysis on the dataset
- import numpy as np - numpy is a package for scientific computing in python  
- import pandas as pd - python package that is used for data analysis
- import matplotlib.pyplot as plt - data visualisation tool 
- import seaborn as sns - data visualisation tool
- import datetime as dt - Useful for visualising datetime in Python
- import random - Random distribution funcionality


3 Attendances at an Emergency Department over a period of 24 hours 
======
In this section I will go into some detail about the real world phenomenon that I have chosen for this project and why. I have chosen the phenomenon of 24 hours in an Emergency Department. 


4 Types of Variables and Scales of Measurement
======

This section of my project goes into detail about the variable types in my dataset. I will explain the data types that can be assigned and why you would assign a particular data type to a variable.


### ***Registration***

This is the datetime that a patient arrives at the Emergency Department. I go into detail in this section about the variable Registration, the type of variable it is, type of distribution. Finally I simulate 24 hours data by using a numpy.random distribution function.

### ***DISCH_DEST***

The DISCH_DEST is the location the patient goes to after they leave the emergency department. I go into detail in this section about the variable DISCH_DEST, the type of variable it is, type of distribution. Finally I simulate 24 hours data by using a numpy.random distribution function. 

### ***Age***

This is age of the patient at the time of the attendance to the Emergency Department.  I go into detail in this section about the variable Age, the type of variable it is, type of distribution. Finally I simulate 24 hours data by using a numpy.random distribution function.

### ***Hours_in_Department***

This is the length of time in hours that a patient has spent in the department. Again I will go into detail in this section about the variable Hours_in_Department, the type of variable it is, type of distribution. Finally I simulate 24 hours data by using a numpy.random distribution function.

### ***TRIAGE_CATEGORY***

The Triage Category is based on the Manchester triage system. The Manchester Triage System is one of Europe's most used triage systems considering five levels to prioritize patients in the ED: level 1 (red), immediate; level 2 (orange), very urgent; level 3 (yellow), urgent; level 4 (green), standard; level 5 (blue), non-urgent.

I will go into detail in this section about the variable TRIAGE_CATEGORY, the type of variable it is, type of distribution. Finally I simulate 24 hours data by using a numpy.random distribution function.

### ***Sex***

This variable describes the gender of the patient. I will go into detail in this section about the variable Sex, the type of variable it is, type of distribution. Finally I simulate 24 hours data by using a numpy.random distribution function.


5 Simulation of Dataset
======

This section of my project after deciphering the type of variable, distribution of each of the variables I will simulate the 6 variables for 24 time period with a date of 02/11/2023.

6 Correlation
======
Correlation is a statistical measure that expresses the extent to which two variables are linearly related (meaning they change together at a constant rate). It's a common tool for describing simple relationships without making a statement about cause and effect.

In this section I detail the correlations between the different variables on both the original and simulated dataset.

7 Conclusion
======

Conclusion of project


8 References
======

https://www.investopedia.com/terms/b/bell-curve.asp#:~:text=The%20term%20%22bell%20curve%22%20is,given%20values%20around%20the%20mean

https://www.scribbr.com/statistics/poisson-distribution/#:~:text=A%20Poisson%20distribution%20is%20a,the%20mean%20number%20of%20events

https://studyonline.unsw.edu.au/blog/types-of-data#:~:text=Psychologist%20Stanley%20Stevens%20developed%20the,to%20properly%20analyse%20the%20data

https://bobbyhadz.com/blog/python-typeerror-object-of-type-int-has-no-len

https://blog.finxter.com/manipulating-dates-and-times-in-python/

https://pynative.com/python-timestamp/

https://medium.com/nerd-for-tech/analyse-the-distribution-of-ages-python-data-analysis-series-part-1-cc0fb2ca7f36

https://www.geeksforgeeks.org/random-sampling-in-numpy-randint-function/

https://stats.oarc.ucla.edu/other/mult-pkg/whatstat/what-is-the-difference-between-categorical-ordinal-and-interval-variables/#:~:text=A%20categorical%20variable%20

https://numpy.org/doc/stable/reference/random/generated/numpy.random.triangular.html

https://numpy.org/doc/stable/reference/random/generated/numpy.random.lognormal.html

https://www.sciencedirect.com/science/article/abs/pii/S1755599X20301038#:~:text=The%20Manchester%20Triage%20System%20is,blue %2C%20non%2Durgent

https://www.jmp.com/en_au/statistics-knowledge-portal/what-is-correlation.html#:~:text=What%20is%20correlation%3F,statement%20about%20cause%20and%20effect

https://www.geeksforgeeks.org/python-pearson-correlation-test-between-two-variables/

https://karger.com/ger/article-abstract/59/1/17/148039/Correlation-between-Age-Emergency-Department?redirectedFrom=fulltext

https://emj.bmj.com/content/32/12/994.1

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8830250/

