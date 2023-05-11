# How can I make portals (enemy spawn points), which spawn enemies and are in different locations each time the level loads?
In the game that me and the person im working with are working on, we wanted enemies to spawn from portals. These portals should spawn a set amount of enemies and should be in different locations each playthrough.

## How did I solve this?
I knew that I wanted to do this by having multiple set locations where I can instantiate the portals. I had already found a tutorial that showed me how to instantiate objects in the locations I wanted.
(Library, Design Pattern Research) 
Source:
https://www.youtube.com/watch?v=NWNH9XRtuIc

I made a scene with 3 spawn points and used a random number generator to pick one of the 3 points to instantiate an object. 
(Workshop, Prototyping)

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/dacc1581-d657-43ab-b32a-f95b6632d818)

## What was the result?
The first version of my script Could spawn 1 portal In a random location, like I wanted, as shown in the GIF.

![PortalV1](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/7e6e692d-3193-4199-8ae5-fb50b134699f)

## What is the quality of the result?
I showed the result to my duo partner, with this one portal it has worked without fail every time I loaded the level

## What is the next step now that I have this result?
I’m going to update this script to make sure that there is no way for 2 portals to spawn in 1 location, as well as adding serialized fields to the script so values can be changed without altering the code.
