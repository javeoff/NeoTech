# NeoTech

Neo Tech [+Modpack Server] - is a modern version of tech minecraft with 100+ quests, similar to old mod versions but with a new format.

![preview](https://cdn.modrinth.com/data/cached_images/3d976d36bc5521095b0021d55f2805e1c1047405.jpeg)

## Install modpack

- https://www.curseforge.com/minecraft/modpacks/neotech
- https://modrinth.com/modpack/neotech/versions

## Join server

1. Click to "Join Server" in the main menu
2. Or connect manually with IP: `85.192.56.57`

## Tech Mods:

- Mekanism + addons
- Applied Energetics 2 + addons
- Computer Craft + addons
- Modern Industrialization (IC2) + addons + resource pack
- AdAstra (Cosmos traveling) + addons
- Just Bees (Forestry)
- Immersive Engineering (Create)
- ExNihilo + ExMachines (Automate ore processing)
- Pneumatic Craft (Build Craft)
- Powah (IC2)
- Just Dire Things (Vanilla Like tech)

## Exploration Mods:

- AquaCulture 2
- The Aether
- The Undergarden
- Trofers
- Travelers Backpack
- Artifacts, Accesories
- Serene Seasons

## Magic Mods:

- Theurgy
- Occultism

## Architect Mods:

- Handcrafted (furniture)
- Chisel Reborn (More blocks)
- Chipped (More blocks)
- Building Gadget

## Create server by modpack

### Auto setup (recommended)

1. Fork the project
3. Pass secrets from .env.example to github "project secrets"
4. Make release to launch github actions

### Manual setup

1. Copy `docker-compose.yml` to the server
2. Copy .env.example to .env
3. Pass secrets
4. Remove .example from the config/Discord-Integration.toml.example and pass secrets
5. Run the command on the server `docker-compose up -d`

## FAQ

- How to install docker on a server?
  - install the docker by the script
  ```/bin/bash -c "$(curl -fsSL https://get.docker.com)"```
- How to give Operator?
  - you need to launch console 
  ```docker exec -i mc rcon-cli```

Discord: https://discord.gg/hRpBxF4ySz
