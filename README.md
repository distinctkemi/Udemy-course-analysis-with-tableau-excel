Project Description: Assuming I am a data analyst at Udemy, I have been given a task by my manager to present the data on course revenue, and I have been provided with data on courses from different topics to understand where opportunities to increase revenue may lie, and track the performance of courses.
My manager has suggested encouraging Web Development courses to charge more because she believes that these are the most popular courses.

This [repository](https://github.com/distinctkemi/Udemy-course-analysis-with-tableau) contains both the dataset used for the study and a comprehensive report on the analysis' results.

About the dataset: There were four datasets for different subjects (web development, business finance, graphic design and musical instruments) and they were merged to make a single file, after merging the dataset consist if 3,677 rows and 12 columns. The columns in this dataset include:

| Column title | Description |
|---------------| ------------------ |
|`Course_id`    | This is a unique id number for each course |
|`Course_title` | Title of course                            |
| `Url` | The course's website |
|Price | Cost of course |
| `Num_subscribers`|  Number of subscribers to the course |
| `Num_reviews` | NUmber of reviews for the course |
| `Num_lectures` | Number of lectures |
| `Level` | Indicates the course level, ranging from beginner level, intermediate level, expert level, to all levels.|
| `Rating` | Values of the rating range from 0 to 1 on course |
| `Content duration` | Duration of course in hours |
| `Published_timestamp` | Timestamp of the date course was published on website |
| `Subject` | The subject category under which the course falls. There are four subject categoories: web development, corporate finance, graphic design, and musical instruments.|

Three additional columns were added before the analysis using certain formulas in google sheets, and they were created from the price and published timestamp columns using vlookup, if statement, and left function. The new columns are 

 Before the analysis, three additinal columns were included, they were extracted from the price and published timestamp columns using some formulas(vlookup, if formula, and left formula). These new columns are:
 
| Column title | Description |
|---------------| ------------------ |
|`year`| This column only contains the year the courses were published|
|`Date`| This column shows the full date the courses were published (month, day, year|
|`Free or Paid`| This is an indicator for free or paid courses |



![alt text](https://github.com/distinctkemi/Udemy-course-analysis-with-tableau/blob/main/Udemy%20Courses.png)
