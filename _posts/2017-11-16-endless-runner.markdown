---
layout: post
title:  Endless Runner
date:   2017-11-16
description: Starting a new project
category: Low Level Programming
tags:
  - LLP
---
<h1>Making an Endless Runner

Lets start with a bit of research. What is an endless runner? 
An endless runner is a game where the players character is continuously running and 
the score is based on distance travelled or an end goal for each level.

http://www.avalanchegame.org/
<br>https://jackv24.itch.io/space-dash
<br>https://guerragames.itch.io/cave-runners
<br>https://playkiseki.itch.io/moonlight-mori

The design I have chosen is one close to the first of these examples, avalanche, 
where the player has to continuously jump on top of falling blocks to escape rising water.

Lets list some of the more obvious things the game will need to be a game .

<ul>
  <li> Firstly, a player, I think im going to stick to something simple and geometric, like a square.
  <li> A level. I'm going to make the level endless and the score tracked by maximum distance travelled upwards.
  <li> Blocks falling. To get higher the player will have to jump onto falling blocks, like in a cheesy sci-fi movie scene.
  <li> A reason to go up. Rising water is a good idea but I don't know if I want do do the same. We'll look at this later.
  <li> Whats the point in doing it if theres no score? A scoreboard/leaderboard.
  <li> Wrap this up in a little menu system to play/pause/retry/scores. Oh, and quit when you've realised how bad it is.
</ul>

That should get us a basic game. Next we'll have a look at a basic UML for what we will need.
