
# Tokenpass Express Example


## Install

```bash
$ cd example
$ npm install
```

## OAuth Application

Create OAuth application for Tokenpass. For Tokenpass set the redirect url to be `http://localhost.com:3000/connect/tokenpass/callback`, set the application domain to be `localhost`


## Configure

Edit the `config.json` file with your own OAuth application credentials


## Run the App

```bash
$ node app.js
```

## Start the Flow

To start the OAuth flow for tokenpass navigate to `http://localhost:3000/connect/tokenpass` in your browser
