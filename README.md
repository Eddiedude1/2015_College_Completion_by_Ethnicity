# Project 4 - Choose your own adventure

Due Date: November 29, 2017

As you progress through the course, the projects are going to give way to working on your capstone. In preparation for this transition, each instructor has chosen a dataset for you to simply play around with and explore.

From those three datasets, **you'll choose one** that is of interest to you. Use the skills you've learned up to this point (EDA, machine learning, etc), and see what you can come up with.

Unlike the previous projects, this one is intentionally left open-ended; there are no specific questions for you to answer and no set path that you have to follow. We're excited to see where your curiosity takes you.

Here are the three datasets:

## From Richard
I've provided a collection of posts from reddit.com from numerous programming-focused subreddits. Your task is...to give us a model!

As Data Scientists, it is very frequently up to us to find an interesting questions and useful inferences from a body of data. Similar to our expectations for your Capstone Project, this is a situation where you will manage both the development of a question and your approach for modelling it.

Within this directory you will find a csv containing all posts made to a specific set of subreddits (message boards) during the month of December, along with some additional data (the number of upvotes from the community, the number of comments made on the post, etc.) While reddit allows you to submit a link in place of text, this data has been subset to only self-posts (posts where the writer has submitted text instead of a link elsewhere).

## From Justin
For this project you will assemble a dataset for investigating colleges and universities.  Fortunately, there is a large collection of higher education data from the government that is accessible through an API.  This service provides tons of data, from cost statistics to admission rates to instructional expenditures!

The data spans a number of years and categories, so simply deciding what data you want to look at and how you want to analyze will take some time.

A successful project will pull down data, perform thorough EDA and build *at least* one model.  (What you model is up to you, and remember that models can be predictive *or* inferential!).  You could also look at the possibility of clustering to identify different types of schools.

> **Pro tip:** The rate limit is quite high for the API service, but it is still a good idea to cache your data to local file once you have retrieved it.  This allows you to reload your data faster and work offline, not to mention just playing "nice" with the API service.

The main data documentation is available at [https://collegescorecard.ed.gov/data/documentation/](https://collegescorecard.ed.gov/data/documentation/). This page includes a detailed data dictionary as well as a couple of reports describing the data.  That page also links to the specific [API documentation](https://github.com/RTICWDT/open-data-maker/blob/master/API.md).

To use the API you will need to signup for a (free) API key on [https://api.data.gov/docs/](https://api.data.gov/docs/).  This page also includes links describing [API key usage](https://api.data.gov/docs/api-key/) and [rate limits](https://api.data.gov/docs/rate-limits/).

## From Riley
If you're a fan of March Madness, this is the dataset for you! Every year, Kaggle hosts their "March Machine Learning Mania" competition, wherein you build a model to predict the winner of the NCAA men's basketball tournament. Last year, I finished in a respectable-yet-forgettable 57th place.

It's never too early to start building your model. The data you'll be using is current through last year's season, and will be updated when next year's competition starts (late Jan/early Feb?).

If you have a good workflow set up by then, all you'll need to do is download the latest CSVs and you'll be good to go!

> **WARNING**: When predicting the outcome of a game, you can use stats that occur up to **but not including** that particular game.

https://www.kaggle.com/c/march-machine-learning-mania-2017/data

## Project Feedback + Evaluation

For all projects, students will be evaluated on a simple 4 point scale (0-3 inclusive). Instructors will use this rubric when scoring student performance on each of the core project requirements:

Score | Expectations
----- | ------------
**0** | _Does not meet expectations. Try again._
**1** | _Approaching expectations. Getting there..._
**2** | _Meets expecations. Great job._
**3** | _Surpasses expectations. Brilliant!_

For Project 4 the evaluation categories are as follows:

- **Organization**:	Clearly commented, annotated and sectioned Jupyter notebook or Python script. Comments and annotations add clarity, explanation and intent to the work. Notebook is well-structured with title, author and sections. Assumptions are stated and justified.
- **Exploratory Data Analysis**: A thorough exploratory data analysis has been conducted. Descriptive statistics, univariate and bivariate analysis, and plotting are skillfully used to explore connections across the dataset between features and targets.
- **Modeling Process**: Skillful and correct use of cross-validation, grid search, and goodness-of-fit metrics to evaluate candidate models. Assumptions and decisions in the modeling process are stated and justified. Use of correct modeling techniques in each challenge. Data is reproducibly and reliably transformed between training and test datasets.
