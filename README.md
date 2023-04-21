# US_Colleges_Analysis

## Dataset

### Source and Editing
* The dataset of US College admission details has been considered from Kaggle.
* Reference: https://www.kaggle.com/datasets/yashgpt/us-college-data
* The questions and the solutions are mentioned below.

### Data Dictionary
* Group: A categorical variable indicating whether the college is public or private. 1 indicates a private college and 0 indicates a public college.
* Private: A binary variable indicating whether the college is private or not. 1 indicates a private college and 0 indicates a public college.
* Apps: The total number of applications received by the college.
* Accept: The total number of applications accepted by the college.
* Acceptance_70: The acceptance rate of the college. (Acceptance rate = Accept/Apps, >70% - 1, else - 0) - This column has been added manually for analysis.
* Enroll: The total number of students enrolled in the college.
* Top10perc: The percentage of new students who ranked in the top 10% of their high school class.
* Top25perc: The percentage of new students who ranked in the top 25% of their high school class.
* F.Undergrad: The total number of full-time undergraduate students enrolled in the college.
* P.Undergrad: The total number of part-time undergraduate students enrolled in the college.
* Outstate: The out-of-state tuition fee for the college.
* Room.Board: The cost of room and board for the college.
* Books: The estimated cost of books and supplies for a year of study.
* Personal: The estimated personal expenses for a year of study.
* PhD: The percentage of faculty members who hold a PhD degree.
* Terminal: The percentage of faculty members who hold a terminal degree in their field of study.
* S.F.Ratio: The student-to-faculty ratio for the college.
* perc.alumni: The percentage of alumni who donate to the college.
* Expend: The instructional expenditure per student at the college.
* Grad.Rate: The graduation rate of the college as a percentage.


## Questions I tried to answer

1. Based on the given variables, can we classify the colleges based on their type (Public/Private)?

2. Based on the given variables, can we predict the type of college?


## File Dictionary

* US_College_Analysis_Report.pdf file gives the brief report of the questions answered and the hypothesis results.
* College_Data_Cleaned.csv is the dataset considered for the analysis where randonly 30 colleges where chosen from the original master college dataset from Kaggle website.
* The US_College_Analysis.Rmd file contains the R code for the complete analysis performed, the flow of thought process, and inferences mentioned after each step.
* The US_College_Analysis.html file gives the output of the Rmd file which includes the outputs of the file with visuals and inferences.

