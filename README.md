# LoL-Summoners-Tracking-GUI

Hello, this is my first ever application !

This application allows you to easily track your ennemy team's summoner spells while playing League of Legend.
It is made in Python 3.8, using the riotwatcher library.

It creates a small movable window on your sceen, composed of the ennemy team's champion icons and both of their summoner spells.
You can press the spells to start a timer. The spell will ready itself when the timer is over.
When pressed, a spell button turns grey (if it wasnt), or coloured (if it was grey). The timer isnt displayed.
You can press a spell button when grey, it will stop the timer and go back to coloured mode (means the spell is ready).

The program wont run if the name/region/API Key arent correct, and if the player isnt currently playing.
See HOW TO USE to fill these informations.

HOW TO USE :

1) Download the python script.
2) Fill the 3 fields at the end of the file (my_name, my_region, api_key).
      - my_name and my_region are the summoner name and region of the person you want to spectate (probably you).
      - An API Key is a personal key that gets delivered by Riot Games for free on https://developer.riotgames.com/, once you've logged in with your Riot games account.
3) In the directory where the python file is, you must have 2 other folders:
      - An empty folder called "Champions_Icons". The champion icons are going to get downloaded into this folder.
      - A folder called "Spells_Icons". It contains the spell icons displayed on the buttons.
     
I added to the project a .rar file than you can download and unzip in the same directory as the script, composed of both the folders i juste cited.
4) Launch a League of Legend game.
5) Set your game to windowed or bordeless mode so the window can be displayed on top.
   I tried to display it on top of the game when in full-screen mode but sadly it seems quite impossible.
6) Run the script. I personally use the basic Python IDLE so i just double click on the script.
7) Whenever you see an ennemy use one of his summoner spells, click the spell he just used. The button will switch to grey. It will switch back to coloured right when your ennemy gets his spell back.


The application works and the timers are adjusted for Classic games, Ranked Solo/Duo, Ranked Flex, ARAM.
It also takes in consideration the rune "Cosmic insight" that gives you a 5% cd reduction on your summoner spells.
It works with the 10 basic summoner spells, as in my opinion it's not usefull to use this application in fun modes with new spells, or in URF...

I am currently trying to get a permanent key from Riot Games, as a classic API Key expires after 24 hours.
It means you must get a new one every day if you want to keep using the application.
