# Minecraft-skygen-all-commands-needed
Yo, so If you're wanting to make a skygen [Bedrock Edition}  These are all the main commands and what they do. 


Key commands for SkyGen
/setblock <x> <y> <z> <block_type>: This is the core command for generating blocks.
In SkyGen, you'll use relative coordinates like ~ ~2 ~ <block_type in command blocks to place new blocks directly beneath the player.
For example: /setblock ~ ~2 ~ diamond_ore.
/scoreboard objectives add <name> <type> [<display_name>]: Creates a new objective to track data.
For a currency system, you would use: /scoreboard objectives add coins dummy coins.
/scoreboard players add <target> <objective> <score>: Adds a score to a player.
Used to award currency: /scoreboard players add @a coins 1 (adds 1 coin to all players).
/scoreboard players remove <target> <objective> <score>: Removes a score from a player.
Used to charge for items: /scoreboard players remove @a coins 5 (removes 5 coins from all players).
/give <target> <item> [amount]: Gives an item to a player.
This can be used to give rewards or for shopkeepers to give items: /give @a[scores={coins=10..}] diamond_pickaxe 1 (gives a diamond pickaxe to any player with 10 or more coins). 

/tp <target> <x> <y> <z>: Teleports a player. Useful for moving players between islands.
/effect <target> <effect> [seconds] [amplifier] [hideParticles]: Applies an effect.
Example: /effect @s health_boost 10 1 true gives the player a health boost.
/tag add <tag_name: Adds a tag to an entity, which can be used for more complex scoring or effects.
Example: /tag @s add sharp_1000.
/execute `: Executes a command from the perspective of a specific target or block.
/gamerule <value: Changes a game rule.
Example: /gamerule sendcommandfeedback false to hide command output from chat. 
