# DS 150 Capstone Project

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](<[link_to_your_colab_notebook](https://colab.research.google.com/drive/11EmdjRLzoTm3QvHnSSOyPmwJNekRmpej?usp=sharing)>)
[![Status: Complete](https://img.shields.io/badge/Status-Complete-green)](<link_to_your_github_repo>)

## Prerequesites

Step 1 -

First you need to have the csv: 
A copy csv can be found here https://drive.google.com/drive/folders/1kgC5_ICyOEVvdAwVBzu9GlBRZd1bO_bN?usp=drive_link

There are two ways that you can go about running the notebook, you can run the notebook from google colab which requires creating a "DS 150 Capstone" shortcut in your google drive

Option A Run directly in colab (requires authorizing and mounting google drive):
1. Create Shortcut /Colab Notebooks/DS 150 Capstone (folder of the link above)
2. When Running "Setup for project" cell authorize access to google drive so that it can mount it, follow the prompts allowing google colab to access your drive

Option B Copy colab notebook:
1. Get a copy of the colab notebook and csv put them in your own local directory in google drive (you could also do this with a jupyter notebook then)
2. Under "Setup for Project" Cell change the last cell df = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/DS 150 Capstone/games_march2025_cleaned.csv') to df = pd.read_csv('games_march2025_cleaned.csv')

Step 2 -
The "Run all" prompt will most likely time out so I suggest running each "chapter" individually starting from top to bottom before expanding them


