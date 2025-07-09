**Rodri's Case for the Ballon d'Or: A Data-Driven Analysis**

Objective
This project analyzes Rodri’s impact in the Euro 2024 Quarter-Final between Spain and Germany to evaluate whether he deserves the Ballon d'Or ahead of more attacking players like Vinícius Júnior. The aim is to highlight the importance of Rodri’s role as a defensive midfielder, especially in areas like progressive passing, tempo control, and build-up play — aspects that traditional goal and assist stats often overlook.

Background
The 2024 Ballon d'Or race sparked debate when reports emerged that Rodri would win the award. In protest, Vinícius Júnior and several Real Madrid teammates reportedly chose not to attend the ceremony, believing Vinícius’s 26 goals and 11 assists made him the rightful winner.

This project does not aim to dismiss Vinícius’s season, but to offer a data-driven argument in favor of Rodri — a player whose influence is less visible in highlight reels but central to both Manchester City’s and Spain’s success.

Methodology
The analysis is centered around the Spain vs Germany Euro 2024 Quarter-Final match. Using event-level data from StatsBomb, the project focuses on:
Progressive passes by Rodri
His involvement in Spain’s build-up play
Pass networks showing his centrality
Positioning and movement across phases of play
Rodri’s defensive numbers, while elite, are not the focus here — as they are already widely accepted.

Tools Used
numpy
pandas
[statsbombpy](https://github.com/statsbomb/open-data) (for retrieving StatsBomb data)
[mplsoccer](https://github.com/andrewRowlinson/mplsoccer) (for visualizing match events and pass maps)

Data
All event data is sourced from StatsBomb via the statsbombpy API. The data has been cleaned and pre-processed from [statsbomb](https://statsbomb.com/what-we-do/hub/free-data/) to focus only on relevant metrics.
