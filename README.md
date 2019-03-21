## Table of Contents
1. [Installation](#installation)
2. [Introducing a Dataset](#dataset-introduction)
3. [Project Motivation](#project-motivation)
4. [File Descriptions](#files)

### Installation <a name="installation"></a>
For running this project, the most important library is Python version of Anaconda Distribution. It installs all necessary packages for engines and building plots. 
 
### Introducing a Dataset <a name="dataset-introduction"></a>
Data for recommendation engines for articles in IBM is provided by IBM and data contains about articles, user-article interactions.

### Project Motivation <a name="project-motivation"></a>
For this project I will be looking at the interactions that users have with articles on the IBM Watson Studio platform using different recommendation systems

Various kinds of recommendation systems include - 
1. Rank or knowledge based recommendations - When we don't know about user's journey then the most popular events are used as a recommendation for everyone.
2. Collaborative filter based recommendations - A method of making recommendations based on using the collaboration of user-item interactions.
3. Content based recommendations - When we use information about the users or items to assist in our recommendations.

### File Descriptions <a name="files"></a>
There is a notebook available here to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above qustions
1. articles_community.csv - contains all artilces with their info.
2. user-item-interactions.csv - it anchors all user-article interactions.