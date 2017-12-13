---
layout: post
title:  Endless Runner
date:   2017-11-16
description: Starting a new project
category: Low Level Programming
tags: Endless Runner
---
<h1>Making an Endless Runner</h1>
<p>
Lets start with a bit of research. What is an endless runner? 
An endless runner is a game where the players character is continuously running and 
the score is based on distance travelled or an end goal for each level.
<p>
<a class="one" href="http://www.avalanchegame.org" target="_blank">Avalanche</a>
<br><a class="one" href="https://jackv24.itch.io/space-dash" target="_blank">Space Dash</a>
<br><a class="one" href="https://guerragames.itch.io/cave-runners" target="_blank">Cave Runners</a>
<br><a class="one" href="https://playkiseki.itch.io/moonlight-mori" target="_blank">Moonlight Mori</a>
<p>
I have chosen a spaceship avoiding asteroids through an asteroid belt.
<p>
<h4>Lets list some of the more obvious things the game will need to be a game.</h4>
<p>
<ul>
  <li> Firstly, a player, Im going to stick to something simply geometric, like a square shape.
  <li> A level. The level obviously has to be endless and the score tracked by maximum distance travelled.
  <li> Asteroids. To get further the player will have to avoid asteroids, like in a cheesy sci-fi movie scene.
  <li> Whats the point in doing it if theres no score? A scoreboard/leaderboard.
  <li> Wrap this up in a little menu system to play/pause/retry/scores. Oh, and quit when you've realised how bad it is.
<p>
That should get us a basic game. Next we'll have a look at a basic UML for what we will need.
