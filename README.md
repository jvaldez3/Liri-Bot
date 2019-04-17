# Liri-Bot

concert-this	uses the bandsintown API to take a band name from the user and returns that bands next concert

spotify-this	uses the spotify API to take a song name from the user and returns the artist, song name, spotify-link and album

movie-this	uses the OMDB API to take a movie name and returns the name, cast, release year, IMDB and Rotten Tomatoes rating, country of origin, language and plot

do-this	uses the built in readFile() method to access data from a prepopulated .txt file and return its information as a command/search query.


Before you get started, make sure you have these node packages installed:

Dotenv: Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. Storing configuration in the environment separate from code is based on The Twelve-Factor App methodology.

Command Line: 'npm install dotenv'

Request: - Request is designed to be the simplest way possible to make http calls. It supports HTTPS and follows redirects by default.

Command Line: 'npm install request'

Moment: - A lightweight JavaScript date library for parsing, validating, manipulating, and formatting dates.

Command Line: 'npm install moment'

Fs: - a built in node package


Functionality

concert-this

<command, artist name>

Function takes the userInput (command) and the userQuery(artist), and returns the next concert time and date for that artist, as well as location and city.

<See photos folder for examples on this working>


spotify-this

<command, song name>

Function takes the userInput (command) and the userQuery(song), and returns the artist, full track name, a preview link and the album.

<See photos folder for examples on this working>


movie-this <command, movie name>

Function takes the userInput (command) and the userQuery(song), and returns title, cast, release date, ratings, country of origin, original language and synopsis. 

<See photos folder for examples on this working>

do-this <command>

This function will run whatever is in the random.txt file