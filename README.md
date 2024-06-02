<h1 id="streamberry">Streamberry</h1>
<p>Welcome to <strong>Streamberry</strong>, a content-based movie recommendation system designed to help you discover movies tailored to your tastes. This project leverages TF-IDF vectorization and cosine similarity to recommend movies based on your preferences.</p>
<h2 id="features">Features</h2>
<ul>
<li><strong>Content-Based Recommendations</strong>: Provides movie recommendations based on the description and title of movies you like.</li>
<li><strong>Interactive User Interface</strong>: User-friendly interface built with Streamlit.</li>
<li><strong>Easy Deployment</strong>: Ready to be deployed on Streamlit Sharing, Heroku, and other platforms.</li>
</ul>
<h2 id="demo">Demo</h2>
<p>You can try out the live demo of Streamberry <a href="https://chatgpt.com/c/d0e86c17-5c63-45ff-8862-48da6c400b1e#">here</a>.</p>
<h2 id="installation">Installation</h2>
<h3 id="prerequisites">Prerequisites</h3>
<ul>
<li>Python 3.6+</li>
<li>pip</li>
</ul>
<h3 id="steps-to-setup-locally">Steps to Setup Locally</h3>
<ol>
<li>
<p><strong>Clone the Repository</strong></p>
<p><code>git clone https://github.com/Sarvaswa-Mohata/Recommendation-System/tree/main</code></p>
</li>
<li>
<p><strong>Run the Streamlit App</strong></p>
<p><code>streamlit run movie-recommender-sys.py</code></p>
<p>Open your browser and navigate to <code>http://localhost:8501</code> to view the application.</p>
</li>
</ol>
<h2 id="usage">Usage</h2>
<ol>
<li><strong>Select a Movie</strong>: Choose a movie from the dropdown list.</li><br>
  
  ![image](https://github.com/Sarvaswa-Mohata/Recommendation-System/assets/99800509/6bdde22e-2c89-4be3-8345-122ba3f12f3a)

<li><strong>Get Recommendations</strong>: Click on the ‘Get Recommendations’ button to see a list of similar movies.</li><br>

![image](https://github.com/Sarvaswa-Mohata/Recommendation-System/assets/99800509/3dd2629b-230a-44a0-addc-b43fd3f026d6)

</ol>
<h2 id="project-structure">Project Structure</h2>
<ul>
<li><code>movie-recommender-sys.py</code>: Main file to run the Streamlit application.</li>
<li><code>tmdb_5000_movies.csv</code>: Dataset containing movie titles and descriptions.</li>
<li><code>Movie_Recommender_System.ipynb</code>: Core recommendation logic.</li>
</ul>
<h2 id="dataset">Dataset</h2>
<p>The dataset used in this project contains movie titles and descriptions, which are vectorized using TF-IDF for generating recommendations.</p>
<h2 id="contributing">Contributing</h2>
<p>Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.</p>
<h2 id="license">License</h2>
<p>This project is licensed under the MIT License. See the LICENSE file for more details.</p>
<h2 id="acknowledgements">Acknowledgements</h2>
<ul>
<li><a href="https://scikit-learn.org/">Scikit-Learn</a></li>
<li><a href="https://streamlit.io/">Streamlit</a></li>
<li><a href="https://pandas.pydata.org//">Pandas</a></li>
</ul>

