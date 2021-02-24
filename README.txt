MSc Big Data Management and Analytics Project README 

Student Number - 3014289
Student Name- Subhasree Vadukoot 


The source code for each task is written in python and the web application is created using Django Framework. 

The project consists of :

Zipped file - MSCBD_Project_Subhasree_Vadukoot_3014289 which contains :

WEB APPLICATION:
1. climateproject folder
2. firstapp folder- contains python files 
3. static folder- contains images, css files and JavaScript files. 
4. templates folder- contains all of the HTML files. 
5. climatetweet.csv - CSV file containing the climate change sentiment data. 
6. manage.py
7. pkl files of the dumped classification models.

Tableau data and Workbook:
1. per capita co2 emissions.twb
2. Global ecological footprint. twb 
3. countries.csv
4. co-emissions-per-capita.csv
5. countries.hyper
6. co-emissions-per-capita.hyper

Other files are:
- Thesis documents in word and pdf
- climatetweet.csv file
- Climate Conversations and Visualizations powerpoint
- README.txt files with instructions on how to run


Required Installations

1. Django 
2. MongoDB Compass
3. Pandas
4. Djongo
5. Tweepy
6. Textblob
7. imbalanced learn 
8. image 
9. sklearn
10. Twitter API

To perform the installations e
pip install django
pip install djongo
pip insstall tweepy
pip install textblob
pip install twitter
pip install sklearn
pip install pandas
pip install image
pip install imbalanced-learn


Required downloads

1. Python libraries including stopwords, punkt, wordnet
python -m nltk.downloader stopwords
python -m nltk.downloader punkt
python -m nltk.downloader wordnet
python -m nltk.downloader stopwords
python -m nltk.downloader punkt
python -m nltk.downloader wordnet



JavaScript libraries used
1. amChart, canvasJs, html2canvas

Requirements to run the source code of this project

1. The programs were created in Windows 10 Operating System with Python 3.7 version using Django.
However, the program works well in any operating system since it is platform independent.
2. Tableau workbooks are published using Tableau Server. Hence the workbooks are not required for running the Web Application. 
3. Internet connection is required as weather data is collected from Weather API using Internet. 


A zipped file of all the source codes along with the README file is submitted for grading. 


Motivation:

The project was developed for the requirement of Master's in Big Data Management and Analytics Dissertation. 



Datasets used:

1. climate change sentiment dataset from Kaggle.
The dataset is owned by Canada Foundation for Innovation JELF Grant to Chris Bauch, University of Waterloo.
https://www.kaggle.com/edqian/twitter-climate-change-sentiment-dataset

Datasets used to create Tableau workbook

1. Global Ecological Footprint
https://www.kaggle.com/footprintnetwork/ecological-footprint

2. CO₂ and Greenhouse Gas Emissions
https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions



TEST 

To run the program, go to command prompt and cd to the Project Files directory.

Enter:

> python manage.py runserver

Then go to localhost:8000 in a browser of your choice. 



In case you want to see the algorithm report in command line, go to Project files>firstapp>views.py and uncomment the 5 method calls in home().
However, this report is already part of the home page of the User interface.
