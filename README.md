# T411-Torznab

Torznab proxy for T411 French Private Torrent Tracker

It uses Nodejs

# Installation
Simply clone this repository
Then run 
```
npm install
cp config.js.sample config.js
```
Then edit the config.js file to enter your credentials and listen port of the proxy

# Starting application 
Simply run :
```
node server.js 
```
Then the proxy is listening on the port specified
It will try to connect to http://api.t411.io/ to obtain a token with the credentials set in the server.js file

Now you can configure Sonarr to use this proxy to make requests to T411
![Settings Window](https://raw.github.com/KiLMaN/T411-Torznab/screenshots/T411-Torznab-Sonarr-Configuration.png)
The API key is not needed to this proxy, but you must input something so that Sonarr works
For the moment the categories are not working (put anything you want here)
