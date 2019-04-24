This repo reltes to the Spring-2019 session of the Open Machine Learning Course (https://mlcourse.ai)

# Course roadmap

### Plan
- Calendar and deadlines
- Assignments
- Kaggle Inclass Competition “Alice”
- Kaggle Inclass Competition “Medium”
- Kaggle Inclass Competition “DOTA 2 winner prediction”
- Tutorials


### Calendar and deadlines
[Google Calendar](https://calendar.google.com/calendar?cid=Z25pZ3EwZGxxb2I5cDZwMWptam5rdmY3NWtAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ) with all deadlines.
Current deadlines (see also the assignments page):
- February 24 - A1
- March 10 - A2
- March 17 - uploading solutions to Alice & Medium
- Macrh 31 - A3
- April 7 - A4
- April 21 - DOTA 2 competition
- April 23 - uploading solutions to DOTA 2
- April 24 - publishing tutorials

### Assignments
Assignments are announced in the #mlcourse_ai channel in ODS Slack team (pinned items). Also, links to fresh assignments are provided in the Readme file of the course repository and on mlcourse.ai/assignments. Deadlines are typically on Sundays, 20:59 UTC. Apart from that, you can practice with demo assignments, don’t confuse them with “real” ones. Rough plan for spring 2019 assignments is the following:
- A1. Pandas and exploratory data analysis
- A2. Beating baselines in Alice & Medium competitions
- A3. Decision trees, random forest, and gradient boosting. Beating baseline in the “flight delays” competition
- A4. Time series analysis with Python

If stuck with assignments, check course video lectures.

### Kaggle Inclass Competition “Alice”
In the 1st competition you’ll be solving a task of user identification using tracking of his/her visited websites. Let’s call this competition “Alice”, because we’ll be classifying whether a person is Alice (let’s say, intruder) or somebody else (innocent users). The competition is held in cooperation with Yandex and MIPT specialization “Machine Learning and Data Analysis” (in Russian).

Rules:
- Deadline for submissions: 2019 March 10th
- You can make maximum 5 submissions a day, and the competition is individual (that is, 1 person per team, team merges are not allowed)
- In case you want to get credits, you need to rename your team (of 1 person) in full accordance with your name in the course rating
- if you overfitted and plunged several positions down on the private LB - no offense, it’s life. Only private LB is used to calculate final credits (that’s not true for baselines in A2, check instructions therein)
- Till March 17th, those who managed to beat all benchmarks must upload their reproducible solutions in the .py format (python script) here, more details are provided in this post (dated March 5th) in the #mlcourse_ai_news channel
- The results of the competition and the final course rating will be published on 2019 April 26th.

Scoring rules for competitions (Alice & Medium):
Necessary conditions:
- Beat all Yorko’s baselines on the private LB
- A reproducible solution must be submitted within the specified period
- Team name must exactly correspond to the name in the course rating


### Kaggle Inclass Competition “Medium”
Kaggle Inclass. Here you are proposed to predict popularity (number of claps) of an article on Medium.com. Rules are the same as for “Alice” competition, only the webform for uploading solutions .py files is different.


### Kaggle Inclass Competition “DOTA 2 winner prediction”
In the 3rd competition you are going to utilize all knowledge and skills acquired during the course session.
Rules:
- Deadline for submissions: 2019 April 21st, 20:59 UTC
- Teams up to 4 people are allowed.
- Instructions on team naming and uploading your solutions are given in this post on Kaggle
- The results of the competition and the final course rating will be published on 2019 April 26th.


### Tutorials
We propose to write and publish a tutorial on any ML/DS-related topic which is not fully covered in our course. Some exemplar topics are given in a template, but you can choose any new one.
Rules:
- Tutorials must be written in English. As for programming language, only Python is allowed
- It must be a tutorial (reproducible Jupyter notebook, actually, a Kaggle Kernel, see “how to publish” below), i.e you shall teach some skills, do not just express your ideas on some theoretical concept
- It is not just a translation of somebody else’s material. You can borrow some stuff, but with fair links/citations
- The prerequisite for reading your tutorial should be basic ML as taught in mlcourse.ai. Do not write in-depth articles about neural nets, probabilistic programming, Bayesian approach, reinforcement learning etc. - topics like these need a thorough approach. That is, sure, you can write articles like that, but not in the format of mlcourse.ai tutorials. On the other hand, it’s hardly worth making a tutorial too simple (e.g., to pick some library and demonstrate only a couple of methods from it)
- A typical tutorial shall be 30-60 minutes to read and digest (however, here exceptions are possible)
- Check out these lists of published tutorials from previous runs of this course: English, Russian . Yes, the second list is in Russian but still Google Translate can kind of give you an insight into the topics that are already covered. For those who already passed the course: definitely, translating somebody else’s (or your own) tutorial into English is not going to work
- Tutorial submission is due on 2019 April 24

How to publish a tutorial
1.	First of all, choose a unique topic and registered it in the Google doc
2.	Create a Kaggle Kernel with your tutorial here (and of course do upvote all kernels that you find useful)
3.	Make sure your Kernel runs normally and produces no errors
4.	Then share the link to your Kernel in the #mlcourse_ai Slack channel with a short description of the tutorial. You also need to add the #tutorial tag, It’s obligatory, otherwise, the tutorial will be ignored.
For discussions, please stick to ODS Slack, channel #mlcourse_ai, pinned thread #tutorial.

Grading tutorials
Grading is solely done by other participants upvoting Kernels on Kaggle in the mlcourse.ai Kaggle Dataset. Best tutorials will get up to 40 credits. The exact grading formula is to be provided later. Voting is finalised on 2019 April 26th.


# Outline
This is the list of published articles on medium.com [:uk:](https://medium.com/open-machine-learning-course), habr.com [:ru:](https://habr.com/company/ods/blog/344044/), and jqr.com [:cn:](https://www.jqr.com). Icons are clickable. Also, links to Kaggle Kernels (in English) are given. This way one can reproduce everything without installing a single package.  
1. Exploratory Data Analysis with Pandas [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-1-exploratory-data-analysis-with-pandas-de57880f1a68)  [:ru:](https://habrahabr.ru/company/ods/blog/322626/) [:cn:](https://www.jqr.com/article/000079), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/topic-1-exploratory-data-analysis-with-pandas)
2. Visual Data Analysis with Python [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-2-visual-data-analysis-in-python-846b989675cd)  [:ru:](https://habrahabr.ru/company/ods/blog/323210/) [:cn:](https://www.jqr.com/article/000086), Kaggle Kernels: [part1](https://www.kaggle.com/kashnitsky/topic-2-visual-data-analysis-in-python), [part2](https://www.kaggle.com/kashnitsky/topic-2-part-2-seaborn-and-plotly)
3. Classification, Decision Trees and k Nearest Neighbors [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-3-classification-decision-trees-and-k-nearest-neighbors-8613c6b6d2cd) [:ru:](https://habrahabr.ru/company/ods/blog/322534/) [:cn:](https://www.jqr.com/article/000139), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/topic-3-decision-trees-and-knn)
4. Linear Classification and Regression [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-4-linear-classification-and-regression-44a41b9b5220) [:ru:](https://habrahabr.ru/company/ods/blog/323890/) [:cn:](https://www.jqr.com/article/000175), Kaggle Kernels: [part1](https://www.kaggle.com/kashnitsky/topic-4-linear-models-part-1-ols), [part2](https://www.kaggle.com/kashnitsky/topic-4-linear-models-part-2-classification), [part3](https://www.kaggle.com/kashnitsky/topic-4-linear-models-part-3-regularization), [part4](https://www.kaggle.com/kashnitsky/topic-4-linear-models-part-4-more-of-logit), [part5](https://www.kaggle.com/kashnitsky/topic-4-linear-models-part-5-validation)
5. Bagging and Random Forest [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-5-ensembles-of-algorithms-and-random-forest-8e05246cbba7) [:ru:](https://habrahabr.ru/company/ods/blog/324402/) [:cn:](https://www.jqr.com/article/000241), Kaggle Kernels: [part1](https://www.kaggle.com/kashnitsky/topic-5-ensembles-part-1-bagging), [part2](https://www.kaggle.com/kashnitsky/topic-5-ensembles-part-2-random-forest), [part3](https://www.kaggle.com/kashnitsky/topic-5-ensembles-part-3-feature-importance)
6. Feature Engineering and Feature Selection [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-6-feature-engineering-and-feature-selection-8b94f870706a) [:ru:](https://habrahabr.ru/company/ods/blog/325422/) [:cn:](https://www.jqr.com/article/000249), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/topic-6-feature-engineering-and-feature-selection)
7. Unsupervised Learning: Principal Component Analysis and Clustering [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-7-unsupervised-learning-pca-and-clustering-db7879568417) [:ru:](https://habrahabr.ru/company/ods/blog/325654/) [:cn:](https://www.jqr.com/article/000336), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/topic-7-unsupervised-learning-pca-and-clustering)
8. Vowpal Wabbit: Learning with Gigabytes of Data [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-8-vowpal-wabbit-fast-learning-with-gigabytes-of-data-60f750086237) [:ru:](https://habrahabr.ru/company/ods/blog/326418/) [:cn:](https://www.jqr.com/article/000348), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/topic-8-online-learning-and-vowpal-wabbit)
9. Time Series Analysis with Python, part 1 [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-9-time-series-analysis-in-python-a270cb05e0b3) [:ru:](https://habrahabr.ru/company/ods/blog/327242/) [:cn:](https://www.jqr.com/article/000450). Predicting future with Facebook Prophet, part 2 [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-9-part-3-predicting-the-future-with-facebook-prophet-3f3af145cdc), [:cn:](https://www.jqr.com/article/000598) Kaggle Kernels: [part1](https://www.kaggle.com/kashnitsky/topic-9-part-1-time-series-analysis-in-python), [part2](https://www.kaggle.com/kashnitsky/topic-9-part-2-time-series-with-facebook-prophet)
10. Gradient Boosting [:uk:](https://medium.com/open-machine-learning-course/open-machine-learning-course-topic-10-gradient-boosting-c751538131ac) [:ru:](https://habrahabr.ru/company/ods/blog/327250/), [:cn:](https://www.jqr.com/article/000573), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/topic-10-gradient-boosting)

### Lectures
Videolectures are uploaded to [this](https://bit.ly/2zY6Xe2) YouTube playlist.
Introduction, [video](https://youtu.be/QKTuw4PNOsU), [slides](https://bit.ly/2NuadRV)

1. Exploratory data analysis with Pandas, [video](https://youtu.be/fwWCw_cE5aI)
2. Visualization, main plots for EDA, [video](https://www.youtube.com/watch?v=WNoQTNOME5g)
3. Decision trees: [theory](https://youtu.be/H4XlBTPv5rQ) and [practical part](https://youtu.be/RrVYO6Td9Js)
4. Logistic regression: [theoretical foundations](https://www.youtube.com/watch?v=l3jiw-N544s), [practical part](https://www.youtube.com/watch?v=7o0SWgY89i8) (baselines in the "Alice" competition)
5. Emsembles and Random Forest – [part 1](https://www.youtube.com/watch?v=neXJL-AqI_c). Classification metrics – [part 2](https://www.youtube.com/watch?v=aBOMYqGUlWQ). Example of a business task, predicting a customer payment – [part 3](https://www.youtube.com/watch?v=FmKU-1LZGoE) 
6. Linear regression and regularization - [theory](https://youtu.be/ne-MfRfYs_c), LASSO & Ridge, LTV prediction - [practice](https://youtu.be/B8yIaIEMyIc)
7. Unsupervised learning - [Principal Component Analysis](https://youtu.be/-AswHf7h0I4) and [Clustering](https://youtu.be/eVplCo-w4XE)
8. Stochastic Gradient Descent for classification and regression - [part 1](https://youtu.be/EUSXbdzaQE8), part 2 TBA
9. Time series analysis with Python (ARIMA, Prophet) - [video](https://youtu.be/_9lBwXnbOd8)
10. Gradient boosting: basic ideas - [part 1](https://youtu.be/g0ZOtzZqdqk), key ideas behind Xgboost, LightGBM, and CatBoost + practice - [part 2](https://youtu.be/V5158Oug4W8)

### Spring 2019 assignments
1. Exploratory Data Analysis (EDA) of US flights, [nbviewer](https://nbviewer.jupyter.org/github/Yorko/mlcourse.ai/blob/master/jupyter_english/assignments_spring2019/assignment1_USA_flights_EDA.ipynb?flush_cache=true). Deadline: **February 24, 20:59 GMT**
2. In Assignment 2, you'll be beating baselines in first two competitions:
    - Part 1. User Identification with Logistic Regression (beating baselines in the "Alice" competition), [nbviewer](https://nbviewer.jupyter.org/github/Yorko/mlcourse.ai/blob/master/jupyter_english/assignments_spring2019/assignment2_part1_alice_logistic_regression.ipynb?flush_cache=true). Deadline: **March 10, 20:59 GMT**
    - Part 2. Predicting Medium articles popularity with Ridge Regression (beating baselines in the "Medium" competition), [nbviewer](https://nbviewer.jupyter.org/github/Yorko/mlcourse.ai/blob/master/jupyter_english/assignments_spring2019/assignment2_part2_medium_beat_baselines.ipynb?flush_cache=true). Deadline: **March 10, 20:59 GMT**
3. Decision trees, Random Forest, and gradient boosting. Deadline: **March 31, 20:59 GMT**
    - Part 1. "Decision trees for classification and regression", [nbviewer](https://nbviewer.jupyter.org/github/Yorko/mlcourse_open/blob/master/jupyter_english/assignments_spring2019/assignment3_part1_decision_trees.ipynb?flush_cache=true)
    - Part 2. "Random Forest and Logistic Regression in credit scoring and movie reviews classification", [nbviewer](https://nbviewer.jupyter.org/github/Yorko/mlcourse_open/blob/master/jupyter_english/assignments_spring2019/assignment3_part2_rf_logit_scoring_texts.ipynb?flush_cache=true)
    - Part 3. "Flight delays" competition, [Kernel](https://www.kaggle.com/kashnitsky/mlcourse-ai-assignment-3-starter) starter
4. Time series analysis, [nbviewer](https://nbviewer.jupyter.org/github/Yorko/mlcourse_open/blob/master/jupyter_english/assignments_spring2019/assignment4_time_series.ipynb?flush_cache=true). Deadline: **April 7, 20:59 GMT**
    
### Demo assignments, just for practice
The following are demo versions. Full versions are announced during course sessions.  
1. Exploratory data analysis with Pandas, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment01_pandas_uci_adult.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-1-pandas-and-uci-adult-dataset), [solution](https://www.kaggle.com/kashnitsky/a1-demo-pandas-and-uci-adult-dataset-solution)
2. Analyzing cardiovascular disease data, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment02_analyzing_cardiovascular_desease_data.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-2-analyzing-cardiovascular-data), [solution](https://www.kaggle.com/kashnitsky/a2-demo-analyzing-cardiovascular-data-solution)
3. Decision trees with a toy task and the UCI Adult dataset, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment03_decision_trees.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-3-decision-trees), [solution](https://www.kaggle.com/kashnitsky/a3-demo-decision-trees-solution)
4. Sarcasm detection, [Kaggle Kernel](https://www.kaggle.com/kashnitsky/a4-demo-sarcasm-detection-with-logit), [solution](https://www.kaggle.com/kashnitsky/a4-demo-sarcasm-detection-with-logit-solution). Linear Regression as an optimization problem, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment04_linreg_optimization.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-4-linear-regression-as-optimization)
5. Logistic Regression and Random Forest in the credit scoring problem, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment05_logit_rf_credit_scoring.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-5-logit-and-rf-for-credit-scoring)
6. Exploring OLS, Lasso and Random Forest in a regression task, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment06_regression_wine.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-6-linear-models-and-rf-for-regression), [solution](https://www.kaggle.com/kashnitsky/a6-demo-regression-solution)
7. Unsupervised learning, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment07_unsupervised_learning.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-7-unupervised-learning)
8. Implementing online regressor, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment08_implement_sgd_regressor.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-8-implementing-online-regressor), [solution](https://www.kaggle.com/kashnitsky/a8-demo-implementing-online-regressor-solution)
9. Time series analysis, [nbviewer](https://mlcourse.ai/notebooks/blob/master/jupyter_english/assignments_demo/assignment09_time_series.ipynb?flush_cache=true), [Kaggle Kernel](https://www.kaggle.com/kashnitsky/assignment-9-time-series-analysis), [solution](https://www.kaggle.com/kashnitsky/a9-demo-time-series-analysis-solution)
10. Beating baseline in a competition, [Kaggle kernel](https://www.kaggle.com/kashnitsky/assignment-10-gradient-boosting-and-flight-delays)

### Kaggle competitions
1. Catch Me If You Can: Intruder Detection through Webpage Session Tracking. [Kaggle Inclass](https://www.kaggle.com/c/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2)
2. How good is your Medium article? [Kaggle Inclass](https://www.kaggle.com/c/how-good-is-your-medium-article/)
3. DotA 2 winner prediction [Kaggle Inclass](https://www.kaggle.com/c/mlcourse-dota2-win-prediction)


### Community
Discussions between students are held in the **#mlcourse_ai** channel of the OpenDataScience Slack team. Fill in [this form](https://docs.google.com/forms/d/10HAN5huM996snUKjsNYyT_oOlm2uOsTKulKurb3oiNM/) to get an invitation closer to the start of a new session.

*The course is free but you can support organizers by making a pledge on [Patreon](https://www.patreon.com/ods_mlcourse) (monthly support) or a one-time payment on [Ko-fi](https://ko-fi.com/mlcourse_ai). Thus you'll foster the spread of Machine Learning in the world!*
