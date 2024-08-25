# BetterPortals


1.21 support added(i think) Jar in releases

## ***NO SUPPORT OFFERED***  


BetterPortals is a minecraft spigot plugin which allows you to see through nether portals to look at the blocks on the other side.

It aims to provide a similar experience to the BetterPortals mod, but as a plugin, so it requires no client side mods.

This works pretty well for players with low ping (under 50 ms), and portal animations are pretty smooth.

For more info, see the plugin's [Spigot Page](https://www.spigotmc.org/resources/betterportals.75409/)

## Features
- Viewing blocks through nether portals.
- Viewing entities through portals.
- Creating your own custom portals (in a way like MultiversePortals).
- Horizontal custom portals.
- Creating portals between multiple servers. (AKA cross-server portals)

## Limitations
Of course, being a plugin, there are several limitations.
- Portal animations can lag players if not using optifine.
- Players with high ping see artifacts of the portal projection.
- Much longer render distances lag both players and the server.

## Future Plans
- Improve performance to allow for much longer render distances.

## Compilation
Requirements to build:
- [Gradle](https://gradle.org/install/) 7 or higher installed and on `PATH`.
- Java 8 or higher on `PATH` and `JAVA_HOME` also set to point to the folder containing the bin folder.

1. Clone this repository (either via the `Code` dropdown on github and then downloading ZIP, or through `git clone https://github.com/Lauriethefish/BetterPortals.git`).
2. If you want to add the commit hash to the version number (i.e. have the JAR be considered a "dev build"), then set the `BP_DEVELOPER_BUILD` environment variable to `1`.
3. Run `gradle build` in the project root.
4. The shaded JAR is found in `./final/build/libs/`. Make sure to pick the JAR with `-all` at the end, otherwise you will not get all of the necessary dependencies. [Example](https://i.imgur.com/yVYI1IW.png)
