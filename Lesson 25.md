---
title: Lesson 25 - Intro to COMPAS Activity
layout: home
nav-order: 26
---

# Intro to COMPAS Activity

### Objectives:
- Students will explain how categories of race were socially constructed as a method of controlling slaves and perpetuating the institution of slavery. 
- Students will begin to trace the evolution of racial hierarchy after emancipation. 

### Resources:
- Slides
- Discussion Video
- Script
- Student Version Deepnote
- Answer Key Deepnote
- Algorithms Rule Us All

### Activity Steps

- Explain to the students that they will work as data scientists for Northpointe. Northpointe developed COMPAS (Correctional Offender Management Profiling for Alternative Sanctions), an algorithm designed to assess the risk of a criminal defendant reoffending. This tool is used by judges to help make decisions about bail, sentencing, and parole. 
- Also, explain ProPublica. ProPublica, an investigative journalism organization, conducted an in-depth analysis of the COMPAS algorithm. Their findings raised significant concerns about the algorithm's fairness and accuracy.
- COMPAS Questionnaire[1 hour]
    - Inform students that they will be tasked with deciding which data should be used to train COMPAS.
    - Explain the background of COMPAS.
    -  Task 1 (20 minutes):Pause the video at the 3:07 mark.  Determine with your group the questions that should be used to decide whether someone needs to stay in jail by reviewing all 137 questions from the COMPAS Risk Assessment Questionnaire. Determine which questions should be given more weight in COMPAS because they are more indicative of someone committing a crime again. Here is the link to the COMPAS Risk Assessment Questions, which has the questions that each person had to fill out before the COMPAS model made a prediction about their likelihood of committing another crime.
    - Task 2 (20 minutes): Each group shares the questions their group believes should be inputted into the COMPAS algorithm and the reason why they chose those answers.
        -  Next, share the questions that contain information about a prior arrest, and therefore should not be used as input data for the COMPAS algorithm because there are racial disparities in arrests in the US [1]. These questions should not be the input data because they contain information about someone’s prior arrests: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11-19, 20-22, 23, 25, 26, 27, 28, 29, 30, 43, 44, 45, 46, 47, 48, 49, 50, 53, 54, 66, 133, 137
        -  Afterwards, the teacher will discuss how the company that made COMPAS, Northpointe, did not release which questions were used in COMPAS and which questions were given more weight in COMPAS. Inform students how this can be problematic, because it is a black box algorithm.

At the 3:53 mark in the video, have students answer this question: Should people be punished based in part on their estimated likelihood of committing future crimes? 
Watch from the 10:25- 19:30 mark of the discussion video titled, “Algorithms Rule Us All”. Then complete the 3,2,1 framework and have a discussion

- Responsible AI Lifecycle [45 minutes]
    - Discuss how AI is not less biased than humans because data reflects human bias and we have missing data [2].
    - Review the Responsible AI Lifecycle, which is a series of questions that data scientists should ask themselves while they are making algorithms.
    - Introduce the “Intersectional data analysis of COMPAS” activity. During this activity, students will use Python and Pandas(a data analysis library) to analyze COMPAS. Additionally, students will learn about three different fairness metrics: accuracy, demographic parity, and false negative/false positive parity. We will use an interactive data science notebook called “Deepnote”, so students can quickly run each line of code. Their task is to determine the fairness metric that should be used to determine whether COMPAS is fair. Moreover, they will regenerate similar results that investigative journalists from Propublica discovered about COMPAS. For example, Propublica found that “Black people are almost twice as likely as White people to be labeled a higher risk but not actually re-offend ... It makes the opposite mistake among White people: They are much more likely than Black people to be labeled lower risk but go on to commit other crimes” (Propublica). The “Intersectional data analysis of COMPAS” activity will take about 2 hours.
    - Here is the blank assignment link that should be given to students.
    - Here is the answer key link
- Reflection [5 minutes]

At the 8:37 mark in the video, have students answer this question: What should we do to create ethical AI practices? 
- Share your experience doing the activity:
    - What did you learn?
    - What was challenging?
