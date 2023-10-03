<div align="center">
    <img src="https://images-ext-2.discordapp.net/external/aIBRjVfZJAGn2awfso3GY3kadhMQlVupqLEwnKGD3OE/https/repository-images.githubusercontent.com/55325103/2bed6800-bfef-11eb-835b-99b981918623?width=300&height=260"/>
    <div>&nbsp;</div>
    <a href="[https://www.roblox.com/library/7510622625](https://www.roblox.com/library/7503263693/vM-Loader)/">
        <img src="https://img.shields.io/static/v1?label=roblox&message=model&color=blue&logo=roblox&logoColor=white"/>
    </a>
    <a href="https://github.com/Sceleratis/Adonis/releases">
        <img src="https://img.shields.io/github/v/release/Sceleratis/Adonis?label=version"/>
    </a>
    <a href="https://discord.gg/H5RvTP3">
        <img src="https://img.shields.io/discord/81902207070380032?label=discord&logo=discord&logoColor=white"/>
    </a>
</div>
<hr/> 

Adonis is a server moderation and management system created for use on the Roblox platform.

## Installation

### Main Method: Official Roblox Model

* [Take a copy](https://www.roblox.com/library/7503263693/) of the Adonis loader model from the Roblox library

* Insert the model into Studio using the Toolbox into `ServerScriptService`
  ***Main Module***
  [Download](https://www.roblox.com/library/7503242924/)

## Debug Mode

The Adonis loader provides a `DebugMode` option which will load a local copy of the `MainModule` rather than fetching the latest version. This could be useful if you want to stay on a particular version of Adonis or want to maintain a custom version for your game. Debug mode expects the `MainModule` to share the same parent with the loader model (e.g. both should be in `ServerScriptService`). **By default, snapshots provided in  releases have `DebugMode` enabled.**

