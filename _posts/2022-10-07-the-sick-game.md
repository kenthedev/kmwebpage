---
layout: post
title: The Sick Game
date: 2022-10-07
excerpt: '3D Geometry Dash + Rhythm Game'
project: true
tag:
  - unity3d
  - 2D
  - game
  - isometric
comments: true
published: true
---

<figure><iframe src="https://itch.io/embed/1734756" width="552" height="167" frameborder="0"><a href="https://ollie1616.itch.io/the-sick-game">The Sick Game by Ollie1616</a></iframe></figure>
     
The Sick Game was a submission to the DGDG Fall 2022 Jam. That ran from September 21st to October 5th. The theme for this event was "Don't Stop", which inspired our team to create a fusion between Geometry Dash and a 3D rhythm game.

Initially, we wanted to create a game where the player controls a cube that's climbing up a tower. The player would have to change directions by hitting WASD in time to the rhythm of the song to progress up the tower and avoid crashing into a wall. The space key would be used to jump up onto higher platforms. Staying on beat would enable the player to achieve a higher score. 

This project was my first real venture in programming both isometric games and beat systems. Graham Tattersall's blog, 'Coding to the Beat', was a tremendous help in our development. You can read more on it here: https://www.gamedeveloper.com/audio/coding-to-the-beat---under-the-hood-of-a-rhythm-game-in-unity 

The beat manager tracks song position and controls other music synced actions. In the game, you'll see note blocks being instantiated on beat with the song. It was fun learning how to make use of dspTime, as I had the script read in a midi file so we could track note position without losing sync with the music.

We were even able to setup a basic beatmap for a song!

Play it here: [The Sick Game](https://ollie1616.itch.io/the-sick-game)

---
