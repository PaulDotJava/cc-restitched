<img src="logo.png" alt="CC: Restitched" width="100%"/>


[![Download CC: Restitched on CurseForge](https://cf.way2muchnoise.eu/title/cc-restitched.svg?badge_style=for_the_badge)](https://www.curseforge.com/minecraft/mc-mods/cc-restitched "Download CC:  Restitched on CurseForge")
[![Download CC: Restitched via Modrinth](https://img.shields.io/badge/dynamic/json?color=5da545&label=modrinth&prefix=downloads%20&query=downloads&url=https://api.modrinth.com/api/v1/mod/cc-restitched&style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMSAxMSIgd2lkdGg9IjE0LjY2NyIgaGVpZ2h0PSIxNC42NjciICB4bWxuczp2PSJodHRwczovL3ZlY3RhLmlvL25hbm8iPjxkZWZzPjxjbGlwUGF0aCBpZD0iQSI+PHBhdGggZD0iTTAgMGgxMXYxMUgweiIvPjwvY2xpcFBhdGg+PC9kZWZzPjxnIGNsaXAtcGF0aD0idXJsKCNBKSI+PHBhdGggZD0iTTEuMzA5IDcuODU3YTQuNjQgNC42NCAwIDAgMS0uNDYxLTEuMDYzSDBDLjU5MSA5LjIwNiAyLjc5NiAxMSA1LjQyMiAxMWMxLjk4MSAwIDMuNzIyLTEuMDIgNC43MTEtMi41NTZoMGwtLjc1LS4zNDVjLS44NTQgMS4yNjEtMi4zMSAyLjA5Mi0zLjk2MSAyLjA5MmE0Ljc4IDQuNzggMCAwIDEtMy4wMDUtMS4wNTVsMS44MDktMS40NzQuOTg0Ljg0NyAxLjkwNS0xLjAwM0w4LjE3NCA1LjgybC0uMzg0LS43ODYtMS4xMTYuNjM1LS41MTYuNjk0LS42MjYuMjM2LS44NzMtLjM4N2gwbC0uMjEzLS45MS4zNTUtLjU2Ljc4Ny0uMzcuODQ1LS45NTktLjcwMi0uNTEtMS44NzQuNzEzLTEuMzYyIDEuNjUxLjY0NSAxLjA5OC0xLjgzMSAxLjQ5MnptOS42MTQtMS40NEE1LjQ0IDUuNDQgMCAwIDAgMTEgNS41QzExIDIuNDY0IDguNTAxIDAgNS40MjIgMCAyLjc5NiAwIC41OTEgMS43OTQgMCA0LjIwNmguODQ4QzEuNDE5IDIuMjQ1IDMuMjUyLjgwOSA1LjQyMi44MDljMi42MjYgMCA0Ljc1OCAyLjEwMiA0Ljc1OCA0LjY5MSAwIC4xOS0uMDEyLjM3Ni0uMDM0LjU2bC43NzcuMzU3aDB6IiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGZpbGw9IiM1ZGE0MjYiLz48L2c+PC9zdmc+)](https://modrinth.com/mod/cc-restitched "Download CC:  Restitched via Modrinth")
[![Gitpod ready-to-code](https://shields.io/badge/gitpod-ready--to--code-green?logo=gitpod&style=for-the-badge)](https://gitpod.io/#https://github.com/cc-tweaked/cc-restitched)
[![Current build status](https://github.com/cc-tweaked/cc-restitched/workflows/Build/badge.svg)](https://github.com/cc-tweaked/cc-restitched/actions "Current build status")

# What is CC: Restitched?
This is a port of [cc-tweaked/cc-tweaked](https://github.com/SquidDev-CC/CC-Tweaked) to the Fabric modloader as well as being a continuation of [JemmaZZ/cc-tweaked-fabric](https://github.com/JemmaZZ/cc-tweaked-fabric).

## CC: Restitched vs. CC: Tweaked
CC: R tries to maintain parity with CC: T, but may be behind or divergent in some areas. If you notice a disparity please open an issue. CC: R major and minor version numbers indicate parity with the major features of that version of CC: T. Patch version numbers will not align.

## Resource Packs
This mod includes textures by [Jummit](https://github.com/Jummit) that are more in line with the style of Mojang's new texture-artist, Jappa. If you prefer the original textures you should  enable the "Classic" resource pack.
<img src="https://raw.githubusercontent.com/cc-orgs/cc-overhaul/main/pack.png" alt="CC: Restitched" width="32"  height="32"/> We also have a third resourcepack made by [3prm3](https://github.com/3prm3), it features a complete overhaul of CC's textures (in the style of an industrial mod) and can be used by enabling the `overhaul` resource pack. You can also check out his resource pack over [here](https://github.com/cc-orgs/cc-overhaul/tree/main) as  well!

## Bleeding Edge Ver.
Bleeding edge builds can be found [here](https://github.com/cc-tweaked/cc-restitched/actions) at Github Actions.
In the .zip file there should be a `-dev` jar, a `-javadoc` jar, a `-sources-dev` jar, a `-sources` jar, and a "plain" jar (jar without an affixed tag) jar.
Put the "plain" jar in the mods folder.

## Contributions
Any contribution is welcome, be it using the mod, reporting bugs or contributing code. In order to start helping develop CC: R there are a few rules;
1) Follow the [Fabric](https://fabricmc.net/) programming guidelines as close as possible. This means you have to use [`loom`](https://fabricmc.net/wiki/tutorial:mappings) mappings, if you use anything else, your code will be rejected.
2) Make sure your code follows the checkstyle rules. You can test this by running `./gradle build` or `./gradle check`.
3) You cannot intentionally implement bugs and security vulnerabilities.
4) Unless the code is taken directly from CC: Tweaked, `lua` code is offlimits from alteration. If you wish to contribute your changes to the in game rom please contribute upstream at [CC-Tweaked](https://github.com/SquidDev-CC/CC-Tweaked).
5) Branches should be named in this format `mc-<major ver.>.x/<specific-mc-ver.>`

# Rendering Mod Compatability
* [ YES ] [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium)
* [ YES ] [OptiFabric](https://www.curseforge.com/minecraft/mc-mods/optifabric)
	* Works with VBO Rendering (automatically set)
	* No issues
* [ OK ] [Iris Shaders & Sodium](https://www.curseforge.com/minecraft/mc-mods/irisshaders)
	* "Works" with TBO Rendering (Default)
	* Works with VBO Rendering
* [ YES ] [Canvas](https://www.curseforge.com/minecraft/mc-mods/canvas-renderer)
	* Works with TBO Rendering (Default)
	* Scuffed with VBO Rendering
	* <details>
		<summary>VBO is broken</summary>

  		Monitors are just... scuffed beyond belief.
		- ![](https://i.imgur.com/JVNZ2Pn.png)
		- ![](https://i.imgur.com/SXXpr54.png)
			* The content to the left is supposed to be on the monitors to the right, also the bottom one is supposed to `black/white` not colored.
		* Turtle Texture for some reason?
			- ![](https://i.imgur.com/OEmZXsx.png)
		</details>

## Community
If you need help getting started with CC: Restitched, want to show off your latest project, or just want to chat about ComputerCraft, here is the [Computercraft Forum](https://forums.computercraft.cc/) and the Computer Mods [Discord!](https://discord.gg/H2UyJXe). There is also a wiki that can be found at [https://tweaked.cc/](https://tweaked.cc/)

## Perpheral Mods
Unfortunately, CC: Restitched does not have as many peripherals mods available as CC: Tweaked. If you're an interested mod developer, please check out our `api` package. If you've already made a mod with CC: R peripheral support OR if you're a player who found a mod with CC: R integration, please open an [issue here](https://github.com/cc-tweaked/cc-restitched/issues/new?assignees=&labels=peripheralShoutout&template=peripheral_shoutout.md) to let us know and we'll add it to the list!
