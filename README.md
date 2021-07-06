# movie-recommendation-system
This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.


How to run the project?
Clone this repository in your local system.
Install all the libraries mentioned in the requirements.txt file.
Replace YOUR_API_KEY in both the places (line no. 23 and 43) of static/recommend.js file.
Open your terminal/command prompt from your project directory and run the main.py file by executing the command python main.py.
Go to your browser and type http://127.0.0.1:5000/ in the address bar.
Hurray! That's it.
