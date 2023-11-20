![Banner image](https://raw.githubusercontent.com/emmaexe/all-the-horrors/main/assets/banner.png)

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/license/gpl-3-0/)

# All The Horrors

**A minecraft modpack with horror, QoL and optimization mods to make the game fast, beautiful and terrifying.**

> Embark on a chilling adventure with "All The Horrors", a Minecraft modpack that plunges the game into a relentless horror experience. As day turns to night, brace yourself for a world where new and old mobs relentlessly hunt you down. Nowhere is safe in this darkened realm, as you navigate desolate landscapes, armed with only your wits against haunting creatures. Will you emerge unscathed, or become another victim in this nightmarish version of Minecraft?

<details>
    <summary>Version warning!</summary>
    This modpack is in a pre-release state. Until it reaches version 1.0.0, mods may be added and removed as the experience the modpack provides is getting tweaked according to beta testers' feedback.
</details>
<br>

**Beta Tester Quotes:**

> I like it. I mean... like, I hate it because I don't like getting jumpscared, but like if you're asking for opinions on how scary it is, I'd say it is like 10/10 scary.

\- [Shiitakeii](https://www.twitch.tv/shiitakeii)

## FAQ

### How do I install it?

The best way would be via the [modrinth page](https://modrinth.com/modpack/all-the-horrors) or [github releases](https://github.com/emmaexe/all-the-horrors/releases). You will need a launcher that supports either modrinth or curseforge packs. We recommend [Prism Launcher](https://prismlauncher.org/) due to its focus on easy managment of modpacks and instances. In Prism Launcher, on the main interface click on the Add Instance button and select Modrinth as the source. Search for the modpack, select a custom version if you want and click OK to add it.

### Issue with *HT's treechop* / *Jade* ?

There is currently a known issue with HT's treechop where jade does not correctly display the different stages of a tree getting chopped down. The developers of the mods are working on the issue.

## Compile

This project uses [packwiz](https://packwiz.infra.link/) and requires it for compiling.

Clone the project and enter the forge directory:

```bash
  git clone https://github.com/emmaexe/all-the-horrors
  cd all-the-horrors/forge
```

You can compile the project into the modrinth modpack format (recommended) or the curseforge modpack format:

```bash
  packwiz modrinth export
```

```bash
  packwiz curseforge export
```

The packwiz commands should create a .mrpack or .zip file containing the modrinth/curseforge modpack in the root of the forge folder.

## Feedback and support

If you need support or have any feedback, you can open a pull request or issue on the [github page](https://github.com/emmaexe/all-the-horrors/issues), or join the [discord](https://discord.gg/nDPrSyG5py) or [matrix (WIP)](https://matrix.to/#/#emmaexe-server:matrix.org) servers.

## Authors

- [@emmaexe](https://www.emmaexe.moe/)
