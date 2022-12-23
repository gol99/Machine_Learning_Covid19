# Machine Learning COVID-19
## Goal
The goal of this project is to build a Machine Learning Algortihm that predicts COVID-19 Cases based on weather data. With this I want to find out wether weather is a good predictor for COVID-19 and more specifically how good of a predictor weather is for COVID-19 cases. The goal is **not** to build the best algorithm to predict case numbers (for that I would have used different data) but to predict case numbers based on the weather and to see how good this works.

## Data used
For this project I used data from two datasets I found on kaggle (https://www.kaggle.com/kimjihoo/coronavirusdataset). The datasets are about COVID-19 in South Korea in the period till 30/06/2020. The first dataset *TimeProvince.csv* contains data about daily case numbers in different South Korean provinces. The second dataset *Weather.csv* contains different weather measurements for the provinces in the first dataset.

## Machine Learning Methods
The Machine Learning model used in this project is **Random Forest**. This is a supervised learning method. The conceptual idea behind a Random Forest will be explained in great detail in the Jupyter Notebook.

## Programming Language
The programming language used in this proect is Python. The code was written in a Jupyter Notebook using Anaconda.
 
## Packages needed
- pandas
- sklearn
- numpy
- matplotlib
- pydot

## How to run?
If you want to run this project you need to do following steps:
1. Donwload the project from github as a zip file and open it on your own device. Make sure that all files are in the **same** directory/folder. After opening the zip file you should have a folder that looks like this:
![](Images/Depository.png)
2. Run the juypyter notebook *Machince_Learning_Covid19.ipynb*. You can run it in wathever environment you like in which you can run a jupyter notebook. If you don't already have an environment to run the juypter notebook, I'll explain how you can install one under *Installation*
3. To best understand the code, you shoul run it cell by cell. I provide all the information you need to understand what the code does and you need to run it in the jupyter notebook.

## Installation

- Step 1: Download and Install Anaconda (https://www.anaconda.com/download/) - preinstalled packages with python 3 - with this step we will switch to executing code on your PC (Note: select an easy to remember folder - eg: c:\anaconda3)
- Step 2: Once you install Anaconda you should be able to run jupyter notebook which is a powerful online application containing an ordered list of input/output cells which can contain code, text, mathematics, plots and rich media.
- Step 3: Launch jupyter notebook by opening a terminal in your PC: example in Windows --> Click on Run and neter cmd.exe - terminal window shoudl appear - type in: C:\Python>jupyter notebook

(Source: https://codingxcamp.com/levels/level2?lang=Python&taskid=600&levelskill=2)

## Sources
All the sources are mentioned in the appropriate spot in the jupyter notebook.

