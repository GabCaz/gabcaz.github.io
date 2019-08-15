---
title: "My Implementation of the 2048 Game"
tags:
  - Java
  - Programming
---

When I followed [University of Pennsylvania's CIS110][cis110-syllabus], I chose to think of an implementation of the [2048 game][2048-wikipedia] for my final project.

The objective was to write clean, well organised object-oriented code. You can find my corresponding GitHub repository [here][2048-GitHub].

I structured the project as follows:
- The Tile class implements the Tile object, that represents individual Tiles
- The Board class implements the Board object, that simulates the
    group of Tiles when considered together, and how they interact
- TileInterface.java describes the API for the Tile class
- BoardInterface.java describes the API for the Board class
- TwoThousandFortyEight.java coordinates these different objects and calls the
    right methods on it depending on the input from the user so as to actually
    simulate a 2048 game


[cis110-syllabus]: http://www.cis.upenn.edu/~cis110/19su/syllabus.html
[2048-wikipedia]: https://en.wikipedia.org/wiki/2048_(video_game)
[2048-GitHub]: https://github.com/GabCaz/2048
