# pandas-challenge
Challenge for Module 4 - Pandas &amp; Jupyter

This challenge uses the reading and merging of two CSV files containing school district and student test score data to analyze factors that may contribute to student scores on math and reading exams and the overall share of students that may pass.
Utilizing Pandas functions such as Data Frames, Group By, Mean, Sum, Unique/Counts, Formatting, etc., combined with personal notes and in-class examples I was able to find the below insights (which can also be found in the Python Function main.py). Please utilize Jupyter Notebook to perform this analysis using the below navigation functions in Terminal: 
	cd Desktop
	conda activate dev
	jupyter notebook

**Analysis**
From a topline perspective, Reading as a subject tends to see higher than average scores than Math, also seeing higher shares of passing students vs. Math. Overall passing rate for both Math and Reading are about 65% - see below for areas of strength and improvement based on my analysis of the school district and student summary. 

Higher budget does not necessarily correlate with better performance, in fact the opposite. Schools with <$585 per-capita budget saw the highest average test scores, with nearly 90% of students passing both Math and Reading; Schools with the highest spending ranges (645-680) saw the lowest scores across math and reading, with only 53% of students passing overall.

District vs. Charter appears to have the largest impact on student performance, with 90% of charter students passing overall, vs. only 54% of District students passing.
Size of school may play a role in this, with Small to medium size schools seeing the strongest performance, while large schools see overall passing rate fall to 58%.
Because charter schools on average see larger per capita budget, there are opportunities to reallocate budgets from existing programs to providing more teachers and smaller classroom settings to students in the school.

Examples of additional data that can be useful for performing this analysis can be average teacher tenure, as well as average hours spent studying per student. Addionally, budget allocation by department can also be useful data to see if it affects math vs. reading scores. Socioeconomic data could also be a useful value-add to this analysis, as it would provide external insights that could be affecting student test scores.
