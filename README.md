## SF DAT 28 Course Repository

Course materials for General Assembly's Data Science course in San Francisco, CA (10/4/16 - 12/13/16).

**Instructors:** [Sinan Ozdemir](https://www.linkedin.com/in/sinan-ozdemir-10568534) 

**Teaching Assistants:**
[George McIntire](https://www.linkedin.com/in/georgemcintire)
[Cari Levay](https://www.linkedin.com/in/carilevay)

**Course Times**

Tuesday/Thursday: 6:30pm - 9:30pm

**Office hours:** 

Tue/Thurs: 5:30pm - 6:30pm (right before class)

Wed: 6pm - 8pm

Sat: 10am - 12pm

All courses / office hours will be held at GA, 225 Bush Street

**[Course Project Information](project.md)**

**[Course Project Examples](project-examples.md)**


Tuesday | Thursday | Project Milestone | HW
--- | --- | --- | ---
10/4: Introduction / Expectations / Intro to Data Science | 10/6: Pandas
10/11: APIs / Web Scraping 101 | 10/13: Intro to Machine Learning / KNN | | HW 1 Assigned (Th)
10/18: Model Evaluation / Linear Regression Part 1 | 10/20: Linear Regression Part 2 / Logistic Regression | Three Potential Project Ideas (Th) | 
10/25: Natural Language Processing | 10/27: Naive Bayes Classification  ||HW 1 Due (Th)
11/1: Advanced Sklearn (Pipeline and Feaure Unions) | 11/3: Review || 
11/8: Decision Trees  | 11/10: Ensembling Techniques | |HW 2 Assigned (Th)
11/15: Dimension Reduction | 11/17: Clustering / Topic Modelling | First Draft Due (Th) | 
11/22: Stochastic Gradient Descent | 11/23: No Class | Peer Review Due (T)
11/29: Neural Networks / Deep Learning | 12/1: Recommendation Engines ||HW 2 Due (Th)
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

### Class 3: APIs / Web Scraping 101

####Agenda

* To install tweepy please type into your console `pip install tweepy`
* Slides on Getting Data [here](slides/03_getting_data.pdf)
* Intro to Regular Expressions [here](notebooks/03_regex_example.ipynb)
* Getting Data from the open web [here](notebooks/03_getting_data_from_web.ipynb)
* Getting Data from an API [here](notebooks/03_getting_data_from_api.ipynb)
* LAB on getting data [here](labs/03_getting_data_lab.ipynb)

####Homework
* The first homework will be assigned by Friday morning (in a homework folder) and it is due in two Thursdays 
	* It is a combo of pandas question with a bit of API/scraping
	* Please push your completed work to your sfdat28_work repo for grading
* Your [first project milestone](project.md) is due next Thursday. It is the first three ideas you have for your project. Think about potential interesting sources of data you would like to work with. This can come from work, hobby, or elsewhere!

####Resources:

* [Mashape](https://www.mashape.com/) allows you to explore tons of different APIs. Alternatively, a Python API wrapper is available for many popular APIs.
* [The Data Science Toolkit](http://www.datasciencetoolkit.org/) is a collection of location-based and text-related APIs.
* [API Integration in Python](https://realpython.com/blog/python/api-integration-in-python/) provides a very readable introduction to REST APIs.
* [Microsoft's Face Detection API](https://www.microsoft.com/cognitive-services/en-us/face-api#detection), which powers [How-Old.net](https://how-old.net/), is a great example of how a machine learning API can be leveraged to produce a compelling web application.
Web Scraping Resources:
* For a much longer web scraping tutorial covering Beautiful Soup, lxml, XPath, and Selenium, watch [Web Scraping with Python](https://www.youtube.com/watch?v=p1iX0uxM1w8) (3 hours 23 minutes) from PyCon 2014. The slides and code are also available.
* [import.io](https://www.import.io/) and [Kimono](https://www.kimonolabs.com/) claim to allow you to scrape websites without writing any code. Its alrighhhtttttt
* [How a Math Genius Hacked OkCupid](http://www.wired.com/2014/01/how-to-hack-okcupid/all/) to Find True Love and [How Netflix Reverse Engineered](http://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/?single_page=true) Hollywood are two fun examples of how web scraping has been used to build interesting datasets.


### Class 4: Intro to Machine Learning / KNN

####Agenda

* Iris pre-work [code](notebooks/04_iris_prework.ipynb)
	* Using numpy to investigate the iris dataset further
	* Understanding how humans learn so that we can teach the machine!
	* If needed, read intro to numpy [code](notebooks/04_numpy_ref.ipynb)
		* Numerical Python, code adapted from tutorial [here](http://www.engr.ucsb.edu/~shell/che210d/numpy.pdf)
		* Special attention to the idea of the np.array

* Intro to Machine Learning and KNN [slides](slides/04_ml_knn.pdf)
	* Supervised vs Unsupervised Learning
	* Regression vs. Classification

* [Lab](labs/04_knn_lab.ipynb) to use KNN models to investigate accelerometer data


####Homework

* The one page project milestone as well as the pandas homework! [See requirements here](project.md)
* Read this excellent article, [Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html), and be prepared to discuss it in class on Wednesday. (You can ignore sections 4.2 and 4.3.) Here are some questions to think about while you read:
    * In the Party Registration example, what are the features? What is the response? Is this a regression or classification problem?
    * In the interactive visualization, try using different values for K across different sets of training data. What value of K do you think is "best"? How do you define "best"?
    * In the visualization, what do the lighter colors versus the darker colors mean? How is the darkness calculated?
    * How does the choice of K affect model bias? How about variance?
    * As you experiment with K and generate new training data, how can you "see" high versus low variance? How can you "see" high versus low bias?
    * Why should we care about variance at all? Shouldn't we just minimize bias and ignore variance?
    * Does a high value for K cause over-fitting or under-fitting?
* For our talk on linear regression, read:
	* This [explanation](http://blog.minitab.com/blog/adventures-in-statistics/how-to-correctly-interpret-p-values) of p values
	* [Correlation does not imply Causation](http://tylervigen.com/spurious-correlations)
	* [P-values can't always be trusted](http://fivethirtyeight.com/features/science-isnt-broken/#part2)
	
    
**Resources:**

* For a more in-depth look at machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (It's a free PDF download!)
* Stackoverflow article on the difference between generative and discriminative models [here](http://stackoverflow.com/questions/879432/what-is-the-difference-between-a-generative-and-discriminative-algorithm)