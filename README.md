# US_Colleges_Analysis

## Dataset

### Source and Editing
* The dataset of US College admission details has been considered from Kaggle.
* Reference: https://www.kaggle.com/datasets/yashgpt/us-college-data
* Randomly 30 colleges have been selected for the analysis.
* The hypothesis and the questions that were attempted have been provided below.

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

## Hypotheses

* More students prefer Public universities over Private universities.
* The costs associated with Public universities are less compared to Private universities.
* Public universities have better acceptance rates compared to Private universities.
* The differentiation between Public and Private institutes can be classified using Multivariate Analysis techniques.


* We can test our Hypothesis at the end of the analysis.

## Questions I tried to answer

* Investigate the relationships between the universities based on given variables using Principal Component Analysis. Do we find any relations, and can we analyse if there is any difference between the Private and Public Universities

* Carry out cluster analysis to study the relationship between the universities and find out if there are any reasons behind the clustering. Is the clustering done based on the type of university or something different?

* Identify the important factors underlying the observed variables and examine the relationships between the universities for these factors. Check if the factors help us classify the type of university (Public/Private)

* Using regression, can we predict the acceptance rate of the universities based on all the factors provided for the universities? Which regression technique works best for this?


## File Dictionary

* US_College_Analysis_Report.pdf file gives the brief report of the questions answered and the hypothesis results.
* College_Data_Cleaned.csv is the dataset considered for the analysis where randonly 30 colleges where chosen from the original master college dataset from Kaggle website.
* The US_College_Analysis.Rmd file contains the R code for the complete analysis performed, the flow of thought process, and inferences mentioned after each step.
* The US_College_Analysis.html file gives the output of the Rmd file which includes the outputs of the file with visuals and inferences.
* US_College_Analysis_Report.ppt file is a bit more detailed presentation of the Report with more visuals and inferences used for presentation.

