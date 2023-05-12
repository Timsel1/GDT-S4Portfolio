# How can I make a metric conversion system so that it only generates conversions 1 above and below the answer’s metric?

The game we are making is meant for primary school students, grade 7 & 8. If the numbers that are generated are currently way too big/small, this minigame will be unnecessarily hard and won’t help them improve their skills. Problem numbers are above 10000 and under 0.01.

## How did I solve this?

I am able to generate random values and make math problems from these values, I just need to convert them. With my first solution I was able to convert the values, but this solution had a problem. When a number would be converted to millimeters, the numbers would be way too large. And when a number would be converted to kilometers, the numbers would be way too small. With this solution the answer could be in kilometers and some buttons would have answers in millimeters.

(Workshop, Prototyping)

I asked my group to review my code and to ask what would be the next best step. We came to the conclusion to only go up/down by 1 unit (so each question would have 3 units total). This way the player is still able to convert multiple numbers to a different unit within a short amount of time.

(Showroom, Peer Review)

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/5edb79e0-b74d-4db6-8e19-83ddf3b8530a)

This way of solving the problem, made making this system a lot easier, but kilometer and millimeter now couldn’t be an answer to the sum since there is nothing to multiply or divide by 10 to get to the next/previous step. To solve this I made 2 more options, 1 for kilometer and 1 for millimeter.

![1](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/2a0faf1d-916e-4ee0-8e7a-7855ede07205)

## What is the result?

All generated values and the answer are now converted to metrics and will be shown correctly on the buttons.

![Metric](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/23e6b084-c2ed-44ca-8dae-d070dc69405a)

## What is the quality of the result?

I have again shown the result to my group members and showed them how it works. They have confirmed the unwanted numbers are gone and answers are always possible. I have later shown this to a primary school teacher and explained why this choice was made. She told me that this was a good solution given the time constraint the minigame has, but if the timer were to be removed, she would like the other metric values to be included again.

(Showroom, Peer Review - Library, Expert Interview)

## What is the next step now that I have this result?

Now that the conversion method works correctly I can start working on player input and checking the answers the player gives.
