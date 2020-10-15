# LoL-Summoner-Tracking-GUI

Hello, this is my first ever application !

This application allows you to easily track your ennemy team's summoner spells while playing League of legend.

It creates a small movable window on your sceen, composed of the ennemy team's champion icons and both of their summoner spells.
You can press the spells to start a timer. The spell will ready itself when the timer is over.
When pressed, a spell button turns grey (if it wasnt), or coulored (if it was grey).
The timer isnt displayed.

The program wont run if the name/region/API Key arent correct, and if the player isnt currently playing.
See HOW TO USE to fill these informations.

HOW TO USE :

1) Download the python script.
2) Fill the 3 fields at the end of the file (my_name, my_region, api_key).
  - my_name and my_region are the summoner name and region of the person you want to spectate.
  - An API Key is a personal key that gets delivered by Riot Games for free on https://developer.riotgames.com/, once you've logged in with your Riot games account.
3) In the directory where the python file is, you must have 2 other folders:
      - An empty folder called "Champions_Icons". The champion icons are going to get downloaded into this folder.
      - A folder i give you called "Spells_Icons". It contains the spell icons displayed on the buttons.
4) Launch a League of Legend game.
5) Run the script. I personally use the basic Python IDLE so i just double click on the script.
