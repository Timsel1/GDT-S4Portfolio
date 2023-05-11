# How can I make portals (enemy spawn points), which spawn enemies and are in different locations each time the level loads?
In the game that me and the person im working with are working on, we wanted enemies to spawn from portals. These portals should spawn a set amount of enemies and should be in different locations each playthrough.

## How did I solve this?
I knew that I wanted to do this by having multiple set locations where I can instantiate the portals. I had already found a tutorial that showed me how to instantiate objects in the locations I wanted.
(Library, Design Pattern Research) 
Source:
https://www.youtube.com/watch?v=NWNH9XRtuIc

I made a scene with 3 spawn points and used a random number generator to pick one of the 3 points to instantiate an object. 
(Workshop, Prototyping)



## What was the result?
The first version of my script Could spawn 1 portal In a random location, like I wanted, as shown in the GIF.

[Gif](https://lh4.googleusercontent.com/JzpB2LPamc6yX0QtCVXecNJJWJQFQ_sgqjDF8DoA9o9duFoLF9pjhZyHr2Wf77m3zn55o5z4Uh5RWuGfygAUsrk8TvugYwz0ozsoMwLxcYWFbmfL_gWXW48oy6YIkDsXECNH9203OWitTvSJW8TyBFWjZOmJCKfSu6wRtRPATnpF962Wt1wfzKVJ6ZR9eQ)

## What is the quality of the result?
I showed the result to my duo partner, with this one portal it has worked without fail every time I loaded the level

## What is the next step now that I have this result?
I’m going to update this script to make sure that there is no way for 2 portals to spawn in 1 location, as well as adding serialized fields to the script so values can be changed without altering the code.
