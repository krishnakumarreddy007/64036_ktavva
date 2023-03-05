# Business Analytics (MIS 64036):

Assignment 1 – Setting Up R

Purpose:
The purpose of this assignment is to set up and use the tools for this course.

Learning Outcomes:
• Analyze the role of descriptive statistics in data exploration phase of analytics projects (CLOs 1, 4, and 6)
• Module 2 Learning Outcomes:
  o Install Base R and dependent Libraries.
  o Identify key variable types in R.
  o Identify different parts/modules of R-studio environment.
  o Run basic commands in R.
  o Import/export data to/from R.

After downloading and Install R and R-Studio. You will need to complete the following tasks:
1. Install the ISLR library using the install.packages() command. Call the library using the library(ISLR) command to ensure that the library is correctly installed (10% of total points)
2. Create a new R-Notebook (.Rmd) file. In the first code chunk, call the ISLR library and then print the summary of the Carseats dataset. How many observations (rows) this dataset contains? (15% of total points)
3. Using the summary statistics shown above, what is maximum value of the advertising attribute? (15% of total points)
4. Calculate the IQR of the Price attribute. (15% of total points)
5. Plot the Sales against Price. What do you see in there? Calculate the correlation of the two attributes. What does the sign of the correlation coefficient suggest? (15% of total points)
6. Format your notebook file by providing description and document title. Also use # to add comments to your code. (15% of total points)
7. Knit the output file to html, pdf , word and submit the output document. (15% of total points)
Note: If you are trying to Knit to PDF, you may get the following error message
Error: LaTeX failed to compile…. '"pdflatex"' not found. Execution halted
If so, you can use the console to install the following libraries and try again
• install.packages("knitr")
• library(knitr)
• install.packages("tinytex")
• tinytex::install_tinytex()
