Popularity Prediction of Spotify Songs

This repository contains code and data for predicting the popularity of songs on Spotify. The project uses machine learning algorithms to predict the popularity of songs based on various features such as the song's tempo, danceability, energy, and valence.
Installation

To use this code, you will need to have Python 3 and several libraries installed. You can install the required libraries by running the following command:

sh

pip install -r requirements.txt

Usage

You can run the main.py file to train and test the machine learning models on the dataset. The file takes several command-line arguments, including the path to the dataset file and the name of the target feature. You can run the following command to see a list of available command-line arguments:

sh

python main.py --help

Dataset

The dataset used in this project is a modified version of the Spotify Million Playlist Dataset, which contains metadata for over a million Spotify playlists. The dataset used in this project includes only songs that have been played at least 100 times in Spotify, and it contains 16,550 songs and 18 features.
License

The code in this repository is licensed under the MIT license. The dataset used in this project is subject to the license terms of the Spotify Million Playlist Dataset.
Acknowledgments

The code in this repository is based on the work of RexhaMuharrem and JRobertEdwards. Special thanks to them for their contributions.
In this project I aimed to predict Popularity from Spotify Songs Features.

I used Regression models to get result between 1-100,
then I change the Popularity values to Labels like 
  - 0-25 ==> 1. class
  - 25-50 ==> 2. class
  - 50-75 ==> 3. class
  - 75-100 ==> 4. class
  
So used Classification Models too.

You can see Acurracy Scores in Python Notebook page.

PS: Dataset is bigger than 25 mb I cant upload.
- You can reach dataset from this Link: https://docs.google.com/spreadsheets/d/1fDCu4KlQoNbab1gISGQCBzJ8gxmtBXN89ZPxdqOeSoE/edit#gid=210231712
