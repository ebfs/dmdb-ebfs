# 1_orientation / exercises_orientation.md
------------------------------------------

## Task 1

### 1. What are the names of the teachers who have taught the course "Databases"?
* * *

* Stevens, Steve
* Collins, Albert

### 2. What are the names of the students who have received a grade from the course "Databases"?
* * *

* Pass, Joe
* May, Brian
* Sheeran, Ed

### 3. What are the names of the courses Joe Pass has completed successfully?
* * *

* CS-3 Databases
* CS-2 Web Design

### 4. What are the names of the teachers who have taught Frank Zappa?
* * *

* King, Freddie
* Green, Peter

### 5. How many students have grades from courses given by Albert Collins?
* * *

* 1

### 6. What are the names of the students who have been taught by the teachers whose room number is 101?
* * *

* Zappa, Frank
* Pass, Joe
* Sheeran, Ed

### 7. What are the names of the teachers who haven't given any courses yet?
* * *

* Paisley, Brad

---------
## Task 2

### Part A
* * *

Data.

### Part B
* * *

Elvis.

### Part C
* * *

Frank.

### Part D
* * *

* Inconsistent, missing candidate.

* Block merge/overwrite if linting/data quality checks for data entry fail, such as comparison to historical data (age shouldnt be less than before.)

---------
## Task 3

| Table                 | Primary key | Foreign keys |
| --------------------- | ----------- | ------------ |
| Course                | Course ID   |              |
| Teacher               | Teacher ID  |              |
| Student               | Student ID  |              |
| Course grade          | Course ID+CourseIplementation number + Student ID | Course ID & Student ID |
| Course implementation | Course ID0CourseImplementation number | Teacher ID |