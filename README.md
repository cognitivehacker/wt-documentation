# Projects

This project is for study purposes, we are not using the best tecnologies to fit the requirements, that's not the point.
The point off all of this is to improve in the knowledge of the above tecnologies.

Name | Language | Framework | Description
---- | -------- | --------- | -----------
wt-documentation | Javascript | gitbook |Using javascript to generate html documentation
wt-api | Java | Vertx | Rest Api
wt-sockets | Elixir | Phoenix | Websocket server for the webclient
wt-webclient | Javascript | VueJs | Front End Interface
"Classifiers" | Golang | ? | Classifiers and ML

Using:
* Websockets
* oauth2
* DDD
* Event sourcing
* GraphQL ?
* Apache Solr
* Elixir - GenServer
* RabitMQ ?
* Apache Spark ?

## Development
* Git flow
* Merge Requests
* Code review
* TDD
* Travis tests
* ?Deploy?

## wt-api

Using event sourcing to project events to database.

## wt-sockets

Using Web Sockets to consume reactive data.

## wt-webclient

Using websockets we receive reactive events to change de state of the app.

# Classifiers (Clustering)
Made in Golang

(Cluster analysis)[https://en.wikipedia.org/wiki/Cluster_analysis]

## System 1
Get all the resources and classify by its category proximity, e.g: comedy, drama, etc

## System 2
Get all the resources and use an aproximation classification by its synopsis.

## System 3
Get all the resources and use an aproximation classification by its subtitles.

## System 0 - Ensemble methods
The goal of ensemble methods is to combine the predictions of several base estimators built with a given learning algorithm in order to improve generalizability / robustness over a single estimator.

# Resource Rating
Use the client resource ratings to point where they are in the classifiers map, and get the resources in that proximity.
Generate a Map.

# Comparator
Compare the two persons maps created with the resource rating, and get the recomendations.

# Todo

* Facebook login and app authorization
* Select liked categories
* Rating System, 5 stars
* Search System (apache solr)
* Add/List/Remove Friends, get from facebook
* Share your movie reviews and/or rating
* Share watched episodes of your current watching tv show
* Recomend tv shows/movies to your friends
* Create lists, e.g: top 10 movies of 2017
* Geolocalization of close cinemas for your movies recomendations
* Upcomming movies/tv shows
* What movies you want to watch, recomend for your friends that want to watch it too
* Show your friends movies watched or want to watch
* Rate movies you do not want to watch, or dislike
* Show movies that is on top recomendations, or top watched
* In your profile, show how many hours of content you spend
* In your profile, show your frequency
* In your profile, show your badges
* In your profile, show your pontuation (Gamification to change your dashboard)
* Get feedback of recommended movies, ?backpropagation to fix issues?


# Recomendations

* In your friends profile see the movies they watched and you dont recomendations
* In your friends profile see the movies they didnt watch and you do recomendations
* In your friends profile see the movies both of you didnt watch recomendations
* Same tv shows you both watch, and how many episodes you are behind to see together
* Tv Shows you both want to watch
