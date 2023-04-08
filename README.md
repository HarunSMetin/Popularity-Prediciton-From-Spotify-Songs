
	<h1>Popularity Prediction of Spotify Songs</h1>

	<p>This repository contains code and data for predicting the popularity of songs on Spotify. The project uses machine learning algorithms to predict the popularity of songs based on various features such as the song's tempo, danceability, energy, and valence.</p>

	<h2>Installation</h2>

	<p>To use this code, you will need to have Python 3 and several libraries installed. You can install the required libraries by running the following command:</p>

	<pre><code>pip install -r requirements.txt</code></pre>

	<h2>Usage</h2>

	<p>You can run the <code>main.py</code> file to train and test the machine learning models on the dataset. The file takes several command-line arguments, including the path to the dataset file and the name of the target feature. You can run the following command to see a list of available command-line arguments:</p>

	<pre><code>python main.py --help</code></pre>

	<h2>Dataset</h2>

	<p>The dataset used in this project is a modified version of the <a href="https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge">Spotify Million Playlist Dataset</a>, which contains metadata for over a million Spotify playlists. The dataset used in this project includes only songs that have been played at least 100 times in Spotify, and it contains 16,550 songs and 18 features.</p>

	<h2>License</h2>

	<p>The code in this repository is licensed under the MIT license. The dataset used in this project is subject to the license terms of the <a href="https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge">Spotify Million Playlist Dataset</a>.</p>

	<h2>Acknowledgments</h2>

	<p>The code in this repository is based on the work of <a href="https://github.com/RexhaMuharrem">RexhaMuharrem</a> and <a href="https://github.com/JRobertEdwards">JRobertEdwards</a>. Special thanks to them for their contributions.</p>

	<p>If you have any questions or comments, please feel free to create an issue or pull request in this repository.</p>


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
