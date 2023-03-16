#HGBabySpells is a World of Warcraft Classic and Wrath of The Lich King Classic addon that provides a simple yet useful feature to help players identify lower-ranked spells on their hotbars quickly. This addon adds a button to the character's spellbook, and when clicked, it scans the hotbars for spells with lower ranks and highlights them.

#How to Install
Download the addon from the official CurseForge page.
Extract the addon files from the archive.
Copy the extracted files into your WoW addon folder (usually located in World of Warcraft\_classic_\Interface\AddOns for WoW Classic and World of Warcraft\_retail_\Interface\AddOns for WoW Wrath of The Lich King Classic).
Launch the game and ensure that the addon is enabled in the addon selection menu.

#How to Use
Once installed, HGBabySpells adds a new button to the character's spellbook. Clicking this button initiates a scan of your hotbars for spells with lower ranks, which are then highlighted with an overlay glow. The console output will also display the number of spells with lower ranks.

#Technical Details
HGBabySpells is written in Lua, a lightweight programming language used extensively in World of Warcraft addons. It uses Blizzard's API to query the spellbook and hotbars and leverages the Spell:CreateFromSpellID function to asynchronously load spell data.

The addon works by iterating over the hotbars, collecting spell IDs, and querying their ranks from the spellbook. If a spell is found to be of lower rank than the maximum available, it is highlighted on the hotbar with an overlay glow. The addon can scan both the default UI and Bartender4 hotbars.

#Conclusion
HGBabySpells is a simple and effective addon that provides a useful feature for World of Warcraft Classic and Wrath of The Lich King Classic players. By highlighting spells with lower ranks on hotbars, players can ensure that they are using the most potent spells available, thereby improving their gameplay experience.
