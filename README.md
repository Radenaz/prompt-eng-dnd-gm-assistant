# Preface
This is my first attempt at designing prompts, with xml files provided as examples input:output from a prompt. I've been playing DnD, both as player and DM, and notice that sometimes we just need a quick, over the counter contents. So I figured I should give this prompt engineering a go and see how it goes.

I made them with the help of chatgpt as well, and then personally modify where needed.

===
# DnD Game Master Assistant
A collection of structured XML-based generators for Dungeon Masters to create engaging content for their Dungeons & Dragons campaigns. It helps generate encounters, NPCs, factions, magic items, and more.

# 📜 Features
## Encounters Generator (`encounter_gen.xml`)
Generate diverse encounters ranging from social intrigue in noble courts to dangerous ambushes in the wild.

## Hostiles Generator (`hostiles_gen.xml`)
Create unique and terrifying foes with distinct combat tactics and loot.

## Factions Generator (`faction_gen.xml`)
Design secret guilds, noble houses, and warring factions that shape the world.

## Lore & Mythology (`lore_gen.xml`)
Develop ancient legends, forgotten cities, and world-changing historical events.

## Magic Items Generator (`magic_item_gen.xml`)
Generate legendary weapons, cursed artifacts, and enchanted relics.

## NPC Generator (`npc_gen.xml`)
Create compelling non-player characters with unique backgrounds and motivations.

## Traps Generator (trap_gen.xml)
Design deadly dungeon hazards with intricate mechanisms.

## Quest Generator (quest_gen.xml)
Generate engaging quests with multiple resolution paths.

# 📂 File Structure
Each XML file follows a structured format with <example> entries containing:

User Input: The request made by user.
Generated Output: The structured response including details relevant to that type of content.
