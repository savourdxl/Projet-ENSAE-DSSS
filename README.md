# Media Coverage of Climate Change

This repository contains the report, the data and the code used for the project **How is Climate Change covered in French National Newspapers?**.

In this repo, additionally to the report (pdf document), you will find both the code to reproduce our results as well as the resulting dataframes if you want to skip code steps. 
First step is data collection, then a basic analysis (evolution of the attention to climate change per journal) is made; the topic detection code and results can be found in the BerTopic folder, while code and results for the LSTM part are gathered in the LSTM folder.

Basically, you can run the first notebook, save files and use them for running the next notebook and so on, or directly take, for example, the processed data to perform a topic analysis or LSTM.

## Data Collection
The data collection folder contains the articles scrapped, the basic preprocessing (see notebook 'MCCC - creation of datasets') and the resulting datasets.

## Basic Analysis
This folder contains the notebook to perform a basic comparison of attention to climate change between journals.

## BerTopic
This folder contains the notebook used to set up and apply bertopic to our data, as well as the resulting dataframes (articles and their topics - all_docs_topics.csv, themes evolution - all_themes.csv).

## LSTM
This folder contains ... .
