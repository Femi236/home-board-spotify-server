# Spotify Accounts Authentication

This project contains the authorization code flow to connect to the Spotify API.

## Inspired by

- [Spotify Web API](https://developer.spotify.com/web-api/authorization-guide/)

- [Johnny Kalambay](https://youtu.be/prayNyuN3w0) and [his GitHub repo](https://github.com/jonnyk20/spotify-node-react-starter-kit)

## Installation

This is run on Node.js. On [its website](http://www.nodejs.org/download/) you can find instructions on how to install it.

Once installed, clone the repository and install its dependencies running:

    $ npm install

### Using your own credentials

You will need to register your app and get your own credentials from the Spotify for Developers Dashboard.

To do so, go to [your Spotify for Developers Dashboard](https://beta.developer.spotify.com/dashboard) and create your application.

- http://localhost:8888/callback

Once you have created your app, create a .env file in the root directory and create 2 variables.

    $ SPOTIFY_CLIENT_ID=""
    $ SPOTIFY_CLIENT_SECRET=""
    $ SPOTIFY_REDIRECT_URI=""

replace the quotation marks with your `client_id`, `client_secret` and `redirect_uri` that you received from Spotify.

## Running the examples

In order to run the code, open the terminal and run:

    $ node app.js

Then, open `http://localhost:8888` in a browser.
