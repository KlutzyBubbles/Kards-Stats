# Kards API

https://github.com/KlutzyBubbles/kards-json-api

This contains what i have found via trial and error and monitoring on how the kards backend api works.

This repo has nothing to do with the kards website beta, since that is GraphQL, it should be self documenting.

The most complete set of endpoints in the repo would be the Postman requests, as it was theprogram i used to test all of the endpoints.

## What can be done

The API used to be a lot more open until i poked my head around (computer information, IP's, email addresses etc). But it is still fairly comprehensive on what you can see without needing to log in.

`Note: Without logging in means without logging into the user whos data it relates to`

`Limited match data doesnt include mulligan, decks info, rank or rewards, only the match actions`

Some examples of things you can seee are
- Match Replays (limited)
- Previous seasons data (matches played)
- Current win streak, lose streak
- Player equipped items
- Campaigns a player has completed

The rest of the things like nation rewards, decks and cards can only be viewed when logged in.

## What i hope for

I see no reason why this information would be kept hidden. I hope one day they add some of these into the game or better allow it as a proper API.
