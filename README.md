# Ensingm2 Salien Game Idler

[Link to Saliens Game](https://steamcommunity.com/saliengame/play)

### Intro
Hey everyone, Like all of you, I was interested in "streamlining" the process of the 2018 Steam sale 'Salien' minigame. You may or may not remember me as a contributor/dev in the Steam Monster Minigame autoclicking scene from the 2015 Steam sale. I took a look at this year's game, and noticed it's much more... boring. No interactions between other players mean there are only a few interactions with the server, and they can be easily spoofed, as long as you wait out the timer of the round, and only send the maximum allowed score for a zone. So I figured, why automate the game at all? Much easier to just sit at the menu and just say we beat the level.

### Features
* Does not need to run the game at all, works from the main map.
* Automatic switching between zones.
* Easy zone override with the default map.
* Allows quick-switching of planets
* Sends the maximum score allowed for each zone difficulty.
* Automatically repeats runs after completion.
* Optionally disables game animations to minimize game resource usage.
* Status GUI to update level, experience, time remaining in round, etc

### How to Run
**Currently tested on Chrome/Chromium, Firefox and Safari. Internet Explorer and Edge both encounter errors. The following guide is for Chrome:**

1. Open the Salien Game in a new tab and open the planet or battle selector map.
2. Bring up the JavaScript Console
   1. Windows: F12 or CTRL+Shift+J
   1. Mac: Command+Option+J
3. Copy the JavaScript code from [idle.js](https://raw.githubusercontent.com/ensingm2/saliengame_idler/master/idle.js) and paste it into the console and press enter
   1. Output can be seen and tracked in the console

Note: The script may also be setup on userscript managers such as Greasemonkey/Tampermonkey however this is advised against enabling automatic updates for _*any*_ scripts, for your own security.

### TO DO
* Potentially highlight selected zones on the grid?
* Auto-switch between planets (Currently being tested)
* Smarter optimizations of resource usage
* I have a feeling the game will evolve over time, so handle things as they come.
* Any other cool features, with support from viewers like you!

### Want to Contribute?
Feel free. You can submit whatever changes you'd like. Fork, PR, whatever. Go nuts.
