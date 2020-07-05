# RGPV-Exam-Result-Analysis

### Abstract

The project would generate report of the result of the students and is also capable of
concluding the result analysis report of the students as in tables, figures in Excel Sheet. The
project is based on python which will use the web scraping technique used to launch the
website from an automated software (as a web browser) to visit the website (RGPV) and
fetch data as results of an individual student, Data analysis which is used to inspecting,
cleansing, transforming and modeling data with the goal of discovering useful information,
informing conclusion and supporting decision-making, in this case with help of machine
learning the prediction for the score of the students can be generate and shown in the format
of figure as graph which concludes average score of batch, current batch, prediction of the
score for the remaining semesters.

## Overview

RGPV EXAM RESULT ANALYSIS report generator is a GUI application designed and
engineered for colleges that need to manage results across multiple branches students that need
to track, manage and report results. This application is programmed on Python, as an interpreted,
high-level, general-purpose programming language. Graphical user interface is design with the
help of tkinter, the standard GUI library for Python. Python when combined with Tkinter
provides a fast and easy way to create GUI applications. Tkinter provides a powerful object-
oriented interface to the Tk GUI toolkit. The project includes two module first on the Result
Analysis and second on the Result Prediction.

<br>

Result Analysis the module is used to fetch the data from web using web scraping with python.
As this project is design specifically for RGPV university site but in future it can be modified for
other result site also. Basically, the project is using web scraping technique on python which
fetch the data from site for an example here I am fetching the data as grades for an individual
student and using the data to generate result analysis in the form tables and figures in excel sheet.
The analysis shows the result on the data for subjects of an individual batch. The data can further
be used to do analysis on the student subject about the weakness and strengths to improve their
performance and explore more for knowledge.

<br>

Result Prediction the module is used to predict the SGPA for the next semester the prediction
uses machine learning technique which is based on supervised machine learning. In machine
learning, regression algorithms attempt to estimate the mapping function from the input variables
to numerical or continuous output variables. This project uses Random Forest Regression, input
as previous year SGPA and predicting the next semester SGPA and comparing the result with the
whole batch as an average of the SGPA’s of student in their batch as in the form of figures as
graph as Current score, Prediction score and Batch Average score. The user can input custom
SGPA also can get prediction on the basis of input data of student score used for particular
student.
