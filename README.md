![A_B_Test-_Austin_Noriega (1)](https://github.com/user-attachments/assets/8a8d29b1-3265-4ed1-85b6-005025edb747)

# Overview
This project focuses on a critical aspect of the marketing analytics of A/B testing. A large company conducted a survey of people shown different types of advertisements, either advertisements(experiment group) or public service announcements(control group) and if they converted to using their brand. The research done answers the questions: 
* What is the best channel to reach out and convert consumers?
* Is the current marketing strategy profitable?

## Data overview: 
The data provided to conduct the analysis contains valuable participant information, such as: 
* **ID:** Unique identification
* **Test Group:** If they were apart of the test (advertisement) or control (psa) group
* **Converted:** The status of the participant conversion (did the advertisement work?)
* **Total ads:** The total amount of advertisemnts shown
* **Most ads (day):** The day with the most ads seen by the partcipant
* **Most ads (hour):** The hour with the most ads reported by the participant
  
## Methodology: 
In order to do the needed analytics, the following modules and statistical tests were used: 
#### Modules: 
- Pandas & Numpy
- Matplotlib & Seaborn
- Scipy.stats & Statsmodels.forlmula.api
- Scikit-posthocs & Statsmodels.stats.multicomp
  
#### Analysis Done:
- T-Test
- Cohen's D
- ANOVA
- Scheffe
- Tukey HSD
- Chi² 
## Summary of results: 
After conducting the tests, the results found that: 
- While advertisements are __statistically better__, it was an only by a minimal amount and does not hold as much practical significance
- The conversion rate for the advertisements is **2.55%**, which seems to be average compaired to specific industries' advertisement conversion rate
- On average, advertisements are shown on Friday and the start of the week 

## Further Considerations ##
Some of the main options for further research and consideration are:
- Additional reseach can be conducted to find out how the amount of ads shown to people affect their willingness to buy
- Further reseacher can also be applied to looking into ways to better resonate with people to achieve a higher conversion rate
