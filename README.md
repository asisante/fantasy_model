# Fantasy Model PRD
Side Project in developing a data product for Fantasy NFL users in selecting players based on risk preferences and historical point variation
Authors: 
- Angelo Sisante
- Conor Hargrove
Date: 07-25-2020

## The Problem
Incomplete information and behavioral bias prevents a Fantasy sports user from maximizing their Fantasy team’s aggregate production utility as a function of each individual pick a user makes during a draft. 

## The Vision
Identify why this problem is worth solving and what is the novel concept we intend to use to solve it
- Better make gambling decisions 
- Winning feels good 
- Software scales 
Novel 
- Player Variation 
- Risk Preferences 
- Value-based decision making 
- Information availability based on data 
## What Success Looks Like
### We will be successful when: 
- Users can utilize our software to reduce the information gap between where a player is drafted without complete information (the average draft position) and where they should be drafted using complete information (the maximized utility position)
- Reduce the residual in player draft decision making 
- Make a model that accurately calculates fantasy point generation based on position, yards thrown/run, and other point factors 
- Build a website that aggregates a user’s team’s point variation (confidence interval) and recommends undrafted players that would reduce that team’s variation and increase team point production 
## Milestones
### Crawl
What will we/can we conquer first
- Find a complete and accurate NFL dataset that captures player metrics 
- Build a model that calculates point generation for every game the player has played 
- For each season, determine an individual players variation and rank players accordingly
### Walk
What will we solve next
- Identify a way to determine how individual player variation contributes to aggregate user team point variation 
- Develop a way to input risk preferences where the model outputs ranked players based on that risk preference 
- UX/UI Design: Make it intuitive for the user by using their metrics ($)
- Develop a model that takes opposing team characteristics and influences model recommendations for the user 
- Use predicted point outcome and standard deviations on that 
### Run
What does the final product look like 
- Provide the user with litany of draft outcomes based off of (risk, etc) that change model characteristics 
- Web-hosted, clean user interface for people to use (i.e. make it intuitive and hide the model behind a set of user inputs) 
- Consider other factors that influence variation outside of point production characteristics (Home vs Away, Days Off, “Momentum”, etc)
