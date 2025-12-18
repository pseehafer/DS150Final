# DS 150 Capstone Project

Authors: Gavin Sorensen, Parker Seehafer, and Noah Sutherland

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11EmdjRLzoTm3QvHnSSOyPmwJNekRmpej?usp=sharing)
[![Status: Complete](https://img.shields.io/badge/Status-Complete-green)](https://github.com/pseehafer/DS150Final/tree/main/Final_Submission)
[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset)

## Prerequesites

First you need to have the csv:
A copy csv can be found here [DS 150 Capstone Folder](https://drive.google.com/drive/folders/1kgC5_ICyOEVvdAwVBzu9GlBRZd1bO_bN?usp=drive_link)

There are two ways that you can go about running the notebook.

### Option A Run directly in colab (requires authorizing and mounting google drive):
1. **Create a Shortcut** in google drive for the "DS_150_Capstone" Folder in your "Colab Notebooks" Folder
2. When Running "Setup for project" cell **authorize access** to google drive so that it can mount it, follow the prompts allowing google colab to access your drive

### Option B Copy colab notebook:
1. **Get a copy** of the colab notebook and csv put them in your own local directory in google drive (you could also do this with a jupyter notebook then)
2. Under "Setup for Project" Cell **change the last cell** df = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/DS 150 Capstone/games_march2025_cleaned.csv') to df = pd.read_csv('games_march2025_cleaned.csv')

---

## Running the Project

This notebook is divided into clear, collapsible sections (chapters) for ease of navigation.

❗❗❗Suggestion: The "Run all" prompt will most likely time out so I suggest running each "chapter" individually starting from top to bottom before expanding them❗❗❗

* **Chapter 1:** Setup for Project
  - Mount google drive
  - Import neccessary Librarys
  - Creating dataframe from csv file
* **Chapter 2:** Exploratory Data
  - Initial exploration of the data
* **Chapter 3:** Functions
* **Chapter 4:** Analyzing Distrobutions of multiple datasets
  - Walks through Analyzing the distrobutions of a number of datasets
  - Tries to clean the datasets to normalize the datasets
* **Chapter 5:** Analyzing Price and Release Month
  - Uses normalized log of Price and the release months
  - Verifies the correlation between release months and price
  - Predicts the price using the normalized log of Price and Release Month
* **Chapter 6** Analyzing Genres
  -

---

##  Results and Insights

### **Predictions**

In the project we each choose to analyze one set of data and make predictions on this.

Gavin - Price and Release Month

Noah - Price and Genres

Parker - Average Playtime and Genre



### **Results**

#### Price and Release Month

The while the price and release month correlate very well, our predicted values are lower than you would expect. This is most likely due to the dataset having a very low mean price. If we had more time I would go through each dataset to clean them and then perform Multiple linear regression on as much of the dataset as possible.

#### Price and Genres


