# minecraft-charms
This repository contains Java code for a Paper 1.20.6 (Build #112) Minecraft server plugin to add custom charms.

## What the project does

Charms are items that, when placed in the nine slots in a player's hotbar, confer potion effects continuously to that player. This plugin implements charms for Minecraft servers and allows for the addition of custom charms.

All charms must have a custom name and lore. Use the ``/give`` command in minecraft to give yourself a charm after specifying its details in the ``config.yml`` file.

As an example, if you want to give yourself an iron ingot named "Test" with the lore text "Test", you could run this command in-game: ``/give @s minecraft:iron_ingot[minecraft:custom_name="Test",minecraft:lore=[Test]] 1``

List of Potion Effects: hub.spigotmc.org/javadocs/bukkit/org/bukkit/potion/PotionEffectType.html

List of Materials: hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html

## Why the project is useful

Currently, no plugins implement charms or charm-like items in an easy way. Server staff can achieve the same effect with other plugins, but only after cumbersome changes.

## How users can get started with the project

If you'd like to contribute, please create a pull request on the GitHub page for this project! You can also email Kiron at kiron_ang1@baylor.edu.

## Where users can get help with the project

If you need help, please create an issue on the GitHub page for this project! You can also email Kiron at kiron_ang1@baylor.edu.

## Who maintains and contributes to the project

- Kiron Ang: https://github.com/Kiron-Ang, kiron_ang1@baylor.edu
