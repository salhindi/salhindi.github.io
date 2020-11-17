---
layout: post
title:      "Sinatra: GameCircle"
date:       2020-11-17 19:21:16 +0000
permalink:  sinatra_gamecircle
---


This Web App is meant  to connect gamers through platforms and games. If we look at the best platforms for gamers to collaborate, they end up on either Facebook, Discord, or other apps with no gamer ammenities. 

The creation of this app all began with the handy Corneal Gem. I began to think of ways I'd like to improve and developing the main.css and domain model. 

The first directory development plans I will share are under db/migrate. You can currently click on a post someones shared with their platform as the title of the post. I believe recreating it with a stats attribute that would come from adding an additional table called Games that would be jointed with my Platforms model. 

Hopefully in the future, I can add links to Twitch and Discord channels that a user may upload and we can have a calloboration view, and maybe a non-inclusive view for teams that want to connect. 

Here's what I'd like to add
1. Add columns to the platforms database that gamers belong to. Such as their username for the console/gameing platform they're playing on (However this can only be shared with a team feature). 
2. To expand on the games and username I added, I'd need to create another table, "Games", the names would be shoveled into the Platforms games array stored in its table.  
3. This is where a stats/character-API would come into play, if the data for games exists, then users should be able to access their own stats and decide to update certain features provided by their main game console. 
4. I believe the platforms menu to choose for your profile would be better off as a dropdown menu with options instead of text input. That way the option can have their Main Logos, and their text inputs won't need to validated.

In the end, there's a lot of work left to do to get this app, and it was hard not to get stuck on the details and css aspect.

As a painter, watching the styling and aesthetics of the page update was the best part!





