# minecraft-client-optimizations
A client optimization guide for 1.16.x-1.20.x. Here's a list of the recommended Fabric mods you should install:

# [Sodium](https://modrinth.com/mod/sodium)
Sodium is a free and open-source optimization mod for the Minecraft client that improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft.

# [Sodium Extra](https://modrinth.com/mod/sodium-extra)
Sodium Extra aims to bring most of OptiFine's eye-candy options to Sodium; in addition to providing some features such as visual bug fixes and other performance options that are not yet available on Sodium.

# [Starlight](https://modrinth.com/mod/starlight)
Fabric mod for completely rewriting the vanilla light engine.

# [Lithium](https://modrinth.com/mod/lithium)
Lithium is a free and open-source Minecraft mod which works to optimize many areas of the game in order to provide better overall performance. It works on both the client and server, and doesn't require the mod to be installed on both sides.

# [FerriteCore](https://modrinth.com/mod/ferrite-core)
This mod reduces the memory usage of Minecraft in a few different ways. A high-level technical description of the changes is available [here](https://github.com/malte0811/FerriteCore/blob/main/summary.md).

# [Krypton](https://modrinth.com/mod/krypton)
Krypton is a Fabric mod that attempts to optimize the Minecraft networking stack. It derives from work done in the Velocity and Tuinity projects.

# [EntityCulling](https://modrinth.com/mod/entityculling)
Minecraft skips rendering things that are behind you, so why is it rendering everything that you still can't see because of a wall in the way? This mod utilizes your other CPU cores/threads to do really quick path-tracing from your camera to all tile/-entities to determine rather they are visible or not. During the rendering, the not visible ones will be skipped the same way entities behind you are.

# [Immediately Fast](https://modrinth.com/mod/immediatelyfast)
ImmediatelyFast is an open source Fabric mod which improves the immediate mode rendering performance of the client. It is designed to be lightweight and compatible with other mods. This makes it an ideal choice for modpacks or as a replacement for other more aggressive optimization mods such as Exordium or Enhanced Block Entities.

# [Dynamic FPS](https://modrinth.com/mod/dynamic-fps)
Dynamic FPS automatically reduces the speed at which minecraft renders when it's not focused (to 1 FPS) or hidden (no renders at all). It also fixes a bug in Vanilla Minecraft that makes it take much more performance in the background than it should.

# How to install
To start, download the Fabric modloader here: https://fabricmc.net/use/. After installing and launching Fabric for the first time, a mods folder will be generated in your Minecraft installation directory (e.g. Windows: %appdata%/Roaming/.minecraft). From here, find and download the mods you desire and place them into the mods folder. Most mods require the Fabric API mod which can be found here: https://modrinth.com/mod/fabric-api.

Official GitHub links (in case links above no longer work):
* Sodium: https://github.com/CaffeineMC/sodium-fabric/releases
* Starlight: https://github.com/Spottedleaf/Starlight/releases
* Lithium: https://github.com/CaffeineMC/lithium-fabric/releases
* FerriteCore: https://github.com/malte0811/FerriteCore
* Krypton: https://github.com/astei/krypton/releases
* EntityCulling: https://github.com/tr7zw/EntityCulling/releases
* Immediately Fast: https://github.com/RaphiMC/ImmediatelyFast/releases
* Dynamic FPS: https://github.com/juliand665/Dynamic-FPS/releases
