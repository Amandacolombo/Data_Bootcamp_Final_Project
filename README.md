# Data_Bootcamp_Final_Project


This project was completed by Amanda Colombo, Lewis Percy, and Daniel Gulda in partial fulfilment of ECON-UB.0232,
Data Bootcamp, Spring 2019. I certify that the NYU Stern Honor Code applies to this project.
In particular, I have:
Clearly acknowledged the work and efforts of others when submitting written work as our own.
The incorporation of the work of others–including but not limited to their ideas, data, creative
expression, and direct quotations (which should be designated with quotation marks), or paraphrasing thereof– 
has been fully and appropriately referenced using notations both in the text
and the bibliography.
And I understand that:
Submitting the same or substantially similar work in multiple courses, either in the same semester
or in a different semester, without the express approval of all instructors is strictly forbidden.
I acknowledge that a failure to abide by NYU Stern Honor Code will result in a failing grade for
the project and course.

Project Description:

The main question we are exploring in our analysis is, 
"What are the most important predictors for the absence of solar panels in communities across the United States?"
In order to answer this question we will be utilizing the extensive deep solar dataset, compiled by Stanford Engineering 
in 2018. This dataset uses deep learning and satelite imagery to gather data on residential and non-residential solar 
installations in the United States, at the census-tract level. This data is then combined with a series of other demographic
and meteorologic variables e.g. median age, average solar radiation, household income and voting patterns. The dataset is 
extensive, with over 72,000 rows and 169 columns. The question we look to answer while analyzing this dataset is, 
"what are the key indicators for the lack of solar panels in an area?". Various classification methods were trialed for 
accuracy, before deciding that Random Forest produced the most accurate results - with an accuracy figure of greater than 80%.
From this analysis feature importance was used to analyse which features contributed most heavily to this performance. 
It was found that total land area was by far the most predictive both in the U.S. as a whole as well at New York state. 
The workflow to generate these results is demonstrated.
