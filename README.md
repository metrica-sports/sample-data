# Metrica Sports Sample Data

## About the repo
In this repository you can find sample tracking and event data that exemplify the Elite data package we offer. The idea of this data is twofold: 
1. to allow potential clients to check out this data and get familiar with our formats and data quality. 
2. to provide some sample data to play around with to the broader football analytics community! 

## About the data
- At the moment there are two games in our standard CSV format, in the coming days we will add the same data in the standar FIFA format. 
- The data of these two games is anonymized, meaning there are no references to the names of players, teams or competitions.
- You'll see the data goes from 0 to 1 on each axis. The coordiante (0,0) is the top left, (1,1) is the bottom right, and (0.5,0.5) is the kick off point. 
- The dimensions of the field are the same for both games: 105x68 meters. 
- For the events, in the `documentation` folder you can find a pdf file with the definition and explanation of all our events types and subtypes. 
- Tracking and event data are synchronized.
- [UPDATE 2021-04-15] A new game has been added: Sample Game 3. This game is in the new format (EPTS FIFA format for the tracking and metadata and json for the events). We recommend using [kloppy](https://github.com/PySport/kloppy/) to read this data.

## Getting started
Laurie Shaw (https://twitter.com/EightyFivePoint) form the Sports Analytics Lab of Harvard University has some great introductory python code to working with this data as part of the Friends of Tracking initiative. You can find it here: https://github.com/Friends-of-Tracking-Data-FoTD/LaurieOnTracking and watch his first lesson with this data here: https://youtu.be/8TrleFklEsE

## Legal stuff
- Please be responsible with the use of this data.
- If you use it for anything public, please aknowledge the source.

## Future plans
- We will try to add data for more games in the future.
- We will try to add (may be in another repo) scripts to get started analyzing this data.
- To stay up to date with news and additions, follow https://twitter.com/brunodagnino

## Other tracking data sources
- 3 games from Hammarby by Signality as part of David Sumpter analytics course. Tracking and video (not synched), no events. https://uppsala.instructure.com/courses/28112/pages/4-player-movements-on-the-pitch
- 9 games by Skillcorner as part of the Friends of Tracking initiative. Tracking from broadcast feed, no events, no videos. https://github.com/SkillCorner/opendata
- 19 goals scored by Livepool FC in 2019 by Lastrowview / Ricardo Tavares. Tracking (players and ball), no events, no vides. https://github.com/Friends-of-Tracking-Data-FoTD/Last-Row

## Events data sources
- Statsbomb open data: https://github.com/statsbomb/open-data
- Wyscout event data: https://figshare.com/collections/Soccer_match_event_dataset/4415000

