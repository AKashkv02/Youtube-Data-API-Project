# Youtube-Data-API-Project
Building a python project to scrape YouTube data using  YouTube Data API, I extracted  the data of the best Data Science channels and their channel statistics using youtube data API and analysing the data using Tableau and creating a visualisation dashboard

Tableau Dashboard link: https://public.tableau.com/app/profile/akash.kv/viz/YoutubedatasciencechannelsEDA/Dashboard1

In my data science journey i have come across some of the best youtube channels which posts the data science content

Dataset contains the data of following channels
                       
1                   Luke Barousse
2                 Abhishek Thakur
3           Thu Vu data analytics
4                   Jeremy Howard
5               Satyajit Pattnaik
6                         Chandoo
7                  Data Professor
8                        sqlbelle
9                     Siraj Raval
10                     Krish Naik
11                     Tina Huang
12                   Akshit Madan
13                     codebasics
14                  Bhavesh Bhatt
15                   CodeEmporium
16               Alex The Analyst
17                        CampusX
18                        sentdex
19                        Ken Jee
20    StatQuest with Josh Starmer
21                    Data School
22                  Daniel Bourke
23              E-Learning Bridge
24                     deeplizard
25                  Corey Schafer
26             Shashank Kalanithi
27                  DataInterview
28                  Priyang Bhatt
29               365 Data Science
30               Nicholas Renotte
31                        techTFQ
32            Unfold Data Science
33              Applied AI Course
34                     Data Talks
35                  StrataScratch
36                         Jovian



I have extracted the details like total number of videos ,total views,views per video,number of subscribers,likes and published date and can refer to the dataset i have attached



We start this project by first creating an YouTube API Key which will be our credential to access youtube data. I will should you in detail, how to create an API Key. 
Once the API Key is generated, we will then learn how to use this API key to access different youtube data. I.e. we will walk through the documentation given by google to use youtube API. We will look at the different sections in the documentation to access different data we need to build this project. We will also look at the sample python code given by google to call different resources and methods to fetch youtube data.

Finally, we will get into writing the python code to build this project. I will be using Jupyter Notebook to write my python code. Since it is a new project, we will create a new virtual environment for this project. We will use anaconda for this. Once the virtual environment is set, we will then install all the required python packages. So we will install "google-api-python-client" (which is the google python package required to access youtube api data), we will also install pandas and seaborn. I will show you how to create a virtual environment and also how to install all these packages in detail.

Once our environment is set and required packages are installed, we will then start writing the code in Jupyter Notebook. I have divided this project into 2 parts.
In the first part, we extract channel details from youtube. I.e. we extract details such as youtube channel name, total no of subscribers, total views and total number of videos posted by each channel. We gather these details for few Data Analyst/Data Scientist kind of channel and then compare these channel data with each other. We shall see who has the highest subscriber and who gets the most views and the amount of videos posted by these channels. We will be loading all of this data into a pandas dataframe and then analyze it. We will also generate some basic visualization using this data so we can easily compare these multiple channels.


