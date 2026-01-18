# Personalization of clinical decision support based on the analysis of semi-structured information from electronic medical records
Educational Program: Big Data and Machine Learning</br>
Major: 01.04.02 Applied Mathematics and Informatics</br>
Faculty: Artificial Intelligence Technologies</br>
ITMO University</br>
Student: Emil Gaibaliev, J4233</br>
Supervisor: Sergey Kovalchuk, PhD</br>
St. Petersburg, 2025</br>

This repository contains the code, notebooks, and materials for the master’s thesis focused on developing an automated pipeline for analyzing semi-structured text from Electronic Medical Records (EMRs) to support personalized clinical decision-making.

Files discription:</br>

ResearchWorkAlmazov - stands for EDA of received data from ALmazov National Medical Research Centre. Of most interest was the fact that there was a recommendation for patients to keep a diary for self-monitoring of blood pressure.</br>

ResearchWorkPreprocessingAlmazov - a file with pre-processing of the main text field with general recommendations from the doctor.</br>

ResearchWorkAlmazovClustering - a file with the basic algorithm for working with already processed text data. At this stage, topic modeling is performed, and then records within each topic are clustered using the DBSCAN algorithm.</br>
