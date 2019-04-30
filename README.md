# Les Frères Super Guy

![Les Frères Super Guy](https://raw.githubusercontent.com/lux/Super_Guy/master/les-freres-super-guy.png)

Par Alyson Shane et John Luxford. Basé sur uMario_Jakowski, un clone de Mario
en C++/SDL2 par Łukasz Jakowski.

La musique

* [Alouette](https://en.wikipedia.org/wiki/Alouette_(song))
* [Gens du pays](https://en.wikipedia.org/wiki/Gens_du_pays)
* [Log driver's waltz](https://www.youtube.com/watch?v=upsZZ2s3xv8)
* [Sur le pont d'avignon](https://en.wikipedia.org/wiki/Sur_le_Pont_d%27Avignon)
* [V'la l'bon vent](https://www.thecanadianencyclopedia.ca/en/article/vla-lbon-vent-emc)

Tabarnak par [Bob Gratton](https://www.youtube.com/watch?v=MIFvgSCzg4E).

---

## uMario_Jakowski

Author: Łukasz Jakowski

WWW: http://lukaszjakowski.pl
Email: jakowskidev@gmail.com

EXE and DLL - Download: http://lukaszjakowski.pl/DL/uMario.zip

YouTube video: https://www.youtube.com/watch?v=jya5He7KFsE


It is my first game made in C++.

Visual Studio 2012
SDL Tutorials which I have used:
http://lazyfoo.net/tutorials/SDL/index.php


My Google Play account: https://play.google.com/store/apps/dev?id=4635849298843013993


## Build Pre-requisites

FreeBSD:

    $ pkg install cmake sdl2 sdl2_image sdl2_mixer

OS X (brew):

    $ brew install cmake sdl2 sdl2_image sdl2_mixer

## Building and running

    $ make build run

    # or

    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ ./uMario
