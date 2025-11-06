1. About
God Clash is pvp local game made with Unity game engine, it consists of astronaut (first player, Saturn god of time), terrain of matrix-like placed blocks that astronaut can move on and finish which is at start
placed on most distanced block from astronat.
Goal for Saturn is simple, reach the finish by crossing terrain using wasd keys or arrow keys for moving in 2d space before time runs out.
While on the other hand, opposing player (second plaer, Jupyter god of space) wins if time runs out before astronaut reaches finish.
Jupyter have 2 abilities, first one being ability to arise mentioned blocks and by doing that "walls" are created on terrain which makes crossing terrain more difficult.
Jupyter can arise blocks by dragging mouse over grounded blocks while holding left-click.
This is balanced by limiting Jupyter with how many blocks can be arised at the moment, so when limit is exceeded, first block that was elevated will fall down and become ground that astrounaut can again walk on.
Jupyter can never trap astronaut in walls and make reaching finish impossible because his goal is not to make reaching finish for astronaut imposible, but harder.
Second ability of Jupyter can be used only once, and it is ability to move finish by clicking right click with mouse on grounded block.
Saturn have one ability which is to teleport astronaut where he was 5 seconds ago. This ability have cooldown of 5 seconds and is used to trick Jupyter and make reaching finish easier.
There is clone of astronaut that follows real astronaut and is representing where he was 5 seconds ago so it makes easier to tell where astronaut will be teleported by using ability.
2. Implementation
