
# Project Motivation
I love sports and am interested in learning new and interesting things in the sports world. 
This project analyzes SportsStats data to find trends and patterns by group or sport or by country. 
Maybe also things that many people are curious to know.
2 target audience groups I target:
Local news sites who can then aggregate and provide new perspectives and analysis for readers.
Professional coaches who can consult and develop training programs for their athletes.

# Question and Hypothesis
1. Top 5 country got the most medals.
2. Top 10 sports that bring the most medals.
3. Ratio of male and female athletes participating in the olympics over the years
4. Average age of those 5 sports based on medalists
5. Youngest/oldest athlete ever to win an Olympic medal.
6. Top 10 athletes with the most medals in history and medal distribution.
7. What are the strengths of each of the above sport according to the top 10 countries with the most medals?

Hypothesis
1. The age group from 18 to 25 has almost the same number of medals as the total number of medals of all other age groups
2. Body Mass Index Affects Athletes' Performance

# BLOG website for this project
http://for-learning-udacity-phutv.s3-website-ap-northeast-1.amazonaws.com/

# File Description
analysis.ipynb -- 
for_blog.ipynb -- Jupyter notebook file which clear all code to prepare extract to html format file
for_blog.html -- file for blog which will be hosted on amazon S3 at
http://for-learning-udacity-phutv.s3-website-ap-northeast-1.amazonaws.com/

data/athlete_events.csv -- data contain athelte informations and their records
data/noc_regions.csv -- data cotain Olympic host site/city infomation
image/* -- image use for blog

# Datasource
[dataset url](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
# Acknowledgements
- Dataset credit
[rgriffin on Kaggle - 120 years of Olympic history: athletes and results](https://www.kaggle.com/heesoo37)


# Run this repo
## create virtual environment and active it
https://docs.python.org/3/library/venv.html
## install library
pip install -R requirements.txt 
