# My Binding of Isaac data
Welcome to this repository/project

This was made as my graduation project, effectively a showcase of what I can do with the things I have learnt during my time studying. The data set that was used for this project was hand collected by me, based on some rules that I made to make sure that I count things properly, I am planning on coming back to this at some point in the future, but thats then and not now. I'm aware that the techstack that I am using is quite simple but that is the price being paid for how complicated and in depth the data got over the time of collecting it. 

And yes I did play 100 runs in binding of isaac, it was the rebirth version on the latest dlc patch, so all done on afterbirth+.

I will cover a few different things in this readme, I'll seperate everything so you can do read things one by one, since not everyone plays the binding of isaac.

## The columns
The columns we have in the base data are:
- Id
- Character
- Cause of loss
- Floor
- Victory
- Time
- Ending goal
- Boss rush
- Hush beaten
- Delirum beaten
- Item total
- HP up
- DMG up
- Tears up
- Speed up
- Range up
- Shot Speed up
- Luck up

I'll go in depth over the unclear columns

Cause of loss = if I lost what did I lose to, 'b' stands for boss, 'e' stands for enemy, 'o' stands for obstacle, 'r' stands for reset, 'n' is a win 

Floor = how far into the run I got

Victory = if I won or not

Time = how long of a time it took to get there

Ending goal = there are diffrent ending in the game, each ending has a diffrent route attached, ending 15 for reached by taking the negative item and going down

Boss rush = its an optional thing a player can do if they reach and beat floor 6 before a cetain time on the in game clock, if I remember correctly it is before 20 in game mins, it only counted if I beat it

Hush beaten = is an optional boss that is availble from floor 8 if you reach and beat floor 8 before a cetain time, should be before 30 in game min if I remember correctly, only counted if I beat him

Delirum beaten = is a secret boss available if you beat the final boss of whatever route/ending you went for

Item total = the amount of items total picked up during a run

HP up = the total of items that upped my hp in game, for that run

DMG up = the total of items that upped the damage on my bullets in game, for that run

Tears up = the total of items that upped the tears, so how much more often I shoot bullets in game, for that run

Speed up = the total of items that upped my speed in game, for that run

Range up = the total of items that upped the range of my bullets in game, for that run

Shot Speed up = the total of items that upped the shot speed of my bullets in game, for that run

Luck up = the total of items that upped my luck, how often room clears give rewards, in game, for that run

## the columns added in the transformation
the columns that were added in for the transformed data
- other_items
- time_id
- a group of time intervals, not listing all of them out as they all do the same thing

other_items = items that are not stat ups and apply some type of affect onto the player, giving them posion bullets, immune to explosions, ect

time_id = makes all the times listed into date times to then be used for the time intervals

the time intervals = checks for when a time time is less than and greater than the specifed time in minutes