# minecraft-client-optimizations
A client optimization guide for 1.16.x-1.17.x. Here's a list of the recommended Fabric mods you should install:

# [Sodium](https://github.com/CaffeineMC/sodium-fabric)
Sodium is a free and open-source optimization mod for the Minecraft client that improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft.

# [Starlight](https://github.com/Spottedleaf/Starlight)
Fabric mod for completely rewriting the vanilla light engine.

# [Lithium](https://github.com/CaffeineMC/lithium-fabric)
Lithium is a free and open-source Minecraft mod which works to optimize many areas of the game in order to provide better overall performance. It works on both the client and server, and doesn't require the mod to be installed on both sides.

# [FerriteCore](https://github.com/malte0811/FerriteCore)
This mod reduces the memory usage of Minecraft in a few different ways. A high-level technical description of the changes is available [here](https://github.com/malte0811/FerriteCore/blob/main/summary.md).

# [Krypton](https://github.com/astei/krypton)
Krypton is a Fabric mod that attempts to optimize the Minecraft networking stack. It derives from work done in the Velocity and Tuinity projects.

# [Lazydfu](https://github.com/astei/lazydfu)
LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" - that is, it will not immediately create the rules required to migrate data from older versions of Minecraft to newer versions until it actually needs to do so. It does not modify DFU and should be safe, but do exercise more than the usual caution.

# How to install
Firstly, you need to download Fabric. The guide and download link can be acquired here: https://fabricmc.net/use/. Once you have installed that, you just need to download the mods you want and drop them into the mod folder Fabric creates. A lot of mods require the Fabric API mod which can be downloaded here: https://www.curseforge.com/minecraft/mc-mods/fabric-api/files.

Download links for the mod jars:
* Sodium: https://github.com/CaffeineMC/sodium-fabric/releases
* Starlight: https://github.com/Spottedleaf/Starlight/releases
* Lithium: https://github.com/CaffeineMC/lithium-fabric/releases
* FerriteCore: https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric/download
* Krypton: https://github.com/astei/krypton/releases
* Lazyfdu: https://github.com/astei/lazydfu/releases
