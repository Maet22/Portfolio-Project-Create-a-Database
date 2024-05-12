## Porfolio project: create a full database- Football team

The selected theme for this portfolio project is a database that contains the key information for managing a professional football team within a given season. The database is voluntarily centered on an isolated season rather than on the overall history of the club.

The team is a fictional team called "Racing Club de Paimpol", a first division French team displaying international class players and rivaling with European top class teams in Champions' League (as said, it is fictional).

In particular, the areas of the club's life covered by the database, which I envisioned as a draft of full information system, are the following: games played, players performance, availabilities for next game, admissions and discharges from infirmary, tracking of yearly subscriptions/single game tickets sold, career data about players, training programs, staff members...

The schema below represents the tables of the database, their attributes, and their respective relationships. To note that for more clarity, fields that are abbreviated in the real PostGreSQL database are fully written in the schema.

In order to ensure and ease the maintainance of the database throughout the season, I have also created roles with specific perimeters of intervention, and dedicated functions/views/queries, all of which are detailed in the next sheets. 


! [Tables] ([tables.png](https://github.com/Maet22/Portfolio-Project-Football-Team-Database/edit/main/tables.png))
