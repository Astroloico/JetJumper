# JetJumper
Source code from https://astroloico.itch.io/jet-jumper
code organisation:
  first you got the setup of pygame and other boring stuff <p>
  then you got all pygame surfaces<p>
  then you got the map class:<p>
    it contains the map.MAP constant, witch is a 1d array representing the whole game map
  then you got the key class:<p>
    it handles the more system variables like bools for the keys
    it also has a 'reset input()' function that isnt being used in this game
  then you got the player class:<p>
    it handles all th player's phisics, collision and controls
  then you got the particles class:<p>
    it handles creation, phisics and destruction of particles
  then you got the graphics function<p>
  and finally you got the main game loop with the input managet, tick system and main function calls<p>
