# Github-Access-and-Social-Graph
Chloe Conneely 17323080

![Graph 1 Year](https://github.com/TheCsWorld/Github-Access/blob/master/Graph%201%20year.png)

This graph displays the contributors to a the PyGithub repo over the period 1st November 2018 to 26th November 2019.</br>
The purpose of theis graph is to determine the contributors who commits most frequently to a repo as shown over a period of time.

## Description
Initially, I tried to use the linux repo but with over 20,000 contributors and over 800,000 commits, it was not ideal with regard to time. Instead I used the PyGithub repo which has 190 contributors and 1,725 commits.</br>
I obtained information on the number of commits contributors to the repo made over the past year. I created a dataframe with all the contributors who contributed to thr repo over the past year, the dates of the commits and a count that increases by one for each commit per author. My graph uses the date of commit as the x-axis and the commit count for the y-axis. The graph allows the viewer to select individual contributors and view the data over a 1 month, 3 month, 6 month or one year timeframe. I wanted to gather data for second repo such as Node.js and compare the number of contributors with commits over the same time period but I was not able to achieve this in time for the deadline. This repo contains the code to gather and graph the data, along with sceenshots of the graph over 1 month, 3 months, 6 months and 1 year with a video showing the functionality of the graph (i.e. isolating an individual contributor, highlighting commits and showing the data in one of the given timeframes). 

## Software Used
Python (Programming Language)</br>
PyCharm (IDE for Python)</br>
pip (Package Installer)</br>
Jupyter Notebook (Python Editor)(Note: not required to install)</br>
Pandas (Library)</br>
NumPy (Library)</br>
Plotly (Library)</br>
Psutil (Library)</br>
GitHub (GitHub access token, GitHub API, Data for the graph)</br>

##Installation and Setup
1. Install Python, Pycharm and pip.</br>
2. Clone the file githubAccess.</br>
3. Open githubAccess in Pycharm.,/br>
4. Install the libraries listed above using pip.</br>
  a) Open the command line and type in "pip install <name of library>".</br>
5. Run githubAccess in order to gather the data and generate the graph.</br>
  
##Commits
[Initial commit for GitHub Access](https://github.com/TheCsWorld/Github-Access/commit/a1e3224b51cf9e9006a83d3aaa4250134600e671)</br>
[Final code commit](https://github.com/TheCsWorld/Github-Access/commit/493a6ad9f503c310fc642c89d7f7c92ff3fcca9f)

