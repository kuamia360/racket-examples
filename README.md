# racket-examples
A set of example Racket games, mostly created to help me learn Racket, but maybe useful to others?

My starting place for learning Racket was the books: Realm of Racket http://www.realmofracket.com/, The Little Schemer and The Seasoned Schemer https://mitpress.mit.edu/books/little-schemer-fourth-edition

After that I created a set of games / demos (which you'll find in this repo), to help me prove I understood the principles and explore the language further. The games are pretty basic, but hopefully interesting to explore.

Some thoughts on Racket:

* I found each game pretty hard to write (my background is Python and other procedural languages) but surprising low in defects once complete. 
* After getting over the lack of objects I found the functional approach produced a simpler design (although not necessarily easier to produce).
* When making a game do objects and mutable state better model what's going on?

Contents:

* `asteroids` -- a simple arcade game.

![asteroids screen shot](/images/asteroids5.png)

* `learn-music` -- learn to read music with the guitar. Read more on my blog: http://ericclack.blogspot.co.uk/2015/12/learn-to-read-music-with-racket-scheme.html

* `learn-music-phrase` -- like `learn-music` but presents sequences of notes to practice.

* `stars` -- experiments with very basic 3d graphics, including stars and aliens with random 3d paths.

![stars screen shot](/images/stars7.png)

Many of the app filenames have numbers, these indicate major changes -- 
so it's easy to look back at previous, simpler versions.
