# Nautilus: Subnautica Modding API

![banner](https://user-images.githubusercontent.com/71298690/233505405-e89fbc70-31c9-45a2-bb31-64e1f498d4a7.png)

[![NuGet](https://img.shields.io/nuget/vpre/Subnautica.Nautilus)](https://www.nuget.org/packages/Subnautica.Nautilus)
[![Discord](https://img.shields.io/discord/324207629784186882?logo=discord&logoColor=white)](https://discord.gg/UpWuWwq)
[![GitHub contributors](https://img.shields.io/github/contributors/SubnauticaModdings/Nautilus?style=flat-square)](https://github.com/SubnauticaModdings/Nautilus/graphs/contributors)
[![License](https://img.shields.io/github/license/SubnauticaModdings/Nautilus?style=flat-square)](https://github.com/SubnauticaModdings/Nautilus/blob/master/LICENSE.md)

## Contents
- [🌐 About](#about)
- [⬇️ Installation](#installation)
- [📚 Resources / links](#links)
- [🤝 Contributing](#contributing)

## About

Nautilus is a modding library that aims to enhance developer productivity by offering common helper utilities as easy to use and robust as possible.
Notable systems which Nautilus offers include but not limited to: Adding/editing items, implementing custom sprites & textures, custom audio, Subnautica-style configuration menu, and so much more!  

This project was derived from SML Helper with an improved codebase and maintainability. Nautilus offers all the features SML used to offer in a more robust implementation.
Additionally, Nautilus took another route of managing handlers to fix many bugs and timing issues that were persistent in SML.  
We hope to keep improving the modding experience in Subnautica to allow developers to create mods more easily and eliminate the implementation concerns in the mod-making process.

### ⚠️ Nautilus is only supported on the latest version of Subnautica. If you're playing on the Legacy branch of Steam, use SML Helper instead (https://www.nexusmods.com/subnautica/mods/113).

## Installation
1. Download the [Subnautica BepInEx Pack](https://www.nexusmods.com/subnautica/mods/1108).  
   Install it by extracting the contents of the zip into your <b>Subnautica folder</b>:
   - Steam - `C:\Program Files (x86)\Steam\steamapps\common\Subnautica` (default path)
   - Epic Games - `C:\Program Files\Epic Games\Subnautica` (default path)
   - Xbox  PC - `C:\XboxGames\Subnautica\Content` (default path)
   
2. Download Nautilus from here: 
   1. Drag and drop the `plugins` folder in the zip into your `BepInEx`folder located in `PathToSubnautica\BepInEx\`.
   2. It should end up like this: `PathToSubnautica\BepInEx\plugins\Nautilus\`

## Links
* Developer resources:
  * [Documentation](https://subnauticamodding.github.io/Nautilus) ([source](https://github.com/SubnauticaModdings/Nautilus/tree/docs/Nautilus/Documentation))

## Contributing
Please read through our [Contribution Guidelines](CONTRIBUTING.md) before submitting a pull request. We welcome all kinds of contributions.  
If you have an idea for a feature or a bug to report but are not capable of writing code, [submit an issue](https://github.com/SubnauticaModdings/Nautilus/issues/new) instead.
