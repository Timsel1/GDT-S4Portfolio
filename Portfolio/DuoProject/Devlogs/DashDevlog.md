# How can I add a dash that gives the player more control while being in the air?

During our first playtest players had control over their character while being in the air, however there was no way to quickly change direction and keep momentum while being in the air if you were out of jumps. This caused players to get hit by enemy attacks because they fell into them and had no way to dodge them. We had prepared a form for this playtest to see if people would like more movement mechanics and if so, what they would like to see. Dash was the most popular answer.

(Showroom, Peer Review + Field, Observation & survey)
![pasted image 1](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/71eef1f2-7b5f-46e7-9900-1ad24ae57076)

## How did I solve this?

I already had a working dash script from another game I was working on so I wanted to implement it in this game as well. When I did this and tested it out I saw that my dash script messed up the corgi engine and made our player character move on its own and go through walls.

(Workshop, Prototyping)

Since we are using corgi engine I decided to look up if there was a dashing script in the corgi engine and there is. So I decided to use this script. It was easy in use and I only had to look at 3 values, which were Dash Distance, Dash Force and Dash Cooldown.
![1](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/fefe621c-3dfb-4740-88b0-9d5ee8b26d96)

Source(s):

    https://corgi-engine-docs.moremountains.com/API/class_more_mountains_1_1_corgi_engine_1_1_character_damage_dash.html

## What is the result?

A player can now dash on the ground and in mid air. The dash will come back after a short period of time, which makes it possible to dash multiple times without touching the ground if you stay in the air for long enough.

## What is the quality of the result?

I have shown the dash mechanic to my duo partner and the playtesters, since I know that it would function I just needed to know if the values I used were right. I got positive responses and the people that had played the game before said they felt like they had more control while being in the air than before. 

(Showroom, Peer Review + Field, Observation & survey)
## What is the next step now that I have this result?

The dash mechanic will be usable in every level of our game, the values that have been used during the playtest will also stay the same. This means the dash mechanic is done.
