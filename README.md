This project analyzes student performance based on various factors such as gender, race/ethnicity, parental level of education, lunch type, and test preparation course completion. The dataset used for this project is stored in a CSV file named 'stud.csv'.

To begin with, the project imports necessary libraries such as numpy, pandas, seaborn, matplotlib, and plotly.graph_objects. It also sets up the configuration for matplotlib to display plots inline in the Jupyter notebook. Additionally, the project suppresses warning messages.

The dataset, stored in the variable 'df', contains the following columns:
- gender: Indicates the gender of the student (male/female).
- race_ethnicity: Represents the race/ethnicity group a student belongs to (group A, B, C, D, or E).
- parental_level_of_education: Specifies the educational level of the student's parents (e.g., bachelor's degree, high school, etc.).
- lunch: Indicates the type of lunch the student receives (standard or free/reduced).
- test_preparation_course: Specifies whether the student completed a test preparation course (none or completed).
- math_score: Represents the student's score in the math test.
- reading_score: Represents the student's score in the reading test.
- writing_score: Represents the student's score in the writing test.

The unique values for different columns are as follows:
- Gender: ['female', 'male']
- Race/Ethnicity: ['group B', 'group C', 'group A', 'group D', 'group E']
- Parental Level of Education: ["bachelor's degree", 'some college', "master's degree", "associate's degree", 'high school', 'some high school']
- Lunch: ['standard', 'free/reduced']
- Test Preparation Course: ['none', 'completed']

In the analysis, it was observed that students who received a standard lunch performed better compared to those with a free/reduced lunch. Additionally, students belonging to group E generally performed well in all aspects compared to students from other race/ethnicity groups.

This project is designed to provide a clear understanding of student performance based on various factors.
