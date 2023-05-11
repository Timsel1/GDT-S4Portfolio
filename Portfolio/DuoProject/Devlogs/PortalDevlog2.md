# How can I make my portals more dynamic and make sure that only one can spawn at a certain location?

In the game that me and the person im working with are working on, we wanted enemies to spawn from portals. These portals should spawn a set amount of enemies and should be in different locations each playthrough. Right now there is no way to change the amount of enemies you want to spawn without changing the code and 2 portals can spawn in 1 location. These things need to be fixed.
How did I solve this?

To make the portals more dynamic I used serialized fields and new properties so you can easily change the amount of enemies and portals you want to spawn.

To solve the problem of multiple portals spawning in 1 location, I first had to look at why this was possible (Field, Problem Analysis or Workshop, Root Cause Analysis). This was because there were no checks to see if a portal was already spawned in a certain location. The first thing I wanted to test is if I could keep a small list of portal spawn points that were already in use. To do this I had to refactor my code. 

(Workshop, Prototyping)

## What was the result?

I can now change the amount of portals and enemies I want to spawn without changing the script.


Portals now can’t spawn twice in 1 spot, because the script now knows when a location is in use.


## What is the quality of the result?

I showed the result to my duo partner again, and let the game load the portals many times without fail.

(Showroom, Peer Review)


## What is the next step now that I have this result?

With the enemy spawns working correctly, we can use them in our levels.
