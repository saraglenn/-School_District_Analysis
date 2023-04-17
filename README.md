# -School_District_Analysis
Pandas/Anaconda/PythonData
## Data Collection
In order to collect the appropriate data the correct path needed to be identified. As such, the os.chdir code was used to locate the file: os.chdir('C:\\Users\\scath\\OneDrive\\Desktop\\Data Analytics Bootcamp\\Module 4 Pandas\\Resources').  

Once the file was located, an alternative path was identified to access and import the data: student_data = os.path.join('..', 'Resources', 'new_full_student_data.csv'). The data was confirmed imported correctly by using the head and tail functions. 
## Cleaning the Data
The dataframe was reviewed to check for rows with missing values and remove any duplicates. String data was then replaced with integer data so a clean analysis could be performed. 
## Summarizing the Data
Generating a statistical summary using the describe function provided an overview of the properties relaed to count, mean, standard deviation, and quartile percentages. The production of this summary very quickly allowed for a broad overview of the whole data set.  
## Analysis
- Minimum overall reading score: 10.5, grade 10, Charter school
- Mean reading score: 72.4
- Budget report: Public schools have a higher budget at $911,195, while charter schools budget is under 900k at $872,625.
- Montgomery High School has the highest student count with 2,038 students in attendance, while Chang High School has 171 students. 
- The charter schools demonstrated a higher overall math score average in grades 9-10, while public school 12th graders scored 4 points higher on average. 
