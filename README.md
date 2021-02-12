

### About: 

- This Project and notebooks are currently 'work in progress'. 

- It's inspired by [Open Source Society University](https://github.com/ossu/data-science), peter norvig's [pytudes project](https://github.com/norvig/pytudes#pytudes-index-of-jupyter-ipython-notebooks),
multiple Project's by folks like: [Donne_Martin](https://github.com/donnemartin/data-science-ipython-notebooks), [Dfriends](https://dfrieds.com/), [Chris_albon](https://chrisalbon.com/) and many others. 

- It provides an opportunity to document some of my own learnings and acts as a [data science road map](https://i.am.ai/roadmap/#fundamentals) for self-taught learners out there to learn data science for free 

- Data Science is closely related to litrate programming paradigm(as conceived by Don Knuth) and scientific computing 

--------------------------------------------------------------------------------------------------------

## Topics: 

- [Introduction to data Science](#introduction-to-Data-Science)
- [Data Science Experiment LifeCyle](#Data-Science-Experiment-LifeCyle)
- [Data Wrangling Tools](#Data-Wrangling-Tools)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Cleaning](#Data-Cleaning)
- [Data Analytics (Descriptive, Inferential, Predictive, Causal)](#Data-Analytics)
- [Importance of Story telling and Case Studies](#Importance-of-Story-telling-and-Case-Studies)
- [Experimental Design](#Experimental-Design)
- [Product Related Analysis](#Product-Related-Analysis)
- [Natural Language Processing](#Natural-Language-Processing)
- [Decision Making (Probability, Reinforcement Learning)](#Decision-Making-(Probability,-Reinforcement-Learning))
- [Process Analytics](#Process-Analytics)
- [Data Engineering (Large Scale Data Processing)](#Data-Engineering-(Large-Scale-Data-Processing))
- [Math for Data Science](#Math-for-Data-Science)
- [Project Management for data Science](#Project-Management-for-data-Science)
- [Inspiring data Product](#Inspiring-Data-products)
- [Useful datasets](#Useful-datasets) 

--------------------------------------------------------------------------------------------------------

## Introduction to Data Science 

Data Science has been around for a while. Even big data has been around for a while(Hubble has been sending us image data and Scientists at 
CERN have been collecting Tera Bytes to uncover the secrets of the universe). Business recently realised that can extract value out of the 
data they collect(e.g user data and event data) to make data-informed decisions which replaces the old model of going with the gut instinct, 
loudest voice, and best argument methods. The insights gathered through this process can help improve existing processes and lower operations cost. 
Learning 'how to be smart with data' is also bit of an art, that requires curosity, creativity and attention to detail and so on. 
All of this requires experience and practice.  

Instead of providing a sophisticated definition of Data Science, We run with this definition for now(by J. Kolter at CMU): 

> Data science = statistics + data collection + data preprocessing + machine learning + visualization + business insights + scientific hypotheses + big data + (etc)


[cheatsheet]:(https://st2.ning.com/topology/rest/1.0/file/get/1211570060?profile=original)

Types of data scientists by Michael Hochster:


> Type A Data Scientist: The A is for Analysis. This type is primarily concerned with making sense of data or working with it in a fairly static way. The Type A Data Scientist is very similar to a statistician (and may be one) but knows all the practical details of working with data that aren’t taught in the statistics curriculum: data cleaning, methods for dealing with very large data sets, visualization, deep knowledge of a particular domain, writing well about data, and so on.
> Type B Data Scientist: The B is for Building. Type B Data Scientists share some statistical background with Type A, but they are also very strong coders and may be trained software engineers. The Type B Data Scientist is mainly interested in using data “in production.” They build models which interact with users, often serving recommendations (products, people you may know, ads, movies, search results).


read more: 
- [Competing in a Data-Driven World: An executive Guide](https://asjadkhan.ghost.io/generating-business-value-with-ai-an-executive-guide/)
- [Rise of Data Products](https://asjadkhan.ghost.io/untitled/)
- [Beautiful data](https://learning.oreilly.com/library/view/beautiful-data/9780596801656/)
----------------------------------------------------------------------------------------------------------------
##  Data Science Experiment LifeCyle: 


#### Introduction: 

- Every data Science Project starts with a question that is to be answered with data. That means forming the question is an important first step in the process. 
- The second step is finding or generating the data you are going to use to answer that question. 
- With that question solidified and data in hand, the data are then analysed, first by exploring the data and then often by modeling the data, which means using some statisitcal or machine learning techniques to analyse the data and answer your question
- This is an iterative Process 
- After drawing conclusions from this analysis, the project has to be communicated to others.


#### Details: 

Data Science analytics are a lot like broccoli – fractal in nature in
both time and construction. Early versions of an analytic follow the
same development process as later versions. At any given iteration, the
analytic itself is a collection of smaller analytics that often decompose
into yet smaller analytics. 

Decomposing the problem into manageable pieces is the frist step
in the analytic selection process. Achieving a desired analytic action
often requires combining multiple analytic techniques into a holistic,
end-to-end solution. Engineering the complete solution requires that
the problem be decomposed into progressively smaller sub-problems.
Fractal Analytic Model embodies this approach. At any given
stage, the analytic itself is a collection of smaller computations that
decompose into yet smaller computations. When the problem is
decomposed far enough, only a single analytic technique is needed
to achieve the analytic goal. Problem decomposition creates multiple
sub-problems, each with their own goals, data, computations, and
actions.


![alt text](images/data_science_process.png "Logo Title Text 1")

read more: 
  - [A Recipe for Doing Great Data Science Work] (https://dfrieds.com/articles/recipe-great-data-science-work.html)
  - [General Check-list for ML Projects] (https://towardsdatascience.com/task-cheatsheet-for-almost-every-machine-learning-project-d0946861c6d0)

#### references: 
  - Data Science Field guide - Booz Allen Hamilton
  - https://dfrieds.com/articles/recipe-great-data-science-work.html
  

----------------------------------------------------------------------------------------------------------------
## Python Programming


- How to think like a CS in python
- SCIP in python
- Hitch Hiker's Guide to python
- python env https://jacobian.org/2018/feb/21/python-environment-2018/
- Cheatsheet
- Mit Hacker tools
- [Data Algorithms](https://github.com/asjad99/modern_algorithms_toolkit)   

### Data Wrangling Tools and Libraries 

Data wrangling is about taking a messy or unrefined source of data and turning it into something useful. 
You begin by seeking out raw data sources and determining their value: How good are they as data sets? 
How relevant are they to your goal? Is there a better source? Once you’ve parsed and cleaned the data so that the data sets are usable, 
you can utilize tools and methods (like Python scripts) to help you analyze them and present your findings in a report. 
This allows you to take data no one would bother looking at and make it both clear and actionable.

#### Learning the tools 

| Notebook                 | Description | Code |
|--------------------------|-----------|------|
| Command-line             | Learn various unix command line utlities and how they can be used to clean and compute basic statistics          | [blog_post](https://asjadkhan.ghost.io/ghost/#/site) |     
| Web Data Collection      | Learn to collect data available on web (APIs or web scrapping)          | [Notebook](https://github.com/asjad99/datascience-GYM/tree/master/data_engineering)          |  
| numpy_Basics     | Learn the basics of the library that underpins scientific computing          |[Notebook](/work/datascience-GYM/Data_Munging/[Numpy]basics.ipynb)        | 
| numpy_linear_algebra     |           |Notebook        |     
| Pandas Basics            | Learn the basics of pandas        |[Notebook](https://github.com/asjad99/datascience-GYM/blob/master/Data_Munging/Pandas.ipynb)        |      |

-------------------------------------------------------------------------------------------------------------------

## Exploratory Data Analysis  

People are not very good at looking at a column of numbers or a whole spreadsheet and then determining important characteristics of the data. 
They find looking at numbers to be tedious, boring, and/or overwhelming.
Exploratory data analysis techniques have been devised as an aid in this situation. 
Most of these techniques work in part by hiding certain aspects of the data while making other aspects more clear.

Overall, The goal of exploratory analysis is to examine or explore the data and find relationships that weren’t previously known. 
Exploratory analyses explore how different measures might be related to each other but do not confirm that relationship as causitive. 

EDA always precedes formal (confirmatory) data analysis. 
 
EDA is useful for:

- detection of mistakes
- checking of assumptions
- determining relationships among the explanatory variables
- assessing the direction and rough size of relationships between explanatory
and outcome variables, 
- preliminary selection of appropriate models of the relationship between an
outcome variable and one or more explanatory variables.

##### EDA Methods: 

- EDA method is either non-graphical or graphical. 
- Each method is either univariate or multivariate (usually just bivariate).
- Overall,the four types of EDA are univariate non-graphical, multivariate nongraphical, univariate graphical, and multivariate graphical.
- Non-graphical methods generally involve calculation of summary statistics, while graphical methods obviously summarize the data in a diagrammatic or pictorial way. 
- Univariate methods look at one variable (data column) at a time, while multivariate methods look at two or more variables at a time to explore relationships. Usually our multivariate EDA will be bivariate (looking at exactly two variables), but occasionally it will involve three or more variables. It is almost always a good idea to perform univariate EDA on each of the components of a multivariate EDA before performing the multivariate EDA.

We should always perform appropriate EDA before further analysis of our data. Perform whatever steps are necessary to become more familiar with your data, check for obvious mistakes,
learn about variable distributions, and learn about relationships between variables. EDA is not an exact science – it is a very important
art!


##### statistical knowledge required: 

(Expectation and Mean, Variance and Standard deviation, Covarriance and Correlation, Median Quartile, Interquartile range, Percentile/quantile,Mode  )

##### visualization knowledge required: 
  knowing which methods are suitable for which type of data 


| Title            | Description | Code |
|---------------------|-------------|------|
| Univariate Non-Graphical Data Exploration    | Learn Exploratory data analysis using air pollution and temperature data for the city of Chicago          |  [Notebook](https://deepnote.com/project/8c259dff-61ed-46cb-aa94-fdda7d3fdc8e#%2Fdatascience-GYM%2FData_Munging%2F%5Bpandas%5DEDA_pollution.ipynb)    |
| Univariate Non-Graphical Data Exploration    | Data Exploration using data ozone levels dataset          | [Notebook](https://deepnote.com/project/8c259dff-61ed-46cb-aa94-fdda7d3fdc8e#%2Fdatascience-GYM%2FData_Munging%2F%5BPandas%5DEDA_ozone.ipynb)    |
| Graphical Data Exploration    | Data Exploration using visualization techniques        | Notebook    |

Useful Guides: 

- [Chapter 4, Experimental Design and Analysis by Howard J. Seltman](http://www.stat.cmu.edu/~hseltman/309/Book/Book.pdf)
- [Section 1, Hands-On Exploratory Data Analysis with Python](https://www.packtpub.com/product/hands-on-exploratory-data-analysis-with-python/9781789537253)
- [Chapter 1, Practical Statistics for Data Scientists, 2nd Edition](https://learning.oreilly.com/library/view/practical-statistics-for/9781492072935/ch01.html) 

practice projects: https://github.com/ammarshaikh123/Projects-on-Data-Cleaning-and-Manipulation

----------------------------------------------------------------------------------------------------------------

## Data Cleaning: 

Real-world data is rarely clean and homogeneous. It is often said that 80% of data analysis is spent on the process of cleaning and preparing the data (Dasu and Johnson 2003). Data preparation is not just a first step, but must be repeated many over the course of analysis as new problems come to light or new data is collected

Data Formats should be easy for computers to parse, people to read and widely used by systems in production. 
The computations we perform must be reproducible and tweakable. 

![alt text](images/data_cleaning.png "Logo Title Text 1")




| Notebook            | Description | Code |
|---------------------|-------------|------|
| Data Cleaning       | Learn data cleaning with synthetic data | [Notebook](https://deepnote.com/project/8c259dff-61ed-46cb-aa94-fdda7d3fdc8e#%2Fdatascience-GYM%2FData_Munging%2F%5BPandas%5Ddata_cleaning.ipynb)|


### useful guides: 
- [Tidy data](http://vita.had.co.nz/papers/tidy-data.pdf) 
- [Reproducability in Data Science](https://maxmasnick.com/media/slides/data-analysis-reproducibility/data-analysis-reproducibility.pdf)
- Guide by Jeff lean on [how to share data with a statistician](https://github.com/asjad99/datascience-GYM/blob/master/Data_Munging/3.%20Data_Cleaning.ipynb)
- Best Practices in Data Cleaning: A Complete Guide to Everything You Need to Do Before and After Collecting Your Data
- Data Wrangling with Python by Jacqueline Kazil, Katharine Jarmul
- Clean Data by Megan Squire 
- Python Data Cleaning Cookbook - Modern techniques and Python tools to detect and remove dirty data and extract key insights
By: Michael Walker

----------------------------------------------------------------------------------------------------------------

## Data Analytics: 

we cover the following topics: 

1. Descriptive Analysis:
    The goal of descriptive analysis is to describe or summarize a set of data. 

2. Inferential Analysis:
    The goal of inferential analysis is to use a relatively small sample of data to infer or say something about population at large. 

3. Predictive Analytics:
    The goal of predictive analysis is to use current data to make predictions about future data. 

4. Causal Analysis: 
    The caveat to a lot of the analysis we have looked at above is that we can only see correlations and can’t get at the cause of the 
    relationships we observe. Causal analysis fills that gap. the goal of the causal analysis is to see what happens to one variable when we manipulate anohter variable. looking at the cause and effect of a relationship. 

### Descriptive Analysis 

Descriptive Analytics is aimed at answering real busiessn questions. Describing the dataset at hand, Discovering insigths and Acting on those insights. 
It requires finding meaningful patterns, trends and exceptions that are easy to see and interpret for decision makers. 

The goal of descriptive analysis is to describe or summarize a set of data. Whenever you get a new dataset to examine, this is usually the first kind of analysis you will perform. Descriptive analysis will generate simple summaries about the samples and their measurements. You may be familiar with common descriptive statistics: measures of central tendency (eg: mean, median, mode) or measures of variability (eg: range, standard deviations or variance).
This type of analysis is aimed at summarizing your sample – not for generalizing the results of the analysis to a larger population or trying to make conclusions. Description of data is separated from making interpretations; generalizations and interpretations require additional statistical steps.
Some examples of purely descriptive analysis can be seen in censuses. Here, the government collects a series of measurements on all of the country’s citizens, which can then be summarized. Here, you are being shown the age distribution in the US, stratified by sex. The goal of this is just to describe the distribution. There is no inferences about what this means or predictions on how the data might trend in the future. It is just to show you a summary of the data collected.


- Framing a question
- Statistics knowledge (covered earlier in EDA)


### Projects: 

| Notebook            | Description | Code |
|---------------------|-------------|------|
| Data Visualization  | Analyse Stackoverflow data using visaluzation techniques   |       |
| Taxi data Analysis  | Mobility behaviour Analysis  of rome taxi driver |  [Repo](https://github.com/asjad99/mobility-intelligence)    | 


Useful Guides: 
- Guide for [Common Data Types and Formats](https://github.com/asjad99/datascience-GYM/blob/master/Data_Munging/2.%20data_types_formats.ipynb)
- [Statistics for Social Sciences](http://www.stat.cmu.edu/~hseltman/309/Book/Book.pdf)
- [Edward Tufte's Books](https://www.edwardtufte.com/tufte/)
- [Economist](https://www.economist.com/graphic-detail/)
- [What's going on in this graph](https://www.nytimes.com/column/whats-going-on-in-this-graph)
- [A network of science: 150 years of Nature papers](https://www.youtube.com/watch?v=GW4s58u8PZo)

### Inferential analysis

The goal of inferential analysis is to use a relatively small sample of data to infer or say something about population at large. 


| Notebook            | Description | Code |
|---------------------|-------------|------|
| Inferential Analysis  |         |  Notebook|
Useful resoruces: 

https://www.coursera.org/specializations/statistics-with-python  
Experimental Design and Analysis: http://www.stat.cmu.edu/~hseltman/309/Book/Book.pdf

### Causal analysis

The caveat to a lot of the analysis we have looked at above is that we can only see correlations and can’t get at the cause of the relationships we observe. Causal analysis fills that gap. the goal of the causal analysis is to see what happens to one variable when we manipulate anohter variable. looking at the cause and effect of a relationship. 
https://ff13.fastforwardlabs.com/ 

----------------------------------------------------------------------------------------------------------------
## Importance of Story telling and Case Studies

Context, inferences and models are created by humans and carry with them biases and assumptions. Blindly trusting your analyses is a dangerous thing
that can lead to erroneous conclusions. We should try to clearly communite our findings by describing: 

- What problem are we trying to solve and why its intresting? 
- Document your assumptions and make sure they have not introduced bias in your work.
- Does the approach taken and answers make sense? (we should be Be skeptical of surprise findings and make sure the analysis address the
original intent)

The goal of your analysis is to tell an actionable story. 
Its good to see some data science projects and learn from them. 
In each project, the author had a question they wanted to answer and used data to answer that question. 
They explored, visualized, and analysed the data. Then, they wrote blog posts to communicate their findings. 
Take a look to learn more about the topics listed and to see how others work through the data science project process and communicate their results!

- https://pennmusa.github.io/MUSA_801.io/project_5/index.html
- https://sharlagelfand.netlify.app/posts/tidying-toronto-open-data/
- https://masalmon.eu/2017/11/16/wheretoliveus/
- http://varianceexplained.org/r/trump-tweets/

----------------------------------------------------------------------------------------------------------------

## Experimental Design

### Randomized Control 

### Hypothesis Testing 

![alt text](images/experiment_cycle.png "Logo Title Text 1")

### A/B Testing

>As a Data Scientist, you get to establish causality (something really hard to do with observational data) by running actual randomized, controlled experiments. At Twitter, “It’s rare for a day to go by without running at least one experiment” — Alex Roetter, VP of Engineering. A/B testing is ingrained in our DNA and our product development cycle.

Here is the typical process of running a A/B test: Gather Samples -> Assign Buckets -> Apply Treatments -> Measure Outcomes -> Make Comparisons. 

Hypothesis Testing: Statistical test, p-values, statistical significance, power, effect size, multiple testing


Useful Guide: 
- [Experimental Design and Analysis by Howard J. Seltman](http://www.stat.cmu.edu/~hseltman/309/Book/Book.pdf)
- http://www.datasciencecourse.org/slides/hypothesis_testing.pdf 
- So, you need a statistically significant sample?
- Experiments at Airbnb
- When should A/B testing not to be trusted when making decisions

----------------------------------------------------------------------------------------------------------------

## Product Related Analysis

Examples of Analysis at twitter: 

1. Push Notification Analysis — How many users are eligible for push notifications? across user segment? across clients? What are the tap rates of different push notification types?
2. SMS Delivery Rates — How do we calculate Twitter’s SMS delivery rates across different carriers? Are our delivery rates in emerging countries poorer? How can we make them better?
3. Multiple Accounts — Why do certain countries have a higher ratio of multiple accounts? What drive people to create multiple account?

> Generating insights through product analysis is an iterative process. It requires challenging the questions being asked, understanding the business context, and figuring out the right dataset to answer the questions. Over time, you will become an expert in where the data lives and what they mean. You will get better at estimating how much time it will take to carry out an analysis. More importantly, you will slowly move from a reactive state to proactive state and start suggesting interesting analyses that product leaders might not think of, because they don’t know the data exists or that disparately different data sources can be complementary and combined in a particular way.

- Gather Samples — How many samples do we need? How many users should go into each bucket? Can we ensure that the experiment will have sufficient power?
- Assign Buckets — Who are eligible to be in the experiments? and where in the code should we start assigning buckets and showing treatments? Would the placement introduce data dilution (i.e. some users are assigned to treatment but never see it)?
- Apply Treatment — Are there any other teams in the organization running experiments that are competing for the same real estate in the app? How do we deal with experiment collision and ensure our data is not contaminated?
- Measure Outcome — What is the hypothesis of the experiment? What are the success and failure metrics of this experiment? Can we track them? and How? What additional logging do we need to add?
- Make Comparisons — Suppose we see that the # of users who logged-in increase dramatically, is it due to noise? How do we know if the results are statistically significant? Even if it is, is it practically significant?


Implementing models: 

  Set up the infrastructure, aggregate and prepare the data, and
incorporate domain expert knowledge. Try different analytic
techniques and models on subsets of the data. Evaluate the models,
refine, evaluate again, and select a model. Do something with your
models and results – deploy the models to inform, inspire action, and
act. Evaluate the business results to improve the overall product.

----------------------------------------------------------------------------------------------------------------

## Predictive Analytics with Machine Learning 

Machine Learning  
- Machine Learning is the modern probabilistic approach to artificial intelligence. It studies algorithms that learn to predict from (usually independent and identically distributed) data.
- It Utilizes past observation data to predict future observations. e.g Can we predict which products
that certain customer groups are more likely to purchase? 
- It also allows us to implement cool new feature like smart reply in gmail. 

- Jeff Bezos in his 2016 letter to Amazon shareholders:

> Over the past decades computers have broadly automated tasks that programmers could describe with clear rules and algorithms. 
Modern machine learning techniques now allow us to do the same for tasks where describing the precise rules is much harder.

- In terms of impact most of AI technologies currently being deployed are still falling under this machine learning. 

According to Andrew NG: 

> Almost all of AI’s recent progress is through one type, in which some input data (A) is used to quickly generate some simple response (B). Being able to 
input A and output B will transform many industries. The technical term for building this A→B software is supervised learning. These A→B systems have been
improving rapidly, and the best ones today are built with a technology called deep learning or deep neural networks, which were loosely inspired by the brain. 


#### Machine Learning Engineer: 

a machine learning engineer is someone who sits at the crossroads of data science and data engineering, and has proficiency in both data engineering and 
data science.

![alt text](images/ml_problems.png "Logo Title Text 1")


The ultimate goal of Machine learning is to be able to generatize to new unseen data. i.e predicting
behavior under new conditions. we study Problems like: Regression, Clustering, Classication, Recommendation. 



#### General Process for Machine Learning Projects: 

![alt text](images/process.png "Logo Title Text 1")





### Data Prep-Processing for Machine learning 

Note: Data Cleaning and EDA was covered earlier, the next step is pre-processing 


- Dimensionality Reduction
- Normalization 
- Unbiased Estimators 
- Binning Sparse values 
- Feature Extraction 
- Denoising 
- Sampling 


| Algorithm           | Notebooks | Description |
|---------------------|-----------|-------------|
| Linear Regression   |           |             |
| Logistic Regression |           |             |
| SVMs                |           |             |
| XGboost             |           |             |
| Clustering          |           |             |



#### Useful Guides: 

- [Neural Networks](http://karpathy.github.io/neuralnets/) 
- [Machine Learning Mind Map](https://github.com/dformoso/machine-learning-mindmap) 
- [Understanding Generalizations in Machine Learning](https://www.asjadk.io/untitled-3/)
- [Why is ML hard](http://ai.stanford.edu/~zayd/why-is-machine-learning-hard.html)
- [Debugging ML Systems by Andrew Ng](https://d2wvfoqc9gyqzf.cloudfront.net/content/uploads/2018/09/Ng-MLY01-13.pdf)
- [Feature Engineering and dimensionality reduction](https://learning.oreilly.com/library/view/feature-engineering-for/9781491953235/)
- [Challenges in Deploying Machine Learning: a Survey of Case Studies](https://arxiv.org/abs/2011.09926)
- [Challenges in Production](https://blog.acolyer.org/2019/10/07/150-successful-machine-learning-models/)



----------------------------------------------------------------------------------------------------------------



## Deep Learning and Natural Language Processing

- According to J. Kolter at CMU:  

> for many data science problems, simple machine learning algorithms suffice to attain sufficiently good performance (by whatever metric you want to define performance, but I simply mean that they effectively solve the problem). The numbers here are all just examples (specifically the solvable/unsolvable ratio), but the point it gets at is important. There are many data science problems one would like to be able to solve, but in a large number of these cases, there is simply no way to solve the problem given the available data. For the set of problems that are solvable with some kind of machine learning, the vast majority will be solvable at least to a level of sufficient performance, using relatively simple models. The 5% of remaining problems is an important one, because they often consist of the most “interesting” problems from a research standpoint (think problems like speech recognition, natural language understanding, computer vision), but they are often not indicative of the types of problems one encounters in “most” data science applications.


Topics: 

1. Know about standard architectures (MLP, vanilla RNN, LSTM (also see this blog), GRU, conv layers, resnets, attention mechanisms), 
2. common regularizers (weight decay, dropout)
3. Normalization (batch norm, layer norm, weight norm)
4. Optimizers (SGD, momentum SGD, Adam, others). 
5. the reparameterization trick 
6. Practice and Trends: https://www.youtube.com/watch?v=YJnddoa8sHk


Useful guides: 
  - [How neural networks work](https://omar-florez.github.io/scratch_mlp/)
  - [Deep Learning Nature Paper](https://www.nature.com/articles/nature14539)
  - [History of Deep Learning](https://www.asjadk.io/history-of-deep-learning/)





----------------------------------------------------------------------------------------------------------------

## Decision Making  (Optimal Decision in Prescene of uncertainty with probability:) 

- http://www.datasciencecourse.org/notes/probability/ 

### Markov decision Processes and Reinforcement Learning:  

We can model many problems as a Markov Decision Process or POMDP. We define a reward function that captures out goals and we then find a policy that maximuses the sum of future rewards.
This is similar to Operations Research techniques focused on selecting the best element from a set of available alternatives to maximize a utility function. 

#### My Notes on RL Theory: 
  - 3 pillers of reinforcement learning 
  - Exploration vs Exploitaion 
  - [RL in the Real World: Challenges and Opportunities](https://asjadkhan.ghost.io/real-world-rl/?fbclid=IwAR0jDaeMeALcSnEZu3gVq1MfZQegeXbWuWYt5W3PJNV1NiSePABsoAvS2EY)
  - Counterfactual Policy Evaluation  


### Deep Learning and Reinforcement Learning 


#### Deep Q-Network (DQN):


    - For artificial agents to be considered truly intelligent they should excel at a wide variety of tasks that are considered challenging for humans. Until this point, it had only been possible to create individual algorithms capable of mastering a single specific domain. 
    - Successfully combining Deep Learning (processing perception) with RL (decision-making) at scale for the first time 
    - is able to master a diverse range of Atari 2600 games to superhuman level with only the raw pixels and score as inputs.
    - Takes the raw inputs and a reward signal (e.g the score) and it has to then figure out everything else. i.e transform a vector of image pixels into a policy for selecting actions 
    -  They leveraged recent breakthroughs in training deep neural networks to show that a novel end-to-end reinforcement learning agent, termed a deep Q-network (DQN) was able to surpass the overall performance of a professional human reference player and all previous agents across a diverse range of 49 game scenarios
    - One Key ingredient is experience replay - where by a network stores a subset of the training data in an instance-based way and then replays it offline, learning anew from successes or failures that occurred in the past. 
    - This work represents the first demonstration of a general-purpose agent that is able to continually adapt its behavior without any human intervention, a major technical step forward in the quest for general AI.


#### AlphaGo:


    - Enormous Search Space and impossible to write evaluation function
    - Top players use intution and insticts rather than calculuation like in chess
        Components:
        
    - Monte Carlo Tree Search (certain variant with PUCT function for tree traversal):https://int8.io/monte-carlo-tree-search-beginners-guide/
    - Residual Convolutional Neural Networks – policy and value network(s) used for game evaluation and move prior probability estimation
    - Policy Network tries  to predict the move that human was going to
    -     play by training on 100k human games downloaded from internet
    - After training it can output probability distribution of possible moves
    - we can look at top 5 moves 
    - trained the second neural network(called the value net) to predict from the current position who is likely to be a winner 
    - trained on the data produced by first network playing against itself many millions of times 
    - Reinforcement learning used for training the network(s) via self-plays

#### AlphaGo Zero: 

    - Latest and greatest version of AlphaGo
    - Fully automated pipeline - No bootstrapping from human data 
    - Starts from completely random play with 'zero knowledge'
    - plays against itself millions of times
    - Learns incrementally from its own mistakes
    - Even Stronger, more efficient and more general

#### Alpha Zero: 

    - Trained on three perfect information games (chess, shogi and Go)
    - Chess engines are highly specialized systems using a whole bag of handcrafted hurrisitics, extensions and domain knowledge
    - Alpha Zero replaces all of that with Self-play reinforcement Learning + Self-Play Monte Carlo Tree Search 
    - No Openbook or endgame database or Heuristics 
    - Starts from random play 
    - Same Algorithm with Same hyperparameters for all 3 games
    - Proof that system is very general and that learning systems could be better than hand-crafted systems

#### Beating Professional Dota 2 Players: 

OpenAI created a bot which beats the world’s top professionals at 1v1 matches of Dota 2 under standard tournament rules. 
“The bot learned the game from scratch by self-play, and does not use imitation learning or tree search. 
This is a step towards building AI systems which accomplish well-defined goals in messy, complicated situations involving real humans.”
 https://blog.openai.com/dota-2/

#### My Project: 
  - [Supporting Knowledge Instensive Processes in Clincial Settings]() 

#### Resources 
  - [Math of RL](https://www.youtube.com/watch?app=desktop&v=LiaEmNToeQA&list=PLTPQEx-31JXhguCush5J7OGnEORofoCW9&index=17&t=0s)
  - [RL Course](https://deepmind.com/learning-resources/-introduction-reinforcement-learning-david-silver)
  - [Reinforcement learning](https://github.com/aikorea/awesome-rl)
  - [Deep Reinforcement Learning](https://spinningup.openai.com/en/latest/)

TODO: add notebooks 

------------------------------------------------------------------------------------------------------------------------
## Process Analytics


### Introduction 
.   
> There have long been a few fundamental challenges associated with business process management. But a relatively new and innovative technology, process mining, has the capability to revitalize process management in firms where it has lain fallow for years. One problem involves the creation of “current state” processes — a description of how a business process is being performed today. In business process reengineering, organizations are primarily interested in an improved “to be” process, so often they have little interest in exploring “as is,” or how the process is currently performed. The other general problem with process management is the lack of connections between business processes and an organization’s enterprise information systems. Enter process mining. Process mining software can help organizations easily capture information from enterprise transaction systems and provides detailed — and data-driven — information about how key processes are performing. It creates event logs as work is done: an order is received, a product is delivered, a payment is made. The logs make visible how computer-mediated work is really happening, including who did it, how long it takes, and how it departs from the average. 
Process analytics create key performance indicators for the process, which enables a company to focus on the priority steps to improve - What Process Mining Is, and Why Companies Should Do It by Thomas H. Davenport and Andrew Spanyi


- [Introduction to Business Process Analytics](https://asjadkhan.ghost.io/business-process-analytics/)
- [Improving Process Efficiency with Process Mining](https://asjadkhan.ghost.io/improving-process-efficincy-with-process-mining/)
- [Case Study: Improving treatment careflow with Process Mining]()

### Projects: 

- [Memory-Augmented Neural Networks for Predictive Process Analytics](https://arxiv.org/abs/1802.00938) 
- [Supporting Knowledge Instensive Processes in Clincial Settings](https://asjadkhan.ghost.io/ghost/#/site) 

resources: 

https://github.com/asjad99/process-analytics 


------------------------------------------------------------------------------------------------------------------------

## Data Engineering 


> a data engineer is someone who has specialized their skills in creating software
solutions around big data.

Before we can do data science we need to setup the infrastructure

![alt text](images/pyramid.png "Logo Title Text 1")

At early stage start-ups: the primary analytic focus is to implement logging, to build ETL processes, to model data and design schemas so data can be tracked and stored. The goal here is focused on building the analytics foundation rather than analysis itself
At mid-stage growing start-ups: Since the company is growing, the data is probably growing too. The data platform needs to adapt, but with the foundation laid out already, there will be a natural shift to insight generation. Unless the company leverages Data Science for its strategic differentiation to start with, many analytics work are around defining KPI, attributing growth, and finding the next opportunities to grow
Companies who achieved scale: When the company scales up, data also scales up. It needs to leverage data to create or maintain competitive edge. e.g. Search results need to be better, recommendations need to be more relevant, logistics or operations need to be more efficient — this is the time where specialist like ML engineers, Optimization experts, Experimentation designers can play a huge role in stepping up the game.

### Data Engineering is concerned with following: 

##### Clean and wrangle data into a usable state

> Data engineers make sure the data the organization is using is clean, reliable, and prepped for whatever use cases may present themselves. 
Data engineers wrangle data into a state that can then have queries run against it by data scientists.

> Data Formats should be easy for computers to parse, people to read and widely used by systems in production. 
The computations we perform must be reproducible and tweakable. Data Pipelines need to be documented. 

##### Build and maintain the organization’s data pipeline systems

> a data pipeline is nothing but a series of operations, when streamed together, helped us to automatically capture, munged, aggregated data on a recurring basis.

> Creating a data pipeline may sound easy or trivial, but at big data scale, this means bringing together 10-30 different big data technologies. 
More importantly, a data engineer is the one who understands and chooses the right tools for the job. 

> A data engineer is the one who understands the various technologies and frameworks in-depth, and how to combine them to create solutions to enable a 
company’s business processes with data pipelines.

read more:
Building Data Pipelines with Python — Katharine Jarmul explains how to build data pipelines and automate workflows.


### Data Models

| Algorithm           | Notes     | 
|---------------------|-----------|
| Relational Data     |           |
| Document Model      |           |
| Graph Model         |           |

### Primer on distributed systems 

Replication
Partitioning
Transactions 
Consistency and Consensus

### Data Ingestion 
### Large-Scale Processing 

| Notebook                 | Description | Code | Blog | 
|--------------------------|-------------|------|------|
| Speeding up Numpy        | Learn how to get optimal performance out of NumPY | | [Notes](https://asjadkhan.ghost.io/speeding-up-numpy/)          |
| Spark Tutorial           | Learn large scale Data Engineering with Spark          |     | [Notes](https://asjadkhan.ghost.io/ghost/#/editor/post/5f39c86010c8da00398dc9ce)     |
| Topic Modeling in Spark  | LSI Modeling in Spark to Extract document topics | [Python_code](https://gist.github.com/asjad99/e87a695df10b0859ee943b8e661f0fc3)  | |
|


 
#### Guides: 
- Batch Processing 
- Stream Processing 

#### Data Storage  
storage engines (e.g. S3, HDFS, HBase, Kudu)

### resources:
- Stanford Data Engineering: 
https://docs.google.com/document/d/1b9iuZiDEGVLHyMmnf6w2y1aN6yWQhAyqk3GHlpI9q6M/edit 
- Designing Data-Intensive Applications
- https://github.com/andkret/Cookbook
- Is dataFrame just a table
- https://www.mikealche.com/software-development/a-humble-guide-to-database-schema-design
- SQL Mastery

------------------------------------------------------------------------------------------------------------------------

## Math for Data Science
Data science rests on a foundation of mathematics, particularly statistics and linear algebra. It is important to
understand this material on an intuitive level: why these concepts were
developed, how they are useful, and when they work best. e.g develop statistical reasoning is a core goal. 


| Algorithm           | Description | Code |
|---------------------|-----------|-------------|
| Sets   |           |             |
| Graph Theory             |           |             |
| Linear Algebra |           |             |
| Probability                |http://www.datasciencecourse.org/notes/probability/            |             |
| Statistics                |           |             |


## Project Management 

Data Science is more than feature engineering, training models. XOR build applications and deploy models. Its involves:

> meeting client, understanding business problem, write code to connect to data sources,
get the data, clean it, set up training environments, train models, set up serving environments, 
deploy models, write the application (web, mobile).

Data Science supports and encourages shifting between deductive (hypothesis-based) and inductive (pattern-based) reasoning. Tis is a fundamental change from traditional analytic approaches. Inductive reasoning and exploratory data analysis provide a means to form or refine hypotheses and discover new analytic paths. In fact, to do the discovery of signifcant insights that are the hallmark of Data Science, you must have the tradecraft and the interplay between inductive and deductive reasoning. By actively combining the ability to reason deductively and inductively, Data Science creates an environment where models of reality no longer need to be static and empirically based. Instead, they are constantly tested, updated and improved until better models are found. These concepts are summarized in the figure, The Types of Reason and Their Role in Data Science Tradecraft.


![alt text](images/img_1.png "Logo Title Text 1")

The diferences between Data Science and traditional analytic approaches do not end at seamless shifting between deductive and inductive reasoning. Data Science offers a distinctly different perspective than capabilities such as Business Intelligence. Data Science should not replace Business Intelligence functions within an organization, however. Te two capabilities are additive and complementary, each offering a necessary view of business operations and the operating environment. Te fgure, Business Intelligence and Data Science – A Comparison, highlights the diferences between the two capabilities. Key contrasts include:
![alt text](images/img_2.png "Logo Title Text 1")


### 
Data Science Projects Pipeline:
    Data Collection → Data Processing → Exploration/visualization → analysis/machine learning → insight/policy decisions 

![alt text](images/img_3.png "Logo Title Text 1")



### Data Science Maturity within an Organization: 


We use the Data Science Maturity Model as a common framework for describing the maturity progression and components that make up a Data Science capability. Tis framework can be applied to an organization’s Data Science capability or even to the maturity of a specifc solution, namely a data product. At each stage of maturity, powerful insight can be gained.

![alt text](images/img_4.png "Logo Title Text 1")
![alt text](images/img_5.png "Logo Title Text 1")


### Building Your Data Science Team: 

A critical component to any Data Science capability is having the right team. 
Data Science depends on a diverse set of skills as shown in Te Data Science Venn Diagram. 
Computers provide the environment in which data-driven hypotheses are tested, and as such, computer science is necessary 
for data manipulation and processing. Mathematics provides the theoretical structure in which Data Science problems are examined. 
A rich background in statistics, geometry, linear algebra, and calculus are all important to understand the basis for many algorithms and tools. 
Finally, domain expertise contributes to an understanding of what problems actually need to be solved, 
what kind of data exists in the domain, and how the problem space may be instrumented and measured.

### Referenes and Further Readings: 

- Field Guide to data science https://wolfpaulus.com/wp-content/uploads/2017/05/field-guide-to-data-science.pdf
- Executive Data Science Specialization
- AI Product manager nanodegree 
- [Creating a data driven organization](https://www.oreilly.com/library/view/creating-a-data-driven/9781492049227/ch04.html)

- [Managing Data Science Teams and Projects](https://www.oreilly.com/library/view/managing-data-science/9781838826321/)
- Interviews: http://treycausey.com/data_science_interviews.html



--------------------------------------------------------------------------------------------------------------------------------------

# Inspiring Data Products

https://github.com/asjad99/data_products 


----------------------------------------------------------------------------------------------------------------------------------------
# Useful datasets 

https://www.kaggle.com/asjad99 
https://github.com/beamandrew/medical-data 



----------------------------------------------------------------------------------------------------------------------------------------

