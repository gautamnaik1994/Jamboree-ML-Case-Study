# Jamboree Case Study

Gautam Naik (gautamnaik1994@gmail.com)

**Business Problem**

Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.  
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

Your analysis will help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

We will use Exploratory Data Analysis to find important factors and also Linear Regression to predict the chance to get admission and to rank the important factors by importance.

**Metric**

We will use R2 score, Root Mean Squared Error, Adjusted R2 score and plots to gauge the accuracy of the model.

**Dataset:**

*   Serial No. (Unique row ID)
*   GRE Scores (out of 340)
*   TOEFL Scores (out of 120)
*   University Rating (out of 5)
*   Statement of Purpose and Letter of Recommendation Strength (out of 5)
*   Undergraduate GPA (out of 10)
*   Research Experience (either 0 or 1)
*   Chance of Admit (ranging from 0 to 1)

**Recomendations and Insights**

- For Jamboree
  - The Lasso model with polynomial features seems to be best among all models with Adjusted R2 score around 0.82
  - University ratings and Strenght of Letter of recomendation have no impact on the chance of admission
- For Students
  - From above analysis it is clear that smart student, ie students with high CGPA has a higher chance of admission.
  - Students must be advised to increase their CGPA score, GRE scrore and TOEFL score as these factors increase the admission chance.



