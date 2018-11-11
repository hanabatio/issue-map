# Issue Map

![Preview of Issue Map](https://i.imgur.com/PkaGO47.png)

## Authorship
Created at BostonHacks 2018 by Hana Batio, Aaron Brown, Reed Brown, and Jacob Meltzer, using Google and Twitter APIs. 

## How to Run
To start a server run `node server.js`. This will initialize our connect to Twitter through a backend server. (Twitter API must use server-like connection to API due to CORS restrictions)

To start the front-end React component, simultaneously run `npm start`. For purposes of testing, we initialize our server to work on low traffic Twitter streams. Try entering a more popular Twitter stream in the search bar of our web app, and then press **Search**. 

## Technical Specifications
Our application is built on Node with React for frontend, Express, and Stream.io for a two way connection between the two.

We make use of Google's Map API to display and plot tweets on a map, Google's Geocoder API for determining location from user location field, and we began implementing translation of text through Google's translate API. We used Twitter' streaming API to collect data. 
