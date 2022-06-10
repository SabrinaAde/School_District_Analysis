# School_District_Analysis

Overview of the school district analysis: The purpose of the code is to automate the calculation and display of students from different schools within various districts to determine their performance in reading and math based standerdize tests. 

How is the district summary affected?
The district summary is altered by dropping the 9th grad scores in both reading and math from Thompson high school due to their grades then recalculate passing grades for the district. 

![image](https://user-images.githubusercontent.com/35518346/172978323-033f6f4d-e10c-4b4f-8d13-65764533e6ff.png)

How is the school summary affected?
Created a new dataframe called 'per_school_summary_df' that includes all data excluding the 9th grade scores in reading and math from Thompson High School. The School summary shows all of the passing grades in math, reading along with the passing % in the previously mentioned subjects. It shows a good summary of the performance of all the schools in the different districts without be skewed by the poor results in Thompson

![image](https://user-images.githubusercontent.com/35518346/172978905-d2817dc4-48b1-4dd0-8c05-391907fc051b.png)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
passing math and reading scores from Thompson was reintroduced to the school summary dataframe. This is done by setting passing scores by being >70. This essentially helps to artifically inflate the performance of Thompson school since the 9th grade class is removed. Code used to set the condition and define Thompson school from the entire dataframe is defined below. 

![image](https://user-images.githubusercontent.com/35518346/172979509-e9f5a913-20b9-4516-886b-40e8fc93dda1.png)


