# liri-node-app
Liri
LIRI Bot for Week #10 Homework
About
LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

Motivation
This is a project for the UCF Coding Boot Camp where we are learning to implement node.js. The instructor is Graydon Scates.

What it does
Twitter
node liri.js my-tweets <insert Twitter handle>

This will show this username's last 20 tweets and when they were created at in your terminal/bash window.

Spotify
node liri.js spotify-this-song <insert song title>

This will show the following information about the song in your terminal/bash window

Artist(s)
The song's name
A preview link of the song from Spotify
The album that the song is from
If no song is provided then your program will default to the song "Nothing" by Buju Bantoon

Movies
node liri.js movie-this <insert movie title>

This will output the following information to your terminal/bash window:

Title of the movie.
Year the movie came out.
IMDB Rating of the movie.
Country where the movie was produced.
Language of the movie.
Plot of the movie.
Actors in the movie.
If the user does not enter a movie, the program will output data for the movie 'The Equalizer'.

Do What It Says
node liri.js do-what-it-says

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

By deafult, this is set to run spotify-this-song for "Born this way".

A user can change the text in the random.txt document to test out the feature for other commands.

Authors
Adrian Robertson