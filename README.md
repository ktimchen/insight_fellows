## Installation

- Python 3.7.2
- Libraries: 
  - [requests](https://realpython.com/python-requests/)
  - [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
  - [NumPy](http://www.numpy.org/)
  - [Pandas](http://pandas.pydata.org)
  - [matplotlib](http://matplotlib.org/)
  - [seaborn](https://seaborn.pydata.org)
  - [wordcloud](https://github.com/amueller/word_cloud)
  - [json](https://docs.python.org/3/library/json.html)

## Project Motivation

The INSIGHT Data Science Fellows Program is a competitive fellowship targeted at academics from the top universities. It helps recent PhDs and Postdocs to find a prestigious job as data scientists in the industry. I applied for the fellowship twice, made it to interviews, but unfortunately was rejected. So I was really curious about who these top quants are. 


## File Descriptions

You can find the source [code](https://github.com/k-bosko/insight_fellows/blob/master/INSIGHT_Data_Science_Fellowship.ipynb) or read the blog post on my website: [https://www.cross-validated.com/Insight-Data-Science-Fellows/](https://www.cross-validated.com/Insight-Data-Science-Fellows/)


## Results

I will shortly describe the project following the CRISP-DM process:

#### Business Understanding
  1. How many fellows participated in the INSIGHT DS program?
  2. What universities did they attend?
  3. What background do they have?
  4. Where did they find jobs and what job titles did they get?
  5. Does LinkedIn prefer hiring Postdocs?
  
#### Data Understanding
  The questions of interest described in the first step were derived from the data I collected. 
  
#### Prepare Data
  I scraped INSIGHT Data Science Fellows and cleaned the data.
  
#### Data Modeling
  I used descriptive and inferential statistics to answer my questions of interest.
  
#### Evaluate the Results
794 INSIGHT DS Fellows come from 198 different universities. Although half of the fellows studied in just 20 universities. Almost 30% of fellows (219) are from Californian universities, with two the most popular being Stanford (79 fellows) and UC Berkeley (53). <br>
The majority of INSIGHT fellows (64%) are freshly completed PhDs. There are about 29% Postdocs and about 7% practitioners (uni faculty, managers, researchers, etc). Almost every third fellow studied Physics/Astrophysics (32%). The next biggest group - 10% - are neuroscientists. <br>
794 INSIGHT fellows started working in 383 different companies, 72% of which hired just 1 fellow. The TOP 5 companies that hired the fellows most actively were Facebook (54 fellows), LinkedIn (22), Stitch Fix (19), Netflix (15) and Intuit (14).
Two thirds of all fellows (587) have "Data Scientist" as part of their job title. About 15% of fellows managed to get more senior positions with titles such as "Senior", "Head", "Lead" and even "Director".
As found in the hypothesis testing, LinkedIn stands out from other companies in that it on average hire more postdocs than the rest.
  
## Acknowledgements

[The INSIGHT Data Science Fellows Program](https://www.insightdatascience.com)
