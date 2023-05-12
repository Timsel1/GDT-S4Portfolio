# How can I adjust the sum minigame, so that it fits better with the math curriculum of grade 7 & 8?

During the last playtest this minigame could make a team fail with ease. If players got a division sum with decimals, it was hard to figure out what the solution was. If people on fhict can’t complete our game, it will be hard for primary school children to do so. I have also shown the sum minigame to a primary school teacher and the feedback I received was: 

   - Put the answers in (visual) blocks.
   - Automation numbers for plus and minus can be increased, since the difficulty for these questions is way too low.
   - Subtractions shouldn’t have negative answers.
   - Time tables can be increased up to 25 instead of 20, but this is not necessary
   - Divisions shouldn’t have an answer that has decimals, this makes it way too hard.

(Library, Expert Interview - Showroom, Peer Review)

## How did I solve this?
#### Divisions shouldn’t have an answer that has decimals
To achieve this, I had to change the order in which I created a sum. Before I generated the numbers and chose an operator to use later. Now I had to first check what operator I had and base the sum on that.

After this I needed to add a check to the division method. I had to check which of the 2 chosen numbers was biggest, since otherwise you would end up below 1. After this i had to check if the 2 numbers would be a whole number when divided with each other. 

#### Subtractions shouldn’t have negative answers

For the subtraction I only had to check which of the 2 numbers was biggest and then put them in the correct order, this way it is impossible to end up with a negative number.

####Automation numbers for plus and minus can be increased

Since the addition and subtractions were too easy, I increased the values of the max numbers that could be generated.

#### Time tables can be increased up to 25 instead of 20

I decided to keep the highest possible number to generate at 20, since at the playtest some students were struggling a little with these questions.

## What is the result? 

The minigame now has numbers up to 1000 for addition and subtractions, divisions now won’t have any answers with decimals and subtractions can’t have a negative answer.

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/c3bd8265-6eb1-47dc-85eb-96ae1ebdf2dc)

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/5e0ae88e-1280-467c-aa32-92b7c6fc8b6b)


## What is the quality of the result?

I showed the improvements to the same primary school teacher and was told that this fits better with the curriculum. The difficulty seemed right and not too easy. To show my code actually works I wrote 2 unit tests.

(Library, Expert Interview - Lab, Unit Test)

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/82e1417e-9048-4931-b02a-293a02ce4c44)

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/4cc36bce-fa94-4800-9823-e9f2ba8eb815)

## What is the next step now that I have this result?

I will test this minigame with the target audience to see if they think this is still too difficult.
