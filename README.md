**Project Description**: Assuming I am a data analyst at Udemy, I have been given a task by my manager to present the data on course revenue, and I have been provided with data on courses from different topics to understand where opportunities to increase revenue may lie, and track the performance of courses. Another task is to geth the details of the top 20 most subscribed courses.
My manager has suggested encouraging Web Development courses to charge more because she believes that these are the most popular courses.

This [repository](https://github.com/distinctkemi/Udemy-course-analysis-with-tableau) contains both the dataset used for the study and a comprehensive report on the analysis' results.

**About the dataset:** There were four datasets for different subjects (web development, business finance, graphic design and musical instruments) and they were merged to make a single file, after merging the dataset consist if 3,677 rows and 12 columns. The columns in this dataset include:

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

**Summary of findings**
- Web development is the subject with the most subscribers out of the four with almost 70% of the whole data, and it has tripled or more the subscribers of the other three. This is the first data-driven insight identified.
- Despite having the most expensive average cost, of its intermediate level courses, the web development field nonetheless has the most subscribers for its intermediate level courses
- Web development continues to have the biggest number of subscribers on even paid courses when compared to others, with a significant disparity, web development has over 5 million subscribers of the paid courses and only approximately of 2.4 million of free courses.
- An intriguing finding from this data is that, in terms of average ratings, graphic design is rated highest, while web development, which is the main focus, is rated second-to-last in the pyramid.
- Web development courses have experienced the highest number of subscribers compared to other subjects since 2011, growing year over year, but experiencing a fall between 2015 to 2017. It is important to recognise and comprehend the reasons for this recent decline in subscribers.
- Since 2011, the total amount of income created annually has generally increased across all subjects, with Web development producing the most income, but in 2017, the income from each subject decreased.
- Based on the analysis, the number of subscribers for all subjects decreased drastically after beginner level to intermediate level.

I created an interactive dashboard of the insights from this analaysis, click [here](https://public.tableau.com/app/profile/adekemi8173/viz/Udemycourseanalysis_16754714438190/Dashboard1?publish=yes) to view the dashboard.

You can also see the pivot tables and visualisation I generated from googlesheets [here](https://docs.google.com/spreadsheets/d/1Nh9Owk_KV8hQQc-jS8rwe7A7V9AkSDT_ovY0m9AqFGo/edit?usp=sharing)


![alt text](https://github.com/distinctkemi/Udemy-course-analysis-with-tableau/blob/main/Udemy%20Courses.png)
