# How can I make a system that generates math questions based on the player amount?

Our game is for children from grade 7 & 8 to improve their math and cooperation skills. If the players don't know how many answers there are, they will have another topic to discuss.

## How did I solve this?

I started out by writing down what steps I needed to take to get this result and made this into a flowchart. The reason I didn’t just use the player amount as the amount of needed answers is because I didn’t want the players to know how many answers they would need to give beforehand. This way they not only need to figure out what numbers to add together, but also how many, this will in turn cause the players to start discussing what the answers could be.

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/ba8be461-eee5-47d5-b8e5-c71b06ad0223)

(Workshop, Prototyping, Brainstorm)

## What is the result?

I now have a way of generating mathematical questions that can have 2-4 answers based on the amount of players. For 2 players the amount of answers will always be 2, if there are more the amount of answers will be between 2 and the player amount. This helps with the aesthetic we are trying to achieve (fellowship), because the players now have an extra topic to discuss, since they don’t know how many answers they need yet.

![sum generator](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/02a55217-62f3-49fd-aeef-de6686c79a0d)

## What is the quality of the result?

I have shown this solution to my group members and they have validated that this way of generating a sum based on the playeramount works. It has also been showcased during the 3rd sprint review, where I got to hear that this was a nice addition and it’s good to have a game that isn’t reliant on a certain number of players. To make sure it keeps working I also wrote a unit test, this again confirms it will never select an amount of answers that is higher than the amount of players.

(Lab, Unit Test - Showroom, Peer Review)

![sum generator](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/884e81af-8476-4cba-88f5-1cb44619fa79)

## What is the next step now that I have this result?

I now need to convert the values and sum to metrics. So I need to make a conversion system.
