# Basic Prediction Web App
## What is this?
When a data scientist/machine learning engineer develops a machine learning model using Scikit-Learn, TensorFlow, Keras, PyTorch etc, the ultimate goal is to make it available in production. Often times when working on a machine learning project, we focus a lot on Exploratory Data Analysis(EDA), Feature Engineering, tweaking with hyper-parameters etc. But we tend to forget our main goal, which is to extract real value from the model predictions.
Deployment of machine learning models or putting models into production means making your models available to the end users or systems. However, there is complexity in the deployment of machine learning models. This repo aims to make you get started with putting your trained machine learning models into production using Flask API.

## About Data and Web App
In this repo data from 80,000 UFO sightings, gathered by NUFORC (The National UFO Reporting Center) was used. This data has some interesting descriptions of UFO sightings, for example:

* **Long example description.** "A man emerges from a beam of light that shines on a grassy field at night and he runs towards the Texas Instruments parking lot".
* **Short example description.** "the lights chased us".
The `ufos.csv` spreadsheet includes columns about the city, state and country where the sighting occurred, the object's shape and its latitude and longitude.

Seconds, Latitude and Longitude were selected the three features we want to train on as the X vector, and the y vector is the Country. 

On the website you can put three inputs (Seconds, Latitude and Longitude) and get which country is it from to return as a prediction.
## Environment and tools
1. scikit-learn
2. pandas
3. numpy
4. flask

## How to use

1. Clone this repo:

`git clone https://github.com/turhancan97/Basic-Prediction-Web-App`

2. Now, open command prompt run this file by navigating to web-app:

`cd web-app`

3. In your terminal type pip install, to install the libraries listed in requirements.txt:

`pip install -r requirements.txt`

4. Open `notebook.ipynb` with jupyter notebook or VSCode and run all

5. run app python file at cmd to start local web server 

`python app.py`

6. Open `http://127.0.0.1:5000/` in your web-browser, and the GUI as shown below should appear.

![app](https://user-images.githubusercontent.com/22428774/141831612-0a413b65-f279-4a1f-acd2-26e73439aa44.PNG)
