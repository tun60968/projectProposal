# Congressional Text Extraction, Classification, and Analysis using Python's NLTK Library and the Twitter API

# Abstract
This project aims to leverage natural language processing tools to perform a statistical analysis of congressional tweets. Through the combination of observations regarding reoccuring strings and recorded qualities, data can be processed via textual extraction, classification, and analysis mechanisms contained within the aforementioned NLTK library.
Sentiment analysis and topic analysis can be acheived through text classification, while text extraction can be utilized in the form of named entity recognition, which provides potential for the acknowledgement of frequential correlations between congress members and their Twitter account content. This data can be stored in a relational database such as MSSQL or MySQL. 

# Relevance
The following components are both a topic of this course and modular aspects of the proposed project:
Object-oriented design - A UML (Unified Modeling Language) diagram has been created to delineate the relationships between various entities of our object-oriented program (See Abstract).
Test-driven development - The proposed project supports test-driven development as a means of ensuring code maintainability. It is suggested to utilize this learned approach, as it will effectually increase the efficiency of collaboration.
Unified Modeling Language - See first component listed.
Design patterns - To enlist the robustness of "coding to an interface", the Strategy design pattern is depicted as an integral part of the UML design.
Graphical user interface - With a project of this nature, effective data visualization is a substantial portion of its feasibility. Python has numerous libraries that can be leveraged to present a thorough statistical analysis. Additionally, graph theory concepts can be implemented manually to show relational frequencies (e.g., weighted edges connecting nodes representing congress members - each edge depicting the rate of mention between one congress member and another).
Access to database - Accessing a database is paramount in allowing for effective and persistent data storage, particularly when concerned with derived attributes or data. To this effect, the source code, written in Python, will make use of a MSSQL or MySQL database.

# Conceptual Design
![image](https://user-images.githubusercontent.com/89652481/133833431-e73bf8f0-f139-433f-83d7-0bfacd182eb2.png)
Featured above, the constructed diagram displays an overview of the processing of components within the proposed project. It should be noted, however, that a Twitter developer account will need to undergo the process of attaining access to the Twitter API - a task that I have already completed prior to the formation of this document.
Given a team of four members, it would be advised to have the following arrangement of responsibilities:
Person 1 - Accessing Twitter API through Python (https://github.com/twitterdev/search-tweets-python), Accessing tweets conducted by congressional members, extraction of tweets into well-documented format for text files (https://ucsd.libguides.com/congress_twitter/home)
Person 2 - Construction of database, inclusion of custom queries that support statistical inquiries of group members (https://ucsd.libguides.com/congress_twitter/home)
Person 3 - Use of Python's NLTK library to perform congressional text classification and analysis (https://www.nltk.org/); this role is dependent upon the success of Person 1 in proper extraction of tweets. It is advisable, although not required, that Person 2 has designed and implemented the database prior to Person 3 performing their task, as a completed database will make this task much clearer and executable.
Person 4 - Responsible for brainstorming, documenting, and sharing data visualization techniques and ideas in detail. As soon as the data becomes available, Person 4 should begin constructing necessary visualizations. Person 4 may use their own discretion in the determination of tools and technologies used to perform their task. Person 4 is responsible for composing a list of questions that we want to answer regarding congressional members and their Twitter content.

# Background
The following link provides a small yet relatable demonstration of the Python NLTK library:
https://github.com/westbenj2020/presidential-analysis/blob/main/test.py

# Requirements
At least four group members are required for an adequate execution of the proposed project.
The following tools and technologies are required for the execution of the proposed project:
- Supported version of Python
- Appropriate libraries:
    from __future__ import division
    import csv
    import matplotlib
    from matplotlib import pylab
    from bs4 import BeautifulSoup
    import nltk, re, pprint
    #  nltk.download()
    from nltk import word_tokenize
    from urllib import request 
- MyMSQL or MSSQL database 
- Twitter developer account with API access  
