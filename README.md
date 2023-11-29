# Movie Recommenders #
Movie recommender basic tutorial 

Data is being used to create more efficient systems and this is where Recommendation Systems come into play. Recommendation Systems are a type of information filtering system as they improve the quality of search results and provides items that are more relevant to the search item or are related to the search history of the user. Recommender systems are used in a variety of areas, with commonly recognized examples taking the form of playlist generators for video and music services (such as Youtube and Spotify), product recommenders for online stores (such as Amazon), or content recommenders for social media platforms and open web content recommenders. There are also popular recommender systems for specific topics like restaurants and online dating. These systems can vary in scope/complexity. Some utilize a single type of input, like music, or multiple inputs within and across platforms like news, books and search queries.

Content Based Filtering- They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The fundamental idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.


I'll be building two straight-forward Movie Recommendation Systems using "TMDB 5000 Movie Dataset" from Kaggle. I'll attempt to answer the following questions:
Based on user votes, what are the highest rated movies in the entire dataset? 
What are some recommended movies based on the selection of a particular movie?


Follow these steps to run the data analysis project locally:

Prerequisites:
- Python 3.11.4
- Jupyter Notebook 6.5.4

1. Fork the repository link
2. Clone the repository to your Github account
3. Access the repository from your command line or preferred CMD software
4. Install a virtual environment.
- # Virtual Environment Instructions #
- Once repo is cloned, navigate to it's folder in Terminal/GitBash
- Create virtual environment on Windows by entering: 
  - Windows (GitBash): python -m venv venv 
  - Linux/Mac (Terminal): python3 -m venv venv
- Activate venv by entering: 
  - Windows (GitBash): venv/Scripts/activate 
  - Linux/Mac (Terminal): source venv/bin/activate
- Run requirements.txt to install needed libraries: 
- Windows (GitBash): pip install -r requirements.txt 
- Linux/Mac (Terminal): pip install -r requirements.txt
- When done in venv, deactivate by entering: 
- Windows (GitBash): deactivate 
- Linux/Mac (Terminal): deactivate

5. Install the requirements.txt file to install necessary packages 
- Windows (GitBash): pip install -r requirements.txt 
- Linux/Mac (Terminal): pip install -r requirements.txt

# Features: #
- Read in two or more data files (CSV)
- Clean data and perfrom pandas merge. Calculate new values based on new dataset.
- Make 3 matplotlib visualizations of data.
- Use virtual environment and include set up instructions in README.
- Annotate and clean code in Jupyter Notebook.

# Sources: #
1. https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
2. https://www.kaggle.com/code/ibtesama/getting-started-with-a-movie-recommendation-system
3. https://www.kaggle.com/code/jeyasrisenthil/movie-recommender