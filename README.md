# pandas-challenge
Module 4 Analysis
1) Overview
	For this module challenge, I had to act as though I were my city’s, school district’s, new Chief Data Scientist. I assisted the school board and mayor to make strategic decisions regarding future school budgets and priorities. 
	My task was to analyze the district-wide standardized test results. I had been given access to every student's math and reading scores, as well as various information on the schools they attend. My goal was to aggregate the data to showcase obvious trends in school performance.
2) Data, models, and results
The initial data sets I was given were two CSVs. One containing student data which contained the student’s name, the school they attended, grade, gender, and their reading and math scores. The other with the school’s data which was their type of school, size, and budget. To make it easier to manipulate the data we combined the CSV datasets together. 
First, I completed a district summary. Retrieving counts of the schools and students, the total budget amongst the schools, averages of the math and reading scores within the district, and what percent of students are passing their reading and math courses. By creating a new data frame of the results of this information I was able to create the following table.
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/119901186/214451356-1f7a8da0-1a6d-4a79-a9d0-f683c1acf551.png">

	Next, I completed a school summary. Using the necessary calculations, I was able to create a new data frame to summarize key information about each school, I found school name and type, total students for each school, school individual budgets, per student budget, average math and reading scores, and percent passing rates. I was able to display this data frame in the table below.  
 <img width="391" alt="image" src="https://user-images.githubusercontent.com/119901186/214451488-e377d441-7c3e-44f6-bc48-8617fee9a93d.png">

	We then look and the top and bottom-performing schools. Creating two new data frames to do this. This helps the district find what is working well and what needs more work within the district. The first table below is of the top-performing schools in the district. 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/119901186/214451508-af425f8e-fca8-4cca-84b0-0918d26f6d66.png">

This second table is of the bottom-performing schools in the district. 
 <img width="378" alt="image" src="https://user-images.githubusercontent.com/119901186/214451533-9f9b3499-5721-4d33-8cd2-93f9ec42ce58.png">

	Then we will individually look at each grade comparing math and reading scores. This first table, on the left, displays the math scores per grade, per school. The table on the right displays the reading scores per grade, per school. Just by comparing the two, we can assume more students across all grades and most schools do better in reading than in math. 
  <img width="198" alt="image" src="https://user-images.githubusercontent.com/119901186/214451597-4e935a83-3762-48f7-b60b-d51e63267a81.png">
<img width="197" alt="image" src="https://user-images.githubusercontent.com/119901186/214451626-ed076aa1-870d-4ecc-9563-59142b6144a6.png">

	We also look at the scores comparing them to school size. The following table shows the data frame I used to compare average scores and passing rates to the size of the school.
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/119901186/214451662-d685d78d-9dc2-4689-be41-77ebe861ba33.png">

	Finally, we looked at school type. I looked at two types of schools, charter, and district. We compared the type of school to the average scores and passing rates.
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/119901186/214451690-81aebbc3-0cde-4f5f-bdb0-246c71d023e8.png">

4) Conclusion 
	We used this school and student data to make comparisons and try to find patterns between student scores and what school they are going to and how much money that school spends, the type of school, and the size of the school to see if those factors affected the student's math and reading scores. 
	From our new data frames that made analyzing this data easier, we can make conclusions to answer these questions. First, looking at the school type, District vs. Charter, we can see that Charter schools in this school district have higher averages of both reading and math scores and a higher percentage of their students are passing these courses. When looking at the data frame showing the top and bottom-performing schools we can see that all the top-performing schools, were all Charters and all the bottom-performing were Districts. This can lead us to conclude that students going to Charters will perform better in class than in a District school.
	Another conclusion we could draw is that size affects student performance. From our data frame comparing school size and course score we can see that large schools, those ranging from 2000-5000 students have lower reading and math scores and only 56% of the students are passing in the larger schools. But, in the small and medium schools <1000 or 1000-2000, there's a huger increase in overall passing at 90% of the students passing both.
![image](https://user-images.githubusercontent.com/119901186/214451249-08ff1f1d-8975-48eb-80ae-29fcf5797e08.png)
