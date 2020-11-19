## Imdb Data Analytics in GCP

This is the final project for the Data Engineering class (IDS 706) at Duke University. 

#### Data Studio Dashboard
https://datastudio.google.com/reporting/f7da9819-19cd-4591-a877-37fea407017b/page/6zXD

#### Video Presentation
https://youtu.be/KV1s33TZv4c

Preliminary data cleaning cource code can be found in the repository. 

#### Project Flow
* Data Cleaning in Python
* Data Storing in GCP buckets
* Data Preparation in Google Big Query
* Data Visualization & Analytics in Data Studio

#### Source Data
https://www.imdb.com/interfaces/

IMDb Dataset Details:
Each dataset is contained in a gzipped, tab-separated-values (TSV) formatted file in the UTF-8 character set. The first line in each file contains headers that describe what is in each column. A ‘\N’ is used to denote that a particular field is missing or null for that title/name. 

The data IMDB dataset consists of information regarding different types of videos clips, including TV Series, Mini Series, movies, etcs. We only focus on the movie data for this project.  

#### Project Focus
Below is a summary of the areas of interest of the project: 

* Number of moviews produced each year and the trend of volume
* Top genres in the recent years (our project picks a range from 2012 to 2019)
* Most active movie crew (in terms of the number of films they participated)
* Most active actors
* Films with highest ratings
* Characters played by award-winning actors/actresses
* Most versatile film crew of all time
* Time-series analysis using real-time data from Wikipedia film pages (our project picks 2019 and 2020 data)

#### Project Member
Jennie Sun:[@jenniesun](https://github.com/jenniesun)

Dean Huang:[@DeanHuang-Git](https://github.com/DeanHuang-Git)
