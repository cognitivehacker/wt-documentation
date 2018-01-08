# Projects

Name | Language | Framework | Description
---- | -------- | --------- | -----------
wt-documentation | Javascript | gitbook |Using javascript to generate html documentation
wt-api | Java | Vertx | Rest Api
wt-sockets | Elixir | Phoenix | Websocket server for the webclient
wt-webclient | Javascript | VueJs | Front End Interface
"Classifiers" | Go | ? | Classifiers and ML

Using:
* Websockets
* oauth2
* DDD
* Event sourcing
* GraphQL ?
* Apache Solr
* Elixir - GenServer

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

# System 0 - Ensemble methods
The goal of ensemble methods is to combine the predictions of several base estimators built with a given learning algorithm in order to improve generalizability / robustness over a single estimator.

# Resource Rating
Use the client resource ratings to point where they are in the classifiers map, and get the resources in that proximity.
Generate a Map.

# Comparator
Compare the two persons maps created with the resource rating, and get the recomendations.
