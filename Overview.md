# Overview

The kards stats system is admittedly not built well, as it was put together seperately.

![Overview Diagram](https://github.com/KlutzyBubbles/Kards-Stats/blob/main/images/overview.PNG?raw=true)

Some not included in the diagram includes kards-dt-client which was the original idea, to have a helper program to run alongside kards, but the difficulties introduced by the lack of an API made the program into something i wasnt prepared to bring to life, but the source code is still here.

Also not included is kards-tools as it is just a library of utility functions used across the different repos.

## Brief Exmplaination of each

### kards-discord-bot

Exactly the same as the kards bot, except it doesnt have to be updated when there are new cards

### kards-dt-web

Frontend for the web interface for viewing data gathered

### kards-dt-gateway

Connector for kards-public-stats and kards-dt-backend

### kards-public-stats

Backend for getting any stats that dont require to be logged in as the user

### kards-dt-backend

Backend for storing and getting most custom data from the database

### contest

Kards match replay for use as an application or in the browser

### kards-match-watcher

A more controversial program that does what its name says, watches and records every match played in kards (about 1 every 2-3 seconds). Using this ~250K games have been analysed.
