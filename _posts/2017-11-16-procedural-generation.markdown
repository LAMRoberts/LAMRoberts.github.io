---
layout: post
title: Procedural Generation
date: 2017-11-16
description: PD for Endless Runner
category: Low Level Programming
tags: Endless Runner
---

<h1>Kinda random generation of level</h1>
<p>
  We have a few rules that the "random" level needs to abide by just to make the level completable. For example; if 
  <ul>
    <li>There must always be a way to succeed</li>
    <li>Difficulty should start low and increase over time</li>
    <li>Difficulty should never increase so much as to conflict with the first rule</li>
    <li>This means always more than a ship width between atleast two vertical asteriods</li>
    <li>And atleast a ship length between waves of asteroids.</li>
    <li>Asteroids should never overlap</li>
  </ul>
<p>
  <h4></h4>
<p>
  <a class="one" href="https://www.youtube.com/watch?v=lRfdN4L2SUg&t=1s" target="_blank">Nifty Youtube vid by Jorge Rodriguez
</a>
  Here is a clever method for ensuring atleast the requirements are met.
