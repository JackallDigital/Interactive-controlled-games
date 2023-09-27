# Interactive-controlled-games
Control character and object using your body/joints in Unity with Nuitrack API and a depth sensing camera, in my case that was done with Intel Realsense D435i
which I don't think is the best for hand joint detection as the hand jumps around if you go too far away from the camera. The body/waist/torso joint however
can be detected with better precision from a greater distance.

Since this project is not meant to be available to public I have only added the code that shows how I implemented the player controls using the Nuitrack API.
For each different game I provided the code and description.

And this is how the games look like when played using a depth camera, Nuitrack and projected onto a 3x2 meter wall.

The first game show a breakout type game where the user controlls the paddle with their waist
https://github.com/JackallDigital/Interactive-controlled-games/assets/130217068/03db178c-e9c7-451c-9d03-9fbdb3b82162


The second game is an endless runner where the user controlls the character with their waist, but they can aslo duck and jump
https://github.com/JackallDigital/Interactive-controlled-games/assets/130217068/1e82e1ed-e4b0-4218-bbec-75a3858dddde


The third game is a two person dual pong game which detects both left and right hand of each person, which works.. kind of. Look at the code for more information
https://github.com/JackallDigital/Interactive-controlled-games/assets/130217068/d4e96087-0710-4eaf-ac2e-12d6a4b229e4


AND you can learn how I've done the button interactions and see the Left/Right (open golden) hand in action in this video
https://www.youtube.com/watch?v=ZB_DGKb8ylI
