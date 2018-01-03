# LIRI-bot

#### HW #8 for The Coding Bootcamp at UT Austin

For this assignment, I built LIRI. LIRI is like iPhone’s SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives the user back data. 


To retrieve the data that powers this app, I installed the necessary Node packages and sent requests to the Twitter, Spotify and OMDB APIs. 

My app takes the following commands:
	
	* ‘my-tweets’

	* ‘spotify-this-song’

	* ‘movie-this’

	* ‘do-what-it-says’


What each command does:

1. ’node liri.js my-tweets’
	* This will show my last 20 tweets and when they were created at in the terminal/bash window 

2. ‘node liri.js spotify-this-song’
	* This will show the following information about the song in the terminal/bash window: Artist(s), song name, a preview link of the song from Spotify, album name

3. ‘node liri.js movie-this <movie name here>’
	* This will output the following information to the terminal/bash window: Movie title, release year, IMDB rating, Rotten Tomatoes rating, country of production, movie language, plot, and cast.

4. ‘node liri.js do-what-it-says’
	* Using the ‘fs’ Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI’s commands 
	* It will run ‘spotify-this-song for ‘I Want it That Way,’ as follows the text in random.txt

