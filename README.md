
# This project analyzes SportsStats data to find trends and patterns by group or sport or by country. 
2 target audience groups I target:
Local news sites who can then aggregate and provide new perspectives and analysis for readers.
Professional coaches who can consult and develop training programs for their athletes.

# Questions
- Average BMI of the 2 groups of athletes (with and without medals) by year.
- Top 5 sports that bring the most medals.
- Average age of those 5 sports based on medalists
- Average BMI per sport based on 2 groups of medalists and non-medalists
- What are the strengths of each of the above sport according to the top 10 countries with the most medals?
- Top 10 athletes with the most medals in history and medal distribution.
- Youngest/oldest athlete ever to win an Olympic medal.

# Hypothesis
1. The age group from 18 to 25 has almost the same number of medals as the total number of medals of all other age groups
2. Body Mass Index Affects Athletes' Performance

# Approach
## Hypothesis 1:
- Delete rows with null age data.
- Calculate the total number of medals of the age group 18 to 25 and the total number of medals of the remaining age groups. Compare the numbers and percentages between the two groups.

## Hypothesis 2:
- Calculate the BMI of all athletes, insert BMI field to dataframe.
- Compare the average BMI across the group of athletes with and without medals according to the content of the competition, find out the difference between the 2 groups and the pattern of success if any.

# Run this repo
## create virtual environment and active it
https://docs.python.org/3/library/venv.html
## install library
pip install -R requirements.txt 

# static website for this project
http://for-learning-udacity-phutv.s3-website-ap-northeast-1.amazonaws.com/