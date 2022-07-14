# School_District_Analysis


## Overview 

### Purpose

The purpose of this analysis is to look at the two data sets Maria provided for the High schools in her school district and analyze key metrics Maria and her team are looking for. The data is focused on math and reading scores but it seems that after conducting our first analysis it was found that Thomas High School may have cheated and Maria wants to know how removing Thomas High’s 9th grade class affects the overall scores for the district. We will be analyzing both Data Frames we put together to get a comparison.

## Results

### o	How is the district summary affected?

After turing the removing the 9th graders from Thomas High School into null data there was not much of a change in the average or passing grades for math or reading as shown below. This means that not enough students's scores were dropped from the data to make a difference in the entire district.

Original

<img width="918" alt="original district summary" src="https://user-images.githubusercontent.com/107590196/178883253-baca3f56-9ed9-4aea-8ccf-f46c9d8c1e61.png">

New 

<img width="911" alt="new district summary" src="https://user-images.githubusercontent.com/107590196/178883238-e1dde287-221e-4311-b627-516232ec0943.png">

### o	How is the school summary affected?

The summary for the Thomas High School did take a hit the passing percentages. The averages remained pretty steady since since we changed how many students we were counting in the equation. When we look at the passing grades, it is pretty obvious that removing the 9th grade students framatically brought the passing score percent from the 90's to the 60's bringing the overall passing score from 90.1 to 65. This helps the school board confirm that the 9th grade class skewed the scores for these subject at Thomas High.

Original

<img width="992" alt="original school summary" src="https://user-images.githubusercontent.com/107590196/178885931-ea180b86-8181-437e-9e0a-f7d716eac100.png">

New

<img width="989" alt="new school summary" src="https://user-images.githubusercontent.com/107590196/178885568-377b95b3-fbc2-4c5e-bd12-eabdc406c656.png">

### o	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the 9th graders' scores took THomas Highschool from being the 2nd leading school in the district to 8th school in the district.

New

<img width="988" alt="Top Schools original" src="https://user-images.githubusercontent.com/107590196/178886234-d375cda9-2bed-4794-bccb-717ac4df235b.png">

Original

<img width="1002" alt="All Schools new" src="https://user-images.githubusercontent.com/107590196/178886250-707dfdf4-9bee-41ba-9c4d-8abe50bab078.png">

### o	How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade

In the Original data set the 9th grade math score was 83.59 and the reading score was 83.7. After making the scores for these subjects null, the scored for 9th grade show up as nan. Every grade at every school has grades except for this class.

New Math Scores

![Adjusted Math Scores](https://user-images.githubusercontent.com/107590196/178891228-450d46b0-5ea5-4c41-aa07-cd8f9c085997.png)

New Reading Scores

<img width="302" alt="Adjusted reading Scores" src="https://user-images.githubusercontent.com/107590196/178887209-1c2bb5bd-1efc-4ee6-9907-0d66238d1d52.png">

### Scores by school spending

The scores by sepnding was not changed much since it was taking in account close to 40,000 studuents. The only rnge that took a hit was the $630-644 rnge ebcause this included Thomas High. 

<img width="810" alt="Scores by spending -original" src="https://user-images.githubusercontent.com/107590196/178887931-1a2e6dba-9125-4cfb-bf0e-e439c898c649.png">


<img width="818" alt="Scores by spending - new" src="https://user-images.githubusercontent.com/107590196/178887572-14e21b22-3d1b-4582-a725-d550ac508db1.png">


### Scores by school size

The Score by school type was not affected by much either. The only size that took a hit was the medium schools like Thomas High.

<img width="741" alt="scores by size - original" src="https://user-images.githubusercontent.com/107590196/178888594-9c7cc183-eeae-4872-b6cc-2a9b794f83db.png">

<img width="744" alt="scores by size - new" src="https://user-images.githubusercontent.com/107590196/178888607-542102fc-26c8-4934-9a03-5667677c4413.png">

### Scores by school type

The charter school types decreaed scored by a fraction of a percent but still within the same percent when rounded to the whole number.

<img width="703" alt="scores by type - original" src="https://user-images.githubusercontent.com/107590196/178888390-239b1c46-fb96-4dbf-9c8b-5175ed0fa9bc.png">

<img width="708" alt="scores by type - new" src="https://user-images.githubusercontent.com/107590196/178888407-491fe018-49b2-4442-ac11-08a465c83124.png">


## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

After adjusting the analysis, I concluded that the below points:

1. The major change in the updated analysis is the Thomas High School passing grade going from 90% to 65%.
2. The avagerages for math and reading went down for Thomas high school from and A score to the 60's.
3. THomas High went from being ranked 2nd int he district to being ranked 15th.
4. The scores for the 9th grader at Thomas high went from 83 in math and reading to NAN.
