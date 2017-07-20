# spotbot
A bot which updates a Spotify playlist based on songs posted to a Slack channel. Think of it as a fancy #nowplaying channel in Slack.

## Requirements
 * Node.js
 * A Slack Account
 * A Spotify Account

## Setup
### Install Dependencies
```
npm install
```

### Create a Slack bot configuration
Create a custom integration bot within Slack. Copy the API token.

### Create a Spotify App
 1. Go to https://developer.spotify.com and click "My Applications"
 1. Click "Create an app"
 1. Give it a name and a description. Click "Create"
 1. Get the Client ID and Client Secret

## Running
```
SLACK_API_TOKEN=<YOUR SLACK TOKEN HERE> \
SPOTIFY_CLIENT_ID=<YOUR SPOTIFY CLIENT ID> \
SPOTIFY_CLIENT_SECRET=<YOUR SPOTIFY CLIENT SECRET> \
SPOTIFY_REFRESH_TOKEN=<YOUR SPOTIFY REFRESH TOKEN> \
npm start
```