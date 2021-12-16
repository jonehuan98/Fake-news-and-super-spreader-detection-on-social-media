# Fake-news-and-super-spreader-detection-on-social-media

This repository contains the source code for the project: FAKE NEWS DURING THE PANDEMIC: DETECTING AND PREDICTING SUPER SPREADER GROUPS IN SOCIAL MEDIA
## Project description:
As the Covid-19 pandemic has spread at an alarming rate, the propagation of misinformation has been rampant on social media. Misinformation regarding the virus has undermined epidemic prevention and disseminated confusion on a large scale. To tackle this issue, understanding fake news propagation and its potential countermeasures are important to mitigate the negative impact of misinformation.

## Repository description:
The Dataset Construction and Analysis folder contains the notebooks for data collection and data cleaning/analysis based on the given public source raw datasets.
The Classification folder contains the notebooks for Machine Learning, BERT, and LSTM text classification and the datasets.
The Web Application folder contains the web application Python file, template file and styles file for the fake news and super spreader prediction website.

## To run the code (classification):
### Requirements
Python 3.9.6, tensorflow, scikitlearn, pandas, numpy, tensorflow_hub, tensorFlow_text, matplotlib, seaborn, keras
### Instructions
Download the classification folder, and ensure that the two datasets are present on your local machine.  
For all classification files: "BERT Classification.ipynb" for BERT model, "LSTM RNN Classification.ipynb" for LSTM model, and "Machine Learning Classification.ipynb" for machine learning models,  
run the code with the appropriate dataset filename selection:  
For fake news vs real news classification: "fake news dataset.csv"  
For normal news vs Covid-19 news classification: "news categorisation dataset.csv"  
