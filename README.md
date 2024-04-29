# Oath (Group 2)

## Game Introduction
“Oath” is a 2D roguelike game that combines the survival gameplay of "Vampire Survivors" with the lore and character-driven storytelling of "League of Legends." In this game, the player will be guided to unlock abilities, acquire strong passive items, level up the abilities and the passive items, and pass through waves of enemies as well as several boss fights. "Oath" was developed using the Unity engine and has taken advantage of its powerful features, including its cross-platform capability.

## Game Features

### Infinte Map
Unlike most of the traditional RPG games, the map in Oath is infinite. The map can be viewed as a straight line extending indefinitely to the left and right. So no matter which direction (left or right) the player chooses to go, the map always extends to infinity. This infinite map ensures that the player has a high degree of freedom and also provides plenty of room to fight.
<img width="690" alt="1" src="https://github.com/xsy27/Oath/assets/99967861/4807dcd6-00db-4e58-bdff-70b8301dfd36">

### Randomness
Randomness is a key feature of Oath. In each map slice, the constructions are different. And there is a probability of generating a treasure box in each map slice. When the player opens the treasure box, there will also be a probability of getting a positive effect (e.g., recovering health) or a negative effect (e.g., taking damage). Therefore, as the player progresses, the map it encounter is always different, which greatly avoids aethetic fatigue and getting lost. When the player gains enough experience from defeating enemies, it will be given a chance to get a new passive item or upgrade one of its abilities or passive items. The player can choose from three choices, and the three choices are given at random.
<img width="1280" alt="2" src="https://github.com/xsy27/Oath/assets/99967861/7c8ed21a-b642-47e4-8c68-3385e39eed2a">

### Various Combinations
Based on the randomness of the game, various combinations of passive items along with the abilities provide the player with a wealth of play strategies, further increasing the uncertainty as well as the entertainment of the game.
<img width="1280" alt="3" src="https://github.com/xsy27/Oath/assets/99967861/edf9c388-4ca2-4fb3-96d1-61027f6b2ef7">

## Game Instruction

### Build the Game
With the source code of Oath, the player can directly run the game starting from the "Main Menu" scene.
<img width="1280" alt="4" src="https://github.com/xsy27/Oath/assets/99967861/e88e9ab8-bf9e-49fe-a866-93a7756af3cd"> <br>
Or click "Build And Run" (Ctrl+B) under "File".
<img width="1280" alt="5" src="https://github.com/xsy27/Oath/assets/99967861/d977ba69-a74f-4546-8716-3e07a0d141cf"> <br>
Or export the game by clicking "File"->"Build Settings"->"Build"->"Clean Build", and then run the Oath.exe file.
<img width="1280" alt="6" src="https://github.com/xsy27/Oath/assets/99967861/ff9a93f0-d64d-4f9c-98f1-8b71bdac94de">
<img width="536" alt="6(2)" src="https://github.com/xsy27/Oath/assets/99967861/d75770ca-ed08-4d25-87bf-b6bcc1e790b2">

### Start the Game
On Opening the game, the player should be able to see the main menu.
<img width="1280" alt="7" src="https://github.com/xsy27/Oath/assets/99967861/cd49df9c-1205-4fb1-bbf3-a28c6fad8ceb"> <br>
Click "START" to start the game. <br>
Click "INSTRUCTION" to view the playing instructions.
<img width="1280" alt="8" src="https://github.com/xsy27/Oath/assets/99967861/121e6aa7-eca8-4122-bfc0-9b3d68d6a4b8"> <br>
Click "SETTINGS" to adjust gameplay (resolution, screen mode, and volume).
<img width="1280" alt="9" src="https://github.com/xsy27/Oath/assets/99967861/846d5181-84c0-4006-98f7-1ca00dea3bd1"> <br>
Click "QUIT" to exit the game.

### Play the Game
On starting the game, the player should be able to see the character in the center of the screen. <br>
Use WASD to walk around. The abilities are triggered automatically. <br>
The timer right in the middle of the top shows the time elapsed. The panel below shows the current level, the HP, the experience gained, and a button used to open the backpack. <br>
Enemies are spawned in waves, and each wave lasts for 1 minute. There will be a boss in the third and fifth waves, respectively. <br>
The game will end when the player successfully survives for five minutes or the character's HP goes to zero.
<img width="1280" alt="10" src="https://github.com/xsy27/Oath/assets/99967861/0059fd19-8896-414b-ba77-e36e3d86c8cc">

#### Backpack
Press "E" or click the button in the lower right corner to open the backpack and view the character's current statistics, the abilities' levels, the passive items acquired, and the levels of the passive items. <br>
Press "E" again or click the cross button to close the backpack.
<img width="1280" alt="11" src="https://github.com/xsy27/Oath/assets/99967861/d7fa5ff1-4a58-48bb-9cf3-aa2a8fff4152">

#### Pause
Press "Space" to pause the game. <br>
Press "Space" again or click the "Resume" button to resume the game.
<img width="1280" alt="12" src="https://github.com/xsy27/Oath/assets/99967861/6ef78fde-01be-465e-aa19-c1a4546871b8"> <br>
The player can view the instructions again on the paused screen.
<img width="1280" alt="13" src="https://github.com/xsy27/Oath/assets/99967861/c074e16a-e3c7-4746-a412-258c442fcf5d"> <br>
Click "Resume" if the player wants to resume the game. <br>
Click "Quit" if the player wants to go back to the main menu.

#### Level Up
When the character gains enough experience, a level up screen will be poped out and the player can choose one of the three given abilities/passive items to upgrade.
<img width="1280" alt="14" src="https://github.com/xsy27/Oath/assets/99967861/79cc87fa-00b3-4488-b4a8-6e1f53f80646">

#### Game Over
A Game Over screen will be shown when the game ends.
<img width="1280" alt="15" src="https://github.com/xsy27/Oath/assets/99967861/925e2081-c459-4f83-b3c4-e94c65b44dc7"> <br>
Click "Results" to view the statistics of this round of game.
<img width="1280" alt="16" src="https://github.com/xsy27/Oath/assets/99967861/42097261-b277-4abd-808a-d4cdda79b990"> <br>
Click "Quit" to go back to the main menu.

## Game Future
Although the game now has a lot of basic features, it is still in development, and there is much that can be improved. In the future, we plan to improve Oath in many aspects:
* Add more characters with different stories and abilities.
* Add maps with different features.
* Add more passive items that have good linkage effects with the abilities.
* Add more kinds of enemies and bosses.
* Add a handbook to the main menu where the player can check the detailed descriptions of the characters, the characters' abilities, the passive items, the enemies, and the maps.
* Add a shop at the main menu where the player can buy permanent positive effects (e.g., increased initial max health) using coins collected from defeated enemies in the game.
* Add a system that upgrades abilities to ultimate abilities under specific circumstances (e.g., acquire some specific passive item).
* Add conversations between the character and the bosses to make the storyline clear.
* Add multiplayer mode.
* Add different difficulty modes.
* Add partners that will be involved in the fights and stories along with the characters.
