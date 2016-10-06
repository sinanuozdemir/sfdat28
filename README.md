## SF DAT 28 Course Repository

Course materials for General Assembly's Data Science course in San Francisco, CA (10/4/16 - 12/13/16).

**Instructors:** [Sinan Ozdemir](https://www.linkedin.com/in/sinan-ozdemir-10568534) 

**Teaching Assistants:**
[George McIntire](https://www.linkedin.com/in/georgemcintire)
[Cari Levay](https://www.linkedin.com/in/carilevay)

**Course Times**

Tuesday/Thursday: 6:30pm - 9:30pm

**Office hours:** 

TBD

All courses / office hours will be held in the student center at GA, 225 Bush Street

**[Course Project Information](project.md)**

**[Course Project Examples](project-examples.md)**


Tuesday | Thursday | Project Milestone | HW
--- | --- | --- | ---
10/4: Introduction / Expectations / Intro to Data Science | 10/6: Pandas
10/11: 10/13: APIs / Web Scraping 101 | 10/15: Intro to Machine Learning / KNN | | HW 1 Assigned (W)
10/18: Model Evaluation / Linear Regression Part 1 | 10/20: Linear Regression Part 2 / Logistic Regression | Three Potential Project Ideas (W) | 
10/25: Natural Language Processing | 10/27: Naive Bayes Classification  ||HW 1 Due (W)
11/1: Advanced Sklearn (Pipeline and Feaure Unions) | 11/3: Review || 
11/8: Decision Trees  | 11/10: Ensembling Techniques | |HW 2 Assigned (W)
11/15: Dimension Reduction | 11/17: Clustering / Topic Modelling | First Draft Due (W) | 
11/22: Stochastic Gradient Descent | 11/23: No Class | Peer Review Due (M)
11/29: Neural Networks / Deep Learning | 12/1  Recommendation Engines ||HW 2 Due (W)
| 12/6: Web Development with Flask | 12/8: Projects |
12/13: Projects |  | |


### Installation and Setup
* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
* Setup a [conda virtual environment](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)
* Install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and create a [GitHub](https://github.com/) account.
* Once you receive an email invitation from [Slack](https://slack.com/), join our "SFDAT28 team" and add your photo!

### Resources
* [PEP 8 - Style Guide for Python](http://www.python.org/dev/peps/pep-0008)
* [Learn How to Think Like a Computer Scientist](http://interactivepython.org/runestone/static/thinkcspy/toc.html#t-o-c)
* Potential book for course? [:)](https://www.amazon.com/Principles-Data-Science-Sinan-Ozdemir-ebook/dp/B01A8T8YNC)


##Introduction / Expectations / Intro to Data Science

Agenda

* Introduction to General Assembly [slides](slides/01_DAT_intro_deck.pdf)
* Course overview: our philosophy and expectations ([slides](slides/01_course_overview.pdf))
* Ice Breaker

Break -- [**Command Line Tutorial**](http://generalassembly.github.io/prework/cl)

* Figure out office hours
* Intro to Data Science: [slides](slides/01_intro_to_data_science.pdf)

Homework


* Setup a [conda virtual environment](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)
* Install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and create a [GitHub](https://github.com/) account.
	* Read my intro to [Git](slides/01_git.pdf) and be sure to come back on monday with your very own repository called "sfdat28-lastname"
* Once you receive an email invitation from [Slack](https://slack.com/), join our "SFDAT28 team" and add your photo!
* Introduction on how to read and write iPython notebooks [tutorial](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/intro_to_ipython_notebooks.ipynb)


### Class 2: Introduction to Pandas

####Goals

* Feel comfortable importing, manipulating, and graphing data using Python's Pandas
* Be able to find missing values and begin to have a sense of how to deal with them


####Agenda

* Don't forget to `git pull` in the sfdat26 repo in your command line
* Intro to Pandas walkthrough [here](notebooks/02_pandas.ipynb)
	* [Pandas Lab 2](labs/02_pandas_lab.ipynb) Solutions [here](labs/02_pandas_lab_soln.ipynb)

####Homework
* Go through the python class/lab work and finish any exercise you weren't able to in class
* Make sure you have all of the repos cloned and ready to go
	* You should have both "sfdat28" and "sfdat28-lastname"
* Read Greg Reda's [Intro to Pandas](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/)
* Take a look at Kaggle's [Titanic competition](https://www.kaggle.com/c/titanic)
* I will be using a module called `tweepy` next time. 
	* To install please type into your console `pip install tweepy`

#### Resources:
* Another Git tutorial [here](http://try.github.io)
* In depth Git/Github tutorial series made by a GA_DC  Data Science Instructor [here](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD)
* [Another Intro to Pandas](http://nbviewer.ipython.org/gist/wesm/4757075/PandasTour.ipynb) (Written by Wes McKinney and is adapted from his book)
	* [Here](https://vimeo.com/59324550) is a video of Wes McKinney going through his ipython notebook!
* Examples of [joins in Pandas](http://www.gregreda.com/2013/10/26/working-with-pandas-dataframes/#joining)
* For more on Pandas plotting, read the [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation.

#### Next Time on SFDAT28...

* Maria finds out that Sancho has been cheating on her with her.. mother!
* We will use python to programatically obtain data via open sources on the internet
	* We will be scraping the [National UFO reporting center](http://nuforc.org/)
	* We will be collecting tweets regarding Donald Trump and Hilary Clinton
	* We will be examining What people are really looking for in a data scientist..
	
* We will continue to use pandas to investigate missing values in data and have a sense of how to deal with them
