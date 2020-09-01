# rail-rn-json-server
Repository for rail-rn mocked data

## Getting Started
Prerequisites
1. Have Node Package Manager (NPM installed)

Install json-server, json-server-auth
sudo npm install -g json-server

Check version (currently using 0.16.1)
json-server -v

brew cask install ngrok

## Running server
In one terminal
json-server db.json -m ./node_modules/json-server-auth

In another terminal
ngrok http 3000





