As-Toroids: Higher-Genus Asteroids
==================================

This game is a quick experiment to see what it's like to play the classic
video game [Asteroids](https://en.wikipedia.org/wiki/Asteroids_(video_game)
on higher-genus surfaces, beyond the usual torus.  Regular Asteroids is played
on a rectangular screen where anything flying off the top side of the screen
returns at the same coordinate on the bottom side of the screen, and similarly
for the left and right sides.  This usual connectivity describes the
[flat torus](https://en.wikipedia.org/wiki/Torus#Flat_torus).

This game implements a different boundary condition that defines a
[genus-*g* orientable surface](https://en.wikipedia.org/wiki/Torus#Genus_g_surface) for any *g* (not just 1).
It all started when [Jeff Erickson](http://jeffe.cs.illinois.edu/) said
(on June 20, 2019) "what we really need is Asteroids on a double torus".
An early version of this implementation emerged less than an hour later,
thanks to input from Erin Wolf Chambers, David Eppstein, and Jeff Erickson.

The code is a very light edit of the excellent
[Asteroids [Reloaded]](http://www.kevs3d.co.uk/dev/asteroids)
developed by [Kevin Roast](http://www.kevs3d.co.uk/).
All credit for the gameplay, graphics, sound, etc. goes to him!
The main purpose of this experiment is as an educational tool
for teaching topology.

You can [play the game online](https://edemaine.github.io/as-toroids/index-debug.html).
If you want to run this code locally, run the game from within a local webserver for the sound/message file loading to work correctly.
e.g. localhost:8080/Asteroids-Reloaded/index.html

All game graphics, all sounds, and most code is
Copyright (c) 2014 Kevin Roast kevtoast@yahoo.com.
[Some changes to the code](https://github.com/edemaine/as-toroids/commits/master)
are Copyright (c) 2019 Erik Demaine edemaine@mit.edu.
