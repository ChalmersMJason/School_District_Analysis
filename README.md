# School_District_Analysis
Module 4 Python Pandas

## Overview
This analysis was performed for the school board to investigate evidence of academic dishonesty found in the data file 'students_complete.csv'. Suspicious data was found associated with Thomas High School. The purpose of this analysis is to remove the suspicious data and rerun a previous analysis to see how the results are impacted. The analysis will offer the school board key metrics on test scores & budget spending broken down by school and school type. 

## Resources
This analysis leveraged the following:
* Jupyter Notebook
* Python 3.7
* Data from the file 'students_complete.csv'
* Built on a former analysis performed in Module 4

## Results
Adjusting the Thomas High School data had the following impact on the analysis:
* District Summary
  * Drove key metrics slightly lower as shown in images below. The following decreased:
  * Avg Math Score - down 0.1% 
  * % Passing Math - down 0.2%
  * % Passing Reading - down 0.3%
  * % Overall Passing - down 0.1%
  
* District Summary - Initial Data:
![District_Summary - Initial](https://user-images.githubusercontent.com/85259984/132100090-75ed10b2-78b5-4f91-b740-cf02f233d6a6.PNG)
* District Summary - After adjusting Thomas High Data:
![District_Summary - Challenge](https://user-images.githubusercontent.com/85259984/132100092-859e1eef-be5a-42e4-86f0-677099314605.PNG)


* School Summary
  * Drove key metrics slightly lower as shown in images below. The following decreased:
  * Avg Math Score - down 0.06% 
  * Avg Reading Score - up 0.05%
  * % Passing Math - down 0.4%
  * % Passing Reading - down 0.03%
  * % Overall Passing - down 0.3%
  
* School Summary - Initial Data:
![School_Summary - Initial](https://user-images.githubusercontent.com/85259984/132100328-3e4a48db-8696-4711-9ff5-cdf4dceddb35.PNG)
* Summary - After adjusting Thomas High Data:
![School_Summary - Challenege](https://user-images.githubusercontent.com/85259984/132100307-be530254-6037-4a76-915c-e28732690d16.PNG)

* Replacing the ninth graders' math and reading scores had little impact on Thomas High Schools' performance relative to the other schools. Even after changing the data, the overall passing % for Thomas High was still over 90% which ranks it as one of the top schools that data was collected for. 

# Impact on scores by various dimensions

* Math and reading scores by grade
    * This analysis had little impact on the overall scores by grade. The only impact was Thomas High School being replaced with nulls in 9th grade. An example of this can be seen below:

![By_Grade_Challenege](https://user-images.githubusercontent.com/85259984/132101145-d2ba2e6a-085b-4155-8fca-4a779fcd2dac.PNG)



* School Spending
    * This analysis resulted in increased metrics for the $630 - $644 spending bin, as shown in the images below.

Pre ![Scores_School_Spending - Initial](https://user-images.githubusercontent.com/85259984/132101160-f57062e4-c0fa-4d87-b2d4-7d3366fa4b1d.PNG)



Post ![Scores_School_Spending - Challenge](https://user-images.githubusercontent.com/85259984/132101206-981a6c62-f50c-4b9e-8882-e9cd85eea491.PNG)


* School Size
* *
* Pre
![Scores_School_Size - Initial](https://user-images.githubusercontent.com/85259984/132100644-6a4197f0-400d-4775-807a-5a6f93ed2db2.PNG)
* Post
![Scores_School_Size - Challenge](https://user-images.githubusercontent.com/85259984/132100648-04cf1ee0-1704-41c3-b145-7bf067a5d5fb.PNG)

* School Type
* *
* Pre
![Scores_School_Type - Initial](https://user-images.githubusercontent.com/85259984/132100662-efafd1df-71e4-4285-9315-057a8d6a7835.PNG)
* Post
![Scores_School_Type - Challenge](https://user-images.githubusercontent.com/85259984/132100666-4a476285-1afd-4e1a-b062-989cdc28afdb.PNG)



