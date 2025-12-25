# A Lost Travelor

This is a 2D Dungeon Crawler game, where the player enters a last stand to clear as many waves of enemies as possible. The player is able to control a character, who is an accidental time traveler and wishes to return home. The interface is a GUI that displays the UI, abilities, map, player, and enemies. There will be a never-ending sequence of rooms that each contain enemies for the player to clear in order to progress. However, as you venture farther into the rift of time, you will begin to notice that each room will gradually increase in difficulty as the enemies grow stronger and faster.

## Instructions to install and run:

### Install OPAM packages
```terminal
$ opam update
$ opam upgrade
$ opam install graphics
```
### Running the program
```terminal
$ dune exec bin/main.exe
```

For MacOS, if you can't open the display using ```dune exec bin/main.exe```, then download xQuartz from https://www.xquartz.org/

If necessary, restart the computer after downloading xQuartz, and then run ```dune exec bin/main.exe```

### Packages and Libaries

- The Ocaml [Graphics](https://ocaml.org/manual/4.03/libref/Graphics.html) Module/Library was used
- The [OUnit2](https://ocaml.org/p/ounit2/2.2.3/doc/index.html) OCaml unit testing framework was used for 90%+ code coverage 

## Features

- WASD movement
- shooting projectiles
- health and health regeneration
- infinite gameplay loop
- increasing level difficulty

### Contributors

William Liu (Project Lead & Backend Programmer)  
David Chen (Front-end Programmer)  
Ivan Dong (Programmer)  

