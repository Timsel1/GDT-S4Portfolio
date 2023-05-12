# How Can I improve FPS performance in the game?

I have noticed that in the level I made the fps has gone down by about 200 frames per second. This is on a gaming laptop/pc. This means that people who don’t have a gpu in their system might not be able to run the game.
## How did I solve this?

I looked at the parts of the map that could cause a decrease in fps and turned these objects off. Once I knew what to turn off I started working on a solution.

(Field, Problem Analysis) 

I have asked a teacher about improving performance in the game and told him what I thought would be a good solution. My solution were triggers which would set enemies active/inactive. This would make sure that parts of the map the player hadn’t reached yet wouldn’t spawn enemies. My teacher agreed and told me that triggers were a common solution.

(Library, Expert Interview)

Next I looked up how to make trigger zones, all I needed to know was the function that would make something happen if a player stepped into a trigger zone. 

(Library, Design Pattern Research)
    Source(s):

    https://docs.unity3d.com/ScriptReference/Collider.OnTriggerEnter.html 

## What is the result?

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/fd8dd798-5f91-4731-a787-d1683def4a68)

I now have 2 trigger zones which can set enemies active and inactive depending on whether the player is inside of this area. This has increased performance with about 200 fps, which means that the game is now easier to run on lower end hardware.

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/0b9ddc99-ccfe-4a4c-82fd-ee883746d203)


Before:

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/77ca1142-a8da-4885-9a5b-605b79f97d59)

After:

![pasted image 0](https://github.com/Timsel1/GDT-S4Portfolio/assets/90602424/9f41725f-dced-4c68-9de5-3d3cb6e56b30)

## What is the quality of the result?

I have shown my improvements to my duo partner and we talked about how we could improve this even more if we had time left. The improvements for now were good enough and made the game more playable.

(Showroom, Peer Review)
## What is the next step now that I have this result?

If there was more time left I would like to improve my optimizations since it is still noticeable when the enemies spawn in and enemies that spawn from portals stay active after you leave the trigger zone. I have tried setting them inactive if they are outside the range of the camera, but then they can’t be set to active again.
