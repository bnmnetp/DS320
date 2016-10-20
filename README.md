# Data Analysis and Visualization

Course Materials for DS-320 at Luther College

## Schedule

### October 20

* In class presentations of mid-term project

**Assignment For Tuesday Oct. 25**

* Read - [College Acess Index](http://www.nytimes.com/2015/09/17/upshot/college-access-index-2015-the-details.html)
* Acquire data so that we can re-create this study but focusing on midwest colleges comparable to Luther


### October 11

* Exploring some CS enrollment data with the viz tools
* You should really look at [This overview](https://dansaber.wordpress.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/) before class!

**Reminder** Your first projects are due before you leave for Fall Break!  Presentations after break.

### October 6

* An overview of the landscape of viz tools in Python.  [I wish I had seen this two days ago](https://dansaber.wordpress.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/)
* discussion of the layered grammar of graphics and a bunch of examples of using it.

*
### October 4

* Presentations of election questions and answers
* Project work

**Assignment**

* For Thursday read Hadley Wickham's Layered Grammar of Graphics paper

### September 29

* Quick presentations of questions and solutions to the election data
* Project 1 discussion and work

### September 27

**Topics**

* Merging dataframes and Joining database tables
* dataframe pivots

**Assignment**

* For Thursday:  https://classroom.github.com/assignment-invitations/c16643bd30df00c3d682fb2e9ca399e3

### September 22

**Topics**

* Graphing and grouping
* Get the new assignment here: https://classroom.github.com/assignment-invitations/28946cbaf858a44b83817d64448793e1

**Assignment**

* For Tuesday complete Exercises-2 and Exercises-3

### September 20

**Topics**

* REST API's
* Pandas data frames and making the most of them
* [Pandas Official Docs](http://pandas.pydata.org/pandas-docs/stable/)
* clone this:  https://github.com/Kyrand/dataviz-with-python-and-js

** Assignment **

* I have a number of Pandas data frame manipulations for you here:  https://classroom.github.com/assignment-invitations/d6be09e3a01a2ae3cdc2a85d39446f44

### September 15

**Topic**

* Our challenge for today will be to take the box office movie data you got and adjust the price for inflation.  Then we'll re-sort the data.   BUT, we will not be using the spreadsheet and doing our own calculations to adjust the prices, we will use a web service.

* Transferring data across the web
* Serializing data (JSON/XML)
* What do we mean by an API?
* Work through example.

**Assignment**

* Continuing with the box office data we will agument it with further information from IMDB.  Using the http://www.omdbapi.com  API.  It will return data in JSON format and uses a simple query string to make the request.  The Home page does a nice job of documenting the API.  Start by making a new repo using this invitation.  https://classroom.github.com/assignment-invitations/30377fceb9efd4942454402d864d423f

### September 13

**Readings**

* The red book has two good chapters to help with the current project
  * Chapter 1 - Development Setup has some good advice on installing Anaconda
  * Pages 140 to 150 have some great information on reading and writing csv files.
  * Chapter 5 - Getting data off the web talks about requests and BeautifulSoup

**Topic**

* You should have your program to scrape the data from the gasoline web site working, and you should have an excel spreadsheet of CPI data.
* We will restart the process of converting the raw data to a DataFrame and then we will adjust the gas prices for inflation.
* In class we will also work through the rest of the gas price exercise

**Assignment**

* Experimental Hand in method:  https://classroom.github.com/assignment-invitations/3b13f4b6b9f48cdf30630abd005f626f  I have not tried this in class yet, so we will see how well this works for you to turn in your Notebook you created for this exercise.

* For Thursday, Another scraping exercise.  -- Scrape the the box office proceeds for the top grossing movies of all time from http://www.the-numbers.com/movie/records/All-Time-Domestic-Box-Office   Convert these into a Pandas Data Frame and save them as a CSV file.   You will hand in your notebook.  Maybe on github maybe on katie depending on how the experiment goes. Since the experiment was largely a success, turn in your scraping exercise here:  https://classroom.github.com/assignment-invitations/41a43599b6a6051041d8eef98264beb1


### September 8

**Topic**

Our task for today is to Create one or more visualizations to help us put into perspective the change in
gasoline prices over the years.  We will want to follow Tufte's rule for looking at prices by computing our own
adjustment for inflation.  To do this we will begin to dive into some tools for obtaining data such as the requests module and BeautifulSoup.

* requests - for downloading web pages
* BeautifulSoup for parsing and querying web pages
* Lets look at http://www.eia.gov/totalenergy/data/annual/showtext.cfm?t=ptb0524  as an example to get some practice.
* We may have many different data sets since I asked you to look.  One of our tasks will be to compare.
* Here are [some instructions](http://www.maa.org/press/periodicals/loci/joma/the-consumer-price-index-and-inflation-get-cpi-data-from-the-web-and-into-a-spreadsheet) for getting consumer price index information.

** Assignment **

* For Tuesday complete the exercise of scraping the web page for the data.  Also make sure you have downloaded the spreadsheet of CPI data.


### September 6

**Topics**

* Looking at some examples to illustrate Tufte's Principles
* Getting to knuth.luther.edu
  * ssh from your computer anywhere
  * the jupyterhub - web application on knuth

* Command Line Review
  * cd
  * ls
  * cp
  * rm
  * mkdir
  * mv
  * less
  * grep
  * nano/emacs/vi
  * tar and zip
  * chmod
  * pwd
  * man

* Cloning the git repo for this class
* Install [Anaconda](https://www.continuum.io/downloads) on your own machine.
* Working with data in Jupyter Notebooks
  * DataFrames
  * Series

**Homework for Thursday Sept 8**

* Read Chapter 3 of Tufte
* Find one or more data sources (you may need to combine them) that will give us data about the price of gasoline in the USA dating back as far as you can.   At least the 1970's


### September 1 - Welcome

**Topics**

* What is Data Science?
* Course Administrivia
* Flood Water Exercise
* Being a "data skeptic"

**Homework for Tuesday Sept 6**

* Read Chapters 1 and 2 of Tufte
* Bring 2 examples of graphics 2 class one good and one bad be prepared to explain what makes them good or bad.


## Repositories of data sets
