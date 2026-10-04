# Raptor Demos

Browser builds of games made with the Raptor engine
([jayrulez/GameEngine](https://github.com/jayrulez/GameEngine)), served by GitHub Pages at
**https://jayrulez.github.io/GameEngineDemos/**.

- `SkyHopper/`: Sky Hopper, a 3D platformer (the engine's `Data/SampleProjects/PlatformerGame`).
  Its third-party assets and their licences are in `SkyHopper/CREDITS.md` and `SkyHopper/Licenses/`.

Each game folder is a web export straight from the engine (the project's Web export preset, the
Release web template): the page, the wasm player, its script, and the content paks. To update one,
export again and replace the folder. The games need WebGPU (recent Chrome or Edge on desktop).
