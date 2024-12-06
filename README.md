# MCTPMS

Realistic textures & 3D models for Minecraft JE.

<p align="right">
  <img
    src="https://github.com/andrejsharapov/mctpms/blob/main/pack.png?raw=true"
    alt="pack 128x128"
    width="128">
</p>

## Preview

Several videos about creating a texture pack.

| How models are created                        | Textures in the game                                 |
| --------------------------------------------- | ---------------------------------------------------- |
| [![Youtube][youtube-img-sm]][youtube-watch-1] | [![Youtube][youtube-playlist-img]][youtube-playlist] |

> [!TIP]  
> Join us on discord to discuss the texture pack, offer ideas, or just talk about your favorite game.  
> Find out more in [Discord][discord].

## How it works?

You can study the models you need yourself, for example, a [crafting table](https://github.com/andrejsharapov/mctpms/blob/main/assets/minecraft/models/block/crafting_table.json) model, copy the files and use them in your texture pack with your images.

To create more complex models, you can use the [mine-campfire](https://github.com/andrejsharapov/mine-campfire/tree/main/assets/minecraft) package as an example.

> [!NOTE]  
> This repo contains models of blocks and items, but does not contain ready-made textures (images) for them.

## Releases

- [ ] 1.19.x
- [ ] 1.20.x
- [x] 1.21.1
- [x] 1.21.3
- [x] 1.21.4
- [ ] 1.2x.x

## What version of the pack do I have?

See the pack version in the description:

```js
{
  "pack": {
    "description": "🦄 MCTPMS for Minecraft JE v1.gg.g \n\u00A73Realistic 3d textures \u00A78v3.p.pp"
  }
}
```

`v1.gg.g` - game version  
`v3.p.pp` - pack version

## How to update to the latest version?

We try to update the package version in a timely manner, but if you see that the game version has changed, you can update the package yourself.

1. Unzip `mctpms.zip` file with textures;
2. Find and open `pack.mcmeta` through text editor;
3. Change `pack_format` to the [latest version](https://minecraft.wiki/w/Pack_format#List_of_resource_pack_formats) of the game.

```js
{
  "pack": {
    "pack_format": 46,
  }
}
```

## Bugs

If you find a bug in the models/textures or have suggestions for improving the pack, please [report it here](https://github.com/andrejsharapov/mctpms/issues) or in our [discord][discord].

## Addons MCTPMS

| Pack                                 | 3D models | Caption                                                | Game version |
| ------------------------------------ | --------- | ------------------------------------------------------ | ------------ |
| [mctpms-campfire][mctpms_campfire] ↗ | true      | Adds a variety of campfires to the Minecraft.          | > 1.15.x     |
| [mctpms-fences][mctpms_fences] ↗     | true      | Change the standard appearance of fences in Minecraft. | > 1.17.x     |
| [mctpms-gui][mctpms_gui] ↗           | false     | Map, GUI and particles.                                | > 1.21.3     |
| [mctpms-mobs] ↗                      | false     | Add animals, mobs, villagers, etc.                     | > 1.21.3     |

<!-- links -->

[mctpms_campfire]: https://github.com/andrejsharapov/mine-campfire
[mctpms_fences]: https://github.com/andrejsharapov/mine-fences
[mctpms_gui]: https://www.mediafire.com/file/ljs5wolviw65uox/mctpms-gui.zip/file

<!--
[mctpms_mobs]: 
-->

[discord]: https://discord.gg/En8KcxdDra

[youtube-img-sm]: https://github.com/user-attachments/assets/e407f1ca-e7a1-4d4d-85da-2ddcf077daa0
[youtube-watch-1]: https://www.youtube.com/playlist?list=PLZEJODWNKrCdHqHy7JWpTOI-PMl64PuC7

[youtube-playlist]: https://youtube.com/playlist?list=PLAdfPZXFJ1lI8ZlhJK-MUHcSs84TM93Y1&feature=shared
[youtube-playlist-img]: https://github.com/user-attachments/assets/98a6933f-7e8a-44d1-84ba-1630ddb12ab0
