# MagnetBot

A small discord bot that runs a quick game of Doctor Magnethands for any number of people. 

## Typical Use
The general way users interact with this bot is as follows:
1. One user calls the `:magnet: !Commence` command, triggering MagnetBot to post a brief explanation of the rules. The quiet option can be toggled on if the users already know how to play. This option simply truncates the rules explanation. This player is considered the Game Master.
2. Any user who reacts to the bot message is registered as a player, and is sent a private message. Reponses are thus gathered in secret.
3. After three minutes (barring additional time granted through the `:magnet: !Time` command, the game starts. The Game Master is fed four collected answers at a time and may request the next batch by sending any private message to MagnetBot. This continues until:
    * There are no more responses to send
    * The `:magnet: !Stop` command is called
    * One hour elapses

    whichever comes first.

| Command | Action |
|:--------|:-------|
|:magnet: !Commence [q[uiet]]| Starts a new game of DOCTOR MAGNETHANDS |
| :magnet: !Time <time amount> | Adds the specified amount of time to the entry time limit. This has an upper bound of 5 minutes. |
| :magnet: !Stop | Ends a game of DOCTOR MAGNETHANDS prematurely. |

## Credits
Bot created by [@glochtefeld](https://github.com/glochtefeld). Poke around my other stuff.

[Doctor Magnethands](https://rowanrookanddecard.com/product/doctor-magnethands/) by [Grant Howitt](https://twitter.com/gshowitt)
