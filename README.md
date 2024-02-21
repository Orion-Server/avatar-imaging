# Nitro Imager

> This project is based on the [Nitro Imager for Docker](https://github.com/duckietm/docker-imager).
> Nitro Imager by [Billsonnn](https://github.com/billsonnn/nitro-imager)

# Installation

First, run the command to install all dependencies:

```cmd
yarn install
```

Then, copy the `.env.example` file to `.env` and fill in the necessary information.

#### Example:

```env
API_HOST=http://localhost
API_PORT=3030
IMAGER_PATH=/imaging
AVATAR_SAVE_PATH=C:/my/imager_path/src/saved_figures
AVATAR_ACTIONS_URL=C:/my/assets_path/gamedata/HabboAvatarActions.json
AVATAR_FIGUREDATA_URL=C:/my/assets_path/gamedata/FigureData.json
AVATAR_FIGUREMAP_URL=C:/my/assets_path/gamedata/FigureMap.json
AVATAR_EFFECTMAP_URL=C:/my/assets_path/gamedata/EffectMap.json
AVATAR_ASSET_URL=C:/my/assets_path/bundled/figure/%libname%.nitro
AVATAR_ASSET_EFFECT_URL=C:/my/assets_path/bundled/effect/%libname%.nitro
```

Replace the `C:/my/imager_path` and `C:/my/assets_path` with your path's.

# Build

To build the project, run the command:

```cmd
yarn build
```

# Run

To run the project, run the command:

```cmd
yarn start
```