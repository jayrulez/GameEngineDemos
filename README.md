# GameEngine Demos

Browser builds of games made with GameEngine
([jayrulez/GameEngine](https://github.com/jayrulez/GameEngine)), served by GitHub Pages at
**https://jayrulez.github.io/GameEngineDemos/**. They need WebGPU: a recent Chrome or Edge on a
computer.

## Sky Hopper

A 3D platformer across five floating islands: collect coins, stomp crabs, skulls and bees, dodge
saws and spiky balls, and reach the flag. Three lives for the whole run; stars and best scores are
saved in your browser. Keyboard (WASD, Space, Escape) or a gamepad.

**[Play Sky Hopper](https://jayrulez.github.io/GameEngineDemos/SkyHopper/)**

<p>
  <a href="https://jayrulez.github.io/GameEngineDemos/SkyHopper/"><img src="images/SkyHopper-Hud.png" width="32%" alt="Sky Hopper: jumping for a gem, the score rolling up"></a>
  <a href="https://jayrulez.github.io/GameEngineDemos/SkyHopper/"><img src="images/SkyHopper-Clear.png" width="32%" alt="Sky Hopper: the level clear card with its tally and stars"></a>
  <a href="https://jayrulez.github.io/GameEngineDemos/SkyHopper/"><img src="images/SkyHopper-Intro.png" width="32%" alt="Sky Hopper: a level's intro card"></a>
</p>

The engine's `Data/SampleProjects/PlatformerGame`. Credits and licences: `SkyHopper/CREDITS.md`
and `SkyHopper/Licenses/`.

## PaperKid

An arcade paper route: ride round a town block and throw papers onto the subscribers' porches
before time runs out, dodging cars, pedestrians, bins and cones. Five blocks, three lives, and a
minimap of the block. Keyboard (WASD, Space, Escape) or a gamepad.

**[Play PaperKid](https://jayrulez.github.io/GameEngineDemos/PaperKid/)**

<p>
  <a href="https://jayrulez.github.io/GameEngineDemos/PaperKid/"><img src="images/PaperKid-Play.png" width="32%" alt="PaperKid: riding a block, throwing a paper at a porch"></a>
  <a href="https://jayrulez.github.io/GameEngineDemos/PaperKid/"><img src="images/PaperKid-Title.png" width="32%" alt="PaperKid: the title screen"></a>
  <a href="https://jayrulez.github.io/GameEngineDemos/PaperKid/"><img src="images/PaperKid-Cleared.png" width="32%" alt="PaperKid: a block cleared"></a>
</p>

Watch it played on a Steam Deck: [PaperKid gameplay video](https://youtu.be/syJlmIirg_o).

The engine's `Data/SampleProjects/PaperKid`. Credits and licences: `PaperKid/CREDITS.md` and
`PaperKid/Licenses/`.

## Snowline

A snowboard time trial with tricks: carve through slalom gates, take the gems, and hit the kickers
for spins and grabs. Three courses opened by medals (Meadow, Forest with its shortcut through the
trees, and Ridge with a gap over a crevasse and an avalanche chasing you down); medal ghosts ride
beside you and your best run becomes your own ghost. Keyboard (A and D, Space, Left Shift, E,
Escape) or a gamepad.

**[Play Snowline](https://jayrulez.github.io/GameEngineDemos/Snowline/)**

<p>
  <a href="https://jayrulez.github.io/GameEngineDemos/Snowline/"><img src="images/Snowline-Ridge.png" width="32%" alt="Snowline: riding Ridge, the avalanche behind"></a>
  <a href="https://jayrulez.github.io/GameEngineDemos/Snowline/"><img src="images/Snowline-Title.png" width="32%" alt="Snowline: the title and its three courses"></a>
  <a href="https://jayrulez.github.io/GameEngineDemos/Snowline/"><img src="images/Snowline-Results.png" width="32%" alt="Snowline: a run's results"></a>
</p>

Watch it played on a Steam Deck: [Snowline gameplay video](https://youtu.be/vlxxLiMEzp0).

The engine's `Data/SampleProjects/Snowline`. Credits and licences: `Snowline/CREDITS.md` and
`Snowline/Licenses/`.

## How the builds are made

Each game folder is a web export straight from the engine: the project's Web export preset with the
Release web template, giving the page, the wasm player, its script and the content paks. To update
one, export again and replace the folder.
