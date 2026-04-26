---
# Do not edit the text between these lines!
layout: default
---

# Project Summary

## Project Goal

This project analyzes survey data comparing CS and Non-CS students in terms of perceived difficulty, pace, and understanding of COMP110. The primary goal of the analysis is to evaluate whether introducing a targeted support session for non-CS majors could improve their learning experience. This idea is motivated by the possibility that students without prior computer science background may experience greater difficulty, slower perceived pace, or lower understanding compared to CS majors.

The investigation focuses on comparing CS and Non-CS student responses across three key Likert-scale variables: difficulty, pace, and understanding. These variables are selected because they directly reflect students' learning experiences and engagement with the course content.

## Analysis Summary

To conduct the analysis, the two survey files are first combined. Then the dataset is cleaned to remove incomplete responses and grouped by major type (CS and Non-CS). Personal helper function is created to implement the cleaning steps. The sample size is also checked before visualization to verify completeness of data and sample size balance.

## Visualization

During the visualization step, Seaborn was used to generate graphs, including distribution plots and categorical plots, to identify patterns, differences, and variability between the two student groups.

### Distribution of CS and Non-CS students
A bar graph is used to visualize the distribution of CS major and Non-CS major students in the dataset. 

<img src="project-site/static/imgs/Sample_Size_Distribution.png"
alt="Image of CS and Non-CS students distribution." Width="500"/>

This bar chart indicates a substantial sample size imbalance between the two groups. The Non-CS group represents the vast majority of responses (713 students), while the CS group is much smaller (51 students). This imbalance is important to keep in mind when interpreting the remaining visualizations, as patterns in the Non-CS group will dominate the overall dataset.

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="project-site/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>