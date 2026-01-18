# Personalization of clinical decision support based on the analysis of semi-structured information from electronic medical records
Educational Program: Big Data and Machine Learning
Major: 01.04.02 Applied Mathematics and Informatics
Faculty: Artificial Intelligence Technologies
ITMO University
Student: Emil Gaibaliev, J4233
Supervisor: Sergey Kovalchuk, PhD
St. Petersburg, 2025

This repository contains the code, notebooks, and materials for the master’s thesis focused on developing an automated pipeline for analyzing semi-structured text from Electronic Medical Records (EMRs) to support personalized clinical decision-making.

Files discription.
ResearchWorkAlmazov - stands for EDA of received data from ALmazov National Medical Research Centre. Of most interest was the fact that there was a recommendation for patients to keep a diary for self-monitoring of blood pressure.
ResearchWorkPreprocessingAlmazov - a file with pre-processing of the main text field with general recommendations from the doctor.
ResearchWorkAlmazovClustering - a file with the basic algorithm for working with already processed text data. At this stage, topic modeling is performed, and then records within each topic are clustered using the DBSCAN algorithm.
