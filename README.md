# How Well do Professional League of Legends Team Keep Leads at 15 Minutes?
This is project 3 of the UCSD DSC80 class.

## Introduction and Question Identification

League of Legends (LOL) is a popular MOBA that is played by many people around the world. Like other sports like basketball, football, soccer, etc. it can be enjoyed casually and even professionally in the form of League of Legends Esports. Like the many professional leagues for sports, League of Legends Esports is a collection of the best players and teams in the world which compete to lift the Summoner's Cup. Split into the region that they are found in (ie. Americas, Europle, Korea), the teams in each region duke it out with one another to determine which team(s) are most fit to represent the region at international events. With its large increase in popularity, fans, both serious and casual, are able to tune in to these matches and see their favorite teams and players parttake in such events. In a similar fashion to other sports leagues, many of the important events and statistics in each match are documented for those to see and understand. Information such as gold earned, xp gained, CS, etc. can help us viewers understand the current climate of the game and provide insight to who might be victorious at the end. This information is not only valuable to the viewer, but can also be valueable to the players and teams on ways to improve in the future.

In the dataset organized by OraclesElixir, match data across all regions in the 2022 professional LOL esports season were collected. Within this dataset, match data information regarding the who: the team that played, which players, which patch; the what: in-game statistics such as which champions were picked, champions that were banned, which side, game statistics - gold, xp, dragon kills, baron kills,etc.; and the the outcome of the match are organized in a readable format. We hope to use this dataset to explore some deeper intricacies into professional LOL. This dataset contains 149400 rows and 123 columns - with the rows grouped into 12 row groups: 10 rows of player information and 2 rows of team information.

In regular League of Legend matches, players are given the opportunity to play the match for 15 minutes before given the opportunity to forfeit (ff). At this point of the game, players are usually able to determine the feasibility of playing the rest of the match as early action is common up to this point of the game. Unlike regular matches, players in professional matches are not given this liberty of forfeitting due to extraneous reasons. However, with this in mind, we hope to analyze how a lead (specifically in gold **and** xp) might contribute to which team is victorious at the end of the match a.k.a. keeping a lead.

As there are many unnecessary columns in this dataset, we only are interested in the columns that contain the statistics relevant to our analysis of this question, which can be summarized below.

| Column | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |
| Paragraph | Text |

