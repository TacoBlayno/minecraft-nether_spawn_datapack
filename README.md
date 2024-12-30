# Nether Spawn Datapack
Makes the player start in the Nether instead of the Overworld. Currently only provides Java edition support. I primarily play Java edition and might not get around to adding Bedrock support.
## Java
### Why Choose This One
Minecraft added experimental data pack features that I think will stay. These features make this kind of datapack less error prone, and I have not found anyone that is using them (update: I have now found someone using them, but it only works for one world gerneartion type which makes theirs worse than mine). How it works under the hood is it makes minecraft think the Nether is the Overworld and vice versa. In this way, the engine will automatically start the player in the Nether without me having to make a bunch of functions that trigger when certain events are met and are more likely to brake after updates to the game. I could not find any datapacks that do this for any of the more recent updates, which means that hoping this moves out of the experimantal phase is less of a gamble than hoping those keep working.
### Bugs
There are two known bugs. One: it does not work when zipped. Two: it can spawn the player outside the Nether boundaries.
