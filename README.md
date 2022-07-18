# School_District_Analysis
School District Analysis using Jupyter Notebook, Pandas, Python, Visual Studio & Anaconda

## Overview of Project
Here is the list of deliverables for the analysis of the school district: 

* A high-level snapshot of the district's key metrics, presented in a table format
* An overview of the key metrics for each school, presented in a table format
* Tables presenting each of the following metrics:
    * Top 5 and bottom 5 performing schools, based on the overall passing rate
    * The average math score received by students in each grade level at each school
    * The average reading score received by students in each grade level at each school
    * School performance based on the budget per student
    * School performance based on the school size 
    * School performance based on the type of school

## Resources

* Data Source: `PyCitySchools.ipynb` file and rename it `PyCitySchools_Challenge.ipynb`. Additional resources 'schools_complete.csv' & 'student_complete.csv'
* Software: Software: Jupyter Notebook 6.1, Pandas, Python 3.9, Visual Studio Code 1.69.0, Anaconda 4.13

## Background Analysis and Challenges
The school board has notified Maria and her supervisor that the `students_complete.csv` file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

#### Determine Data Types Challenge Data Background
> You have been tasked with getting key metrics from the datasets. This will involve performing calculations to get sums, averages, and percentages.

## Deliverable 1: Replace Ninth-Grade Reading and Math Scores
**Instructions**: Using the Pandas `loc` method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.

### Deliverable 1 Requirements:

You will earn a perfect score for Deliverable 1 by completing all requirements below:

* The `loc` method is used to select all the reading and math scores from the ninth grade at Thomas High School. Inside the `loc` method, the following are completed:

    * A comparison operator is used to retrieve all the rows with Thomas High School in the **"school_name"** column of the `student_data_df`.
    * A comparison operator is used to retrieve all the rows with the ninth grade in the **"grade"** column of the `student_data_df`.
    * Logical and comparison operators are used to retrieve all the rows with the **"reading_score"** column for Thomas High School ninth graders from the `student_data_df`.
    * Logical and comparison operators are used to retrieve all the rows with the **"math_score"** column for Thomas High School ninth graders from the `student_data_df`.
    * The reading and math scores for the ninth graders in **Thomas High school** are replaced with **NaNs**.

    **1. A comparison operator is used to retrieve all the rows with Thomas High School in the **"school_name"** column of the `student_data_df`.**

    **2. A comparison operator is used to retrieve all the rows with the ninth grade in the **"grade"** column of the `student_data_df`.**

    **3. Logical and comparison operators are used to retrieve all the rows with the **"reading_score"** column for Thomas High School ninth graders from the `student_data_df`.**

    **5. The reading and math scores for the ninth graders in **Thomas High school** are replaced with **NaNs**.**

> Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%231%20-%20School%20name%2C%20grade%2C%20reading%20score.jpg 

**4. Logical and comparison operators are used to retrieve all the rows with the **"math_score"** column for Thomas High School ninth graders from the `student_data_df`.**

**5. The reading and math scores for the ninth graders in **Thomas High school** are replaced with **NaNs**.**

> Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%231%20-%20School%20name%2C%20grade%2C%20math%20score.jpg

**Final Code - Deliverable 1**

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%231%20-Final%20Code.jpg



## Deliverable 2: Repeat the School District Analysis
**Instructions**: Repeat the school district analysis you did in this module, and recreate the following metrics:

* The district summary 
* The school summary
* The top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student, by school size, and by school type

### Deliverable 2 Requirements:

You will earn a perfect score for Deliverable 2 by repeating the school district analysis and updating the following required metrics in the `PyCitySchools_Challenge.ipynb` file:

* The district summary DataFrame.
* The school summary DataFrame.
* The top 5 performing schools, based on the overall passing rate.
* The bottom 5 performing schools, based on the overall passing rate.
* The average math score for each grade level from each school.
* The average reading score for each grade level from each school.
* The scores by school spending per student.
* The scores by school size.
* The scores by school type.
 
### Deliverable 2 Results with detail analysis:

**1. The district summary DataFrame.**

Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%232%20-%20District%20Summary%20DataFrame.jpg

**2. The school summary DataFrame.**

Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%232%20-%20School%20Summary%20DataFrame.jpg

**3. The top 5 performing schools, based on the overall passing rate.**
**4. The bottom 5 performing schools, based on the overall passing rate.**

Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%232%20-%20Top%205%20%26%20Bottom%205.jpg

**5. The average math score for each grade level from each school.**
Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%232%20-%20Math%20Scores.jpg

**6. The average reading score for each grade level from each school.**

Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%232%20-%20Reading%20Scores.jpg

**7. The scores by school spending per student.**

Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%232%20-%20scores%20by%20school%20spending%20per%20student.jpg

**8. The scores by school size.**

Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%232%20-%20scores%20by%20school%20size.jpg

**8. The scores by school type.**

Image with code below.

**Code and Image**

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Deliverable%20%232%20-%20scores%20by%20school%20type.jpg


## Deliverable 3: A Written Report for the School District Analysis
**Instructions**: For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

The analysis should contain the following:

1. **Overview of the school district analysis:** Explain the purpose of this analysis.

2. **Results:** Using bulleted lists and images of DataFrames as support, address the following questions.

### How is the district summary affected?
> There were a minor neglible changes.  Please see image below of PyCityschools_ Challenge vs PyCitySchools

![name-of-you-image]https://github.com/ZZaman1989/School_District_Analysis/blob/main/Resources/Dev%20%233%20Distract%20Summary%20affected.jpg

### How is the school summary affected?
> Overall order changed due to removing 9th graders from Thomas High School.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
> Thomas High School ranking improved to second.

## How does replacing the ninth-grade scores affect the following:
- Analysis Below:

    * Math and reading scores by grade
        - Student count() Before THS Cleanup was: 1635
        - Student count() After THS Cleanup was: 1174

    * Scores by school spending
        - Thomas HS is in the spending bucket "$630-644"
        - Student count() Before THS Cleanup was: 1635
        - Student count() After THS Cleanup was: 1174

    * Scores by school size
        - Removing Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket.
        
    * Scores by school type
        - Thomas High School is in the "CHARTER" type
        
3. **Summary:**
The Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks changes, changes that are reflected in the funding for each student. 