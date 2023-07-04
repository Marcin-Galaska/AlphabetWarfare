# AlphabetWarfare
 A tanks-like game made only with basic logic elements, i.e. logic gates, comparators, bit shifters etc. Developed fully in Logisim.

 ### Concept
  There is a significant chance you have played a game of 'Tanks' or 'Dog vs Cat' during your childhood. This project expands this idea, using simple logic components. Two players, represented as letters 'A' and 'B', try to snipe each other by setting the angle and force of their shot, directed to the opponent. The terrain and positions of the players are randomly generated each match. Each player has 3 lives, and whoever shoot the other one thrice - wins. This time, however, to spice things up, there is a wall in the middle of the arena, which changes its shape and position at the start of each round (a round being a turn of player A and B).

Sample footage from ongoing match:

https://github.com/Marcin-Galaska/AlphabetWarfare/assets/106023363/85ea2b61-3075-44d6-b3f1-f75e1192b038

### Files
 The first file is TerrainGeneration.circ, which, as its name suggests, generates the terrain on the screen, adds the moving wall obstacle and places the players in this created world. The player characters' position on the X and Y axes are also randomly drawn from within certain boundaries.
  The second file, ShootingSystem.circ, is responsible for the logic of the game.
  Finally the last file, Game.circ contains all the components packed and linked, allowing the player to boot up this file and enjoy this prototype.

 ### Documentation
  The documentation for the environment itself is available at
  http://www.cburch.com/logisim/docs/2.7/en/html/libs/index.html
  While the custom mechanisms and structures withing the project are commented and described within the first two files.
  
  ![image](https://github.com/Marcin-Galaska/AlphabetWarfare/assets/106023363/cee300bd-3757-443c-8e72-537ec9d3711f)

Have fun!

### License
BSD 2-Clause License

Copyright (c) 2023, Marcin Gałąska <br>
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.
