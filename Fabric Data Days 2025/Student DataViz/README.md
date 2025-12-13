# Student Data Vizualisation challenge 

Using the data provided by Microsoft during Fabric Data Days 2025 I have completed their Student DataViz challenge for personal practice. 

### Concept : College Quest in Fabricland

Data has been collected about all availabile colleges and courses, the idea is to make this data easy to interpret for prospective students. 

#### Dataset 

The dataset is completely fictional, and includes: 

College_Profiles: 
- Name, kingdom, tuition, ranking, admission difficulty
- Student life info (housing, clubs, happiness)
- Career outcomes (placement rate, salary, alumni satisfaction)

Programs_Majors:
- Program name, category, and level (undergraduate/graduate)
- Enrollment, graduation rate, internship availability
- Average starting salary per major

### My Approach 

My approach to this was to eliminate any options that are not viable for whatever reason, so you can focus your attention on just the colleges/courses/career paths that are relevant to you. 

With a decision like this people will often have some initial requirements/must-haves such as: 
- Location
- Field of Study 
- Course Level 
- Colleges with Scholarships / within a certain budget 

#### Tools used 

- Visualisation was completed using Power BI 
- Visuals used are all built in 

Features used in Power BI: 
- slicers 
- bookmarks (info page)
- drill through pages 
- DAX measures

To acheive my approach I have primarily used slicers and drill through pages. The inial page contains multiple slicers to filter those initial must-haves. The results of this are shown in the tables displayed below. From there you can drill through for further information: <br>

Collegege details --> Further college info <br>
Available Courses --> Course info OR Career info 

In case this is not immediately obvious, an info button has been added pointing out how the report can be navigated (created using bookmarks).

Filters can also all be reset with the reset button. 

In this instance DAX measures were primarily used to incorporate icons into the visuals. 

### Challenges and Lessons Learned 

This was a clean dataset so enjoyable to dive straight into visualisation. 

One challenge was that the College Details table did not filter in relation to the field of study or course level slicers, which was resolved by updating the direction of the one to may relationship to both ways. 

In general it was a good learning experience to try implementing drill through pages, buttons, and bookmarks (for the info page), which was a first for me. 

Overall I am happy with the reports performance. One are for potential improvement would be to incorporate a more comparative element to it, so the user can see in a clear way how one course/college compares to another. This would be particularly useful if they narrow their options down to a shortlist and need to make that final decision.  


### Resources 
Details and dataset provided by Microsoft can be found here: 
https://community.fabric.microsoft.com/t5/Power-BI-Community-Blog/Student-Dataviz-Contest-Fabric-Data-Days/ba-p/4863848 