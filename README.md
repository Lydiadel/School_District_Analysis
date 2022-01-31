# School District Analysis

## Author
Lydia Delgado Uriarte

## Overview
Analyze data in a student funding & student's standardized tests. Aggregate data and showcase trends in school performance, regarding the school budget and priorities, protecting the privacy and data of the students.

## Output
### Per School Summary
#### Output before
<img width="984" alt="Per_School_Summary_df" src="https://user-images.githubusercontent.com/71950779/151650155-0bdf9ce8-8739-4761-9e47-cd748d7386f8.png">

#### Output after modifying ninth grader's scores
<img width="978" alt="Per_School_Summary_Modified" src="https://user-images.githubusercontent.com/71950779/151650477-762ea436-78f0-4c09-98ca-af8475bbc3ec.png">

### District Summary
#### Output
<img width="705" alt="Type_Summary_df" src="https://user-images.githubusercontent.com/71950779/151650203-8ec82ec7-a16c-4485-a3eb-07df55b4706a.png">

#### Output after modifying ninth grader's scores
<img width="711" alt="Type_Summary_Modified" src="https://user-images.githubusercontent.com/71950779/151650188-185ca129-905d-43b2-8338-71733aeacc82.png">

### Spending Ranges
#### Output
<img width="814" alt="Spending_Ranges_df" src="https://user-images.githubusercontent.com/71950779/151650210-d25a2208-4c51-410b-8f6b-1ce04f3c6925.png">

#### Output after modifying ninth grader's scores
<img width="814" alt="Spending_Ranges_Modified" src="https://user-images.githubusercontent.com/71950779/151650222-fb52b752-fea5-4d4d-be2b-032b34681b75.png">

### School Size
#### Output
<img width="751" alt="Size_Summary_df" src="https://user-images.githubusercontent.com/71950779/151650260-71632be8-f71d-4ff0-ae1c-53824410010a.png">

#### Output after modifying ninth grader's scores
<img width="776" alt="Size_Summary_Modified_df" src="https://user-images.githubusercontent.com/71950779/151650266-9851c17c-5919-4109-99eb-893ba5f25cc1.png">

### School Type
#### Output
<img width="705" alt="Type_Summary_df" src="https://user-images.githubusercontent.com/71950779/151650372-34a73ce8-ef7d-4872-98c7-b36f5f8eb46a.png">

#### Output after modifying ninth grader's scores
<img width="711" alt="Type_Summary_Modified" src="https://user-images.githubusercontent.com/71950779/151650374-0a144f8d-8441-4cb1-80b9-99913ba8995f.png">

## Results
- How is the district summary affected?
  - It is not affected at all, the calculations doesn't change from the previous one.   
  
- How is the school summary affected?
  - The school summary is affected in the passing percentage, passing math reduce a 27% and passing reading a 27% which affect as well the overall pasing also 27%. 
  - This information allow make a deduction were that 27% of the failling ones were the 9th graders students.
  
- How does replacing the ninth grader’s math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Replacing this scores affect Thomas High School specially, making other school be better than this school. 
  
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade 
      - The math scores were not affected at all sincee the only ones changed were 9th graders scores.
      
    - Scores by school spending
      - The spending ranges between $630 - $644 there is a different outcome after changing 9th graders math scores reducing the passing percentage.
      
    - Scores by school size
      - The output given after changing 9th grader's score we can see how the medium school size which has between (1000 - 2000) students their scores were decreased in the percentage of passing math and reading.
      
    - Scores by school type
      - This scores were not affected at all, same as the district summary. 

## Summary
Major changes presented in the District Analysis
- Inserting Nan values in the dataframe does not affect any calculations done with the dataframe.
- We can see that in any outcome the passing reading percentage is higher than the passing math percentage.
- Dropping califications we can see that 9th graders students help Thomas High School improve performance, otherwise grades would be down.
- In Thomas High School 27% of the students are in 9th grade.
