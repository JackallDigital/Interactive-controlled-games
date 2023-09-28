# Interactive-controlled-games
Control character and object using your body/joints in Unity with Nuitrack API and a depth sensing camera, in my case that was done with Intel Realsense D435i
which I don't think is the best for hand joint detection as the hand jumps around if you go too far away from the camera. The body/waist/torso joint however
can be detected with better precision from a greater distance.

Since this project is not meant to be available to public I have only added the code that shows how I implemented the player controls using the Nuitrack API.
For each different game I provided the code and description.

And this is how the games look like when played using a depth camera, Nuitrack and projected onto a 3x2 meter wall.

The first game show a breakout type game where the user controlls the paddle with their waist
<video src='https://github.com/JackallDigital/Interactive-controlled-games/assets/130217068/7140b43c-8ffe-4602-a6e5-895c5b112d6f'/>



The second game is an endless runner where the user controlls the character with their waist, but they can aslo duck and jump
<video src='https://github.com/JackallDigital/Interactive-controlled-games/assets/130217068/759421c1-9d07-4f24-9635-e69595ca44ce' />


The third game is a two person dual pong game which detects both left and right hand of each person, which works.. kind of. Look at the code for more information
<video src='https://github.com/JackallDigital/Interactive-controlled-games/assets/130217068/4507d31c-fdf9-4cc8-8023-bb97d4cbc136' />


AND you can learn how I've done the button interactions and see the Left/Right (open golden) hand in action in this video
https://www.youtube.com/watch?v=ZB_DGKb8ylI
