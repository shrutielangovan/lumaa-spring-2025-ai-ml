# Movie Recommendation System


## Overview

This repository contains a Jupyter Notebook that implements a movie recommendation system using OpenAI's Azure API. The system takes in movie data(movies.csv) and provides recommendations based on user input/preferences.

## Requirements

Before running the notebook, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in requirements.txt)
- Azure OpenAI API access

## Installation

1. Clone the repository:
   git clone https://github.com/shrutielangovan/MovieRecommender.git
2. Install dependencies:
   pip install -r requirements.txt
3. Set up your environment variables in a .env file:
   AZURE_OPENAI_API_KEY=your_api_key
   AZURE_OPENAI_ENDPOINT=your_endpoint

## Usage

1. Open MovieRecommender.ipynb and run the cells sequentially.
2. Follow the outputs and interact with the recommendations.

## OutPut

The output of the recommendation system provide a list of movies and the genre of interset for the user input. Below are a few examples of the System Outputs.

 1. User Inputs: "I love thrilling action movies set in space, with a comedic twist."
    System Output: Movie Recommendations : Guardians of the Galaxy (2014), Space Jam (1996), Star Wars: Episode IV - A New Hope (1977), The Hitchhiker's Guide to the Galaxy (2005), Men in                    Black (1997) 
                   Genre of Interest: Action, Adventure, Comedy, Sci-Fi
 2. User Inputs: "I am in a mood for light hearted Romantic movies."
    System Output: Movie Recommendations : Notting Hill (1999), Music and Lyrics (2007), The Proposal (2009), The Holiday (2006), Crazy, Stupid, Love (2011) 
                   Genre of Interest: Comedy, Romance
## Dataset Used

The Dataset was obtained from Grouplens. Our model made use of only the first 438 rows from the movies.csv file available in this dataset. The used data present in the movies.csv file within this fork.

Link: https://grouplens.org/datasets/movielens/20m/

---
