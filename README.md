Chisel
=======

Chisel is a mod for Minecraft which adds adds a huge variety of static blocks to 
the game. It uses a lot of textures from the Painterly pack: http://painterlypack.net/

This repository is a fork of the original mod by AUTOMATIC_MAIDEN:
  http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1288400-chisel


Compiling
---------

In order to compile the mod, you should use gradle as described at:
  http://www.minecraftforge.net/wiki/Installation/Source#Installation


Or in short:
```
./gradlew setupDecompWorkspace --refresh-dependencies
./gradlew eclipse
```
Then go into eclipse, select "Import" and "Existing Projects into Workspace", select 
the folder where this source is located and start coding. Once you are done, create a 
jar file by using the command:

```
  ./gradlew reobf
```
