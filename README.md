# Jiglook

### Introduction

As a core part of my learning experience at Udacity, I created, tested and iterated on a mobile VR puzzle called Jiglook. In this game, players enter a scary middle ages-type of dungeon that contain five fantasy orbs and must solve a 3D Simon says puzzle in order to get out. After they solve the puzzle, they transition to the exit gate. Peeking out, they encounter a canvas that congratulates them on completing the puzzle. Once they reach the canvas, players are given the option to restart the game. 

### Development Process

GVR Unity SDK version 1.3.0 was used for this project
The most notable part of this project was making sure the player is of relative size to the dungeon that they’re in. Creating a simple mobile VR experience was key in order to make a simple enough game for a person experiencing VR for the first time. It was important to create a few builds with a modified gate in Unity so that it is of relative size to the front door of my house. 

### User Testing

**Testing the scene and atmosphere**

I conducted a range of user tests on my wife from each development build and it was good to see someone who has never officially critiqued my work. This was done in order to determine player size and the feeling of being in the dungeon.

**New Scene Build**

Initially, my wife said she felt a little too big in the dungeon and could almost can touch the ceiling. It felt like she was sitting but was as tall as the light. The chains on the walls helped with determining how tall the player had to be. When asked how it felt like being in the dungeon, she said, “ Nasty. If I were in that kind of place, I would be like “ew”. Where am I gonna sit, where am I gonna sleep?” There was also an issue with a twitching line on the floor. 

**New build with panels**

In the second build, she had to close one of her eyes because the camera viewpoint made her dizzy. This one had a start and restart panel which had buttons on it which made it obvious how they affected the scene. The restart panel had to be disabled so that the user could switch back and forth.

**New build with movement**

Once the user clicks on the start button, they are eased into the dungeon via gliding motion as if on rails. The movement was a little fast at first but then an element of simulator sickness was of topic for this build. When asked about anything disorienting, the reply was “Just dizzy. When hitting restart, I feel like I’m peeking out from the door.” This peeking meant that the restart canvas needed to be moved to the right.

**Start to finish user test (with noise)**

After the canvas was moved to a more proper location, it was easier for the player to see it once they finished the puzzle. The user determined that the movement after “the bubbles”, (they’re orbs btw) was too fast and it still felt like the event system took the user too low to the ground. Also, a spooky audio clip was inserted which frightened my lovely wife.

__Breakdown of final piece__

![Alt Text](https://github.com/tedlanda/Jiglook/blob/master/Jiglook.png)

[Click here to see Jiglook in Action!](https://www.youtube.com/watch?v=iQocwVV2rcM)

__Conclusion__

This project was fun because it was a puzzler game and it was interesting to create user tests and documentation on Medium.com. Those project write ups seemed professional! When creating lit up orbs using the Puzzle script, it was fun to make it fail with special noises and also get out of the dungeon to be able to restart the scene by moonwalking backwards. 


There was a lot of documentation to write about and a lot of user tests to conduct. Even though it is a necessary evil to get the project started in a composition notebook via sketching, it would be good to jot down every checkpoint what had been worked on. This project was a challenge because of the amount of documentation and getting the puzzle to work properly.
