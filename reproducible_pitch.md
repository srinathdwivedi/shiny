reproducible_pitch
========================================================
author: sri nath dwivedi
date: 21-09-2017
autosize: true

First Slide
========================================================

This was built for the course: **Developing Data Products** as part of the Coursera Data Science Specialization.

The shiny app developed for this assignment is avalilable: https://magnolia.shinyapps.io/Shiny-Application-and-Reproducible-Pitch/

The source codes of ui.R and server.R and also Rpresentation are available on the GitHub repo: https://github.com/Magnoliam/Shiny-Application-and-Reproducible-Pitch

Exam Marks Calculation and Interpretation
========================================================
The average mark for the three exams written is calculated based on the following formula:
Average mark = (x + y + z)/3

Where:

- x = Databases Score 
- y = Data Analytics score 
- z = Project Management score 

Exam Intrepretation
========================================================

**Example:**
For a score of **80** in Database, **97** Data Analytics and **64** Project Management.

Average Score is **80,333**

- Average <70, : Failed
- Average [70-79] , : Considered for the database administrator position
- Average [80-89] , :Considered for the data administrator position
- Average >= 90 : Considered for the business intelligence manager position


Shiny App: Interactive BMI Calculator
========================================================

### Sidebar panel

- numericInput: Value of Database score
- numericInput: Value of Data Analytics score
- numericInput: Value of Project Management score

### Main panel

- Short description of Average value
- Make calculation on server side
- Display the calculated average value
- Display Intepretation


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](reproducible_pitch-figure/unnamed-chunk-2-1.png)
