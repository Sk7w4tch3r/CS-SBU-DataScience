---
layout: default
title: Assignments
---
# Assignment 1
- Due Date: 1400/08/02 12PM
- Points: 2.5/20

## Statistical Analysis
This assignment consists of two tasks. In each task, a dataset is given. Use [descriptive statistics](https://en.wikipedia.org/wiki/Descriptive_statistics) and [inferential statistics](https://en.wikipedia.org/wiki/Statistical_inference) to write a report about that dataset. For inspiration, some questions are given, but an essential part of this assignment is your posed questions. Apply various yet proper statistical tests and analyses to answer them.


### Task 1: Airbnb
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. This dataset describes the listing activity and metrics in NYC.
#### Download: 
- [New York City Airbnb Open Data 2019 (Kaggle)](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)

Also you can download new data from [insideairbnb.com](http://insideairbnb.com/get-the-data.html) which have more columns to work with. 
#### Questions
- What can we learn about different hosts and areas?
- What can we learn from predictions? (ex: locations, prices, reviews, etc) 
- Which hosts are the busiest and why?
- Is there any noticeable difference in traffic among different areas and what could be the reason for it?

### Task 2: Crime Reports 

A bitter truth, crimes do exist. Collecting data about crimes and analyzing them may lead us to their underlying cause. *FBI NIBRS* is a rich database that captures details on each single crime incident.

#### Donwload:

From the Louisville government's [website](https://data.louisvilleky.gov/dataset/crime-reports) download five consecutive yearly datasets.
#### Questions
- Which crimes are most common?
- In which zip codes are crimes more likely to occur?
- Is there a trend of some crimes increasing and others decreasing in number over these five years?
- Which crimes take the longest to report?

## Update
Sample submissions for this assignment are available [here](https://github.com/Sk7w4tch3r/CS-SBU-DataScience/tree/main/assignments/A1/Sample%20Report).

****

__You should consider new additional creative questions for both tasks and answer them with proper statistical tests. Each task should have its report and IPython Notebook. Once again, we emphasize the report; it should contain all your questions and your proper statistical answers. Use figures, pictures, and tables. DO NOT PUT ANY CODE IN THE REPORT.__

# Assignment 2
- Due Date: 1400/08/28 12PM
- Points: 2.5/20

## EDA & Data Visualization
This assignment needs you to be as creative and curious as you can! Unfortunately, our lives have been deeply affected by the corona virus over these past two years. An important goal of data mining is to understand the patterns and trends in the data and extract knowledge and facts from the raw data. It is clear that with the proper analysis and insightful knowledge of the data, we can make better decisions and inform societeies so we can get past this pandemic.<br><br>
In this assignment you will be tasked to first clean the data, e.g. remove the outliers and null values properly, and then perform EDA on the data. Your work will be graded based on the quality of the cleaned data, insightful visualizations, and the distilled knowledge that it represents. (to obtain additional visualization ideas visit [here](https://ourworldindata.org/coronavirus))


### Covid-19 Dataset
This assignment dataset is provided by the generous "*Our World in Data*", a.k.a [owid](https://ourworldindata.org/coronavirus-data), which is an online scientific publication that focuses on large global problems such as poverty, disease, hunger, climate change, war, existential risks, and inequality. The dataset is updated daily, and contains data on the global spread of coronavirus (COVID-19), such as number of confirmed cases, deaths, hospitalizations, and tests performed.
#### Download: 
- The dataset is available in [CSV](https://github.com/owid/covid-19-data/tree/master/public/data/owid-covid-data.csv), [JSON](https://github.com/owid/covid-19-data/tree/master/public/data/owid-covid-data.json), and [Excel](https://github.com/owid/covid-19-data/tree/master/public/data/owid-covid-data.xlsx). 

For further information, please refer to the [documentation](https://github.com/owid/covid-19-data/tree/master/public/data) of the dataset.

## Update
Sample submission for this assignment is available [here](https://github.com/Sk7w4tch3r/CS-SBU-DataScience/tree/main/assignments/A2).

****
__You should consider new additional creative questions for assigned tasks and answer them with proper methods. Each task should have its report and IPython Notebook. Once again, we emphasize the report; it should contain all your questions and your innovative findings. Use figures, pictures, and tables, and DO NOT PUT ANY CODE IN THE REPORT.__


# Assignment 3
- Due Date: 1400/09/19 12PM
- Points: 3/20

# Clustering
In this assignment you have to perform clustering on the spotify dataset and develop a recommendation system for the users. You will be given a dataset of songs and their features like danceability, energy, etc. You will be asked to perform clustering on the dataset and then recommend songs to the users based on the clusters. 


# Task: Music Recommendation System
In this assignment your submission should contain a the main python code file, [`musicRecommender.py`](../assignments/A3/musicRecommender.py), you may use notebooks for your experiments but the main interface to your work should be from the main python code file. It takes the path to user preferences (a csv file) and outputs: 

- 5 csv files, each containing the top 5 songs for each user. Musics from each playlist should be sampled from the same cluster.
- A single playlist file containing all the songs recommended to the users. It is not important how the songs are sampled from the clusters.

In your report, you should specify the following:

- Preprocessing steps you used to clean the data.
- Similarity measures you used, or defined, to find the clusters.
- The number of clusters you used and the logic behind it.

Note: for the music preferences, the input file, you can simply sample  or you can create your own from your favorite songs.

# Be Bold!

If you're more of a programmer:
- Use your trained model and call [spotify API](https://developer.spotify.com/discover/) to get your recommendations for the users. If you have previous experience with webservices, and web development, you can develop a web interface for the recommendation system you've trained. It is possible to use the template projects for spotify website from github or other sources, or you can develop your own.

(+1.5 point)

Or, if you're more of a ML/DL researcher:

If you choose to do this, please contact us beforehand.)
- First read this article on arXiv, [here](https://arxiv.org/pdf/1901.04555.pdf).
- Use the `artist20` dataset provided by colombia university ([dataset homepage](http://labrosa.ee.columbia.edu/projects/artistid/)), to develop a more general recommendation system. In this way you can train a general, robust recommendation system that will perform relatively well on any new given music file.
The different data sets are:

    - artist20-mp3s-32k.tgz (1.3GB) - the 32 kbps mono mp3 audio files
    - artist20-mfccs.tgz (1.6GB) - precalculated 20 dimensional MFCCs at 10ms hops
    - artist20-chromftrs.tgz (122MB) - per-tatum 12 dimensional chroma vectors

Note: This research task is a line of research on its own, and has the potential of possible publication if done properly.

(+4 points)
<!-- [dataset](http://labrosa.ee.columbia.edu/projects/artistid/download/) -->


## Dataset
The full list of genres included in the CSV are Trap, Techno, Techhouse, Trance, Psytrance, Dark Trap, DnB (drums and bass), Hardstyle, Underground Rap, Trap Metal, Emo, Rap, RnB, Pop and Hiphop. 

**You can find description of each feature in the [dataset](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features).**

## Download
You can find the dataset on the kaggle website, this dataset consists of four csv files. The first file is the song features, the second file is the song metadata, the third file is the user playlist, and the fourth file is the user metadata. Here is the link to the dataset: [Spotify Dataset](https://www.kaggle.com/mrmorj/dataset-of-songs-in-spotify)

****
__Since there is no common criterion to properly evaluate your work, you should explain the methods and techniques you used to cluster the songs; and explain your rating, or any other logic, behind your recommendation system. Use figures, pictures, and tables, and DO NOT PUT ANY CODE IN THE REPORT.__


# Assignment 4
- Due Date: 1400/10/10 12PM
- Points: 4/20

## Supervised Learning
You can find the assignment instructions [here](../assignments/A4/Assignment 4.pdf).

## Implementation
The code skeleton for this assignment is provided [here](https://github.com/Sk7w4tch3r/CS-SBU-DataScience/tree/main/assignments/A4) and also you can find the requiered datasets from [here](https://github.com/Sk7w4tch3r/CS-SBU-DataScience/tree/main/assignments/A4/data/).
<<<<<<< HEAD


# Assignment 5
- Due Date: 1400/11/05 12PM
- Points: 3/20

## Optimization Algorithms
You can find the assignment instructions [here](../assignments/A5/Assignment 5.pdf).

## Implementation
The template code for this assignment is provided [here](https://github.com/Sk7w4tch3r/CS-SBU-DataScience/tree/main/assignments/A5).
=======
