# prompts

## Prompt 0

> Este prompt no lo llegué a lanzar al agente. Lo estaba creando y cuando no sabía cómo detallarlo más, decidí usar meta prompting. Sin embargo, como estaba en el archivo prompts.md, el agente lo usó como contexto por lo que tomó requisitos de él.

You are an expert web online games developer.

Develop a Javascript game that works in the browser. All game needs to be developed in a single HTML file that includes all styling. Add all necessary images and sprites in a "assets" folder.

1. **Game Overview**
- The game consists of a spaceship (player) who needs to destroy alien spaceships (enemies) and avoid their attacks, moving inside a limited square-shaped scenario with size 500x900px, placed in the middle of the website.
- The player can move left and right using arrow keys, and shoot missiles upwards with space key.
- Enemies appear in the screen randomly and shoot to the player downwards.
- If a missile from the player hits an enemy, the enemy is destroyed and he gets points.
- The game has a maxium duration of 2 minutes. Then, the game ends and player wins.
- If a missile hits the player, the game ends and the player looses.
- If an enimy collides with the player, the game ends and the player looses.
- When the game ends and the player has won, display a "Congratulations" screen and the final score.
- WHen the game ends and the player has lost, display a "Game Over" screen.
- When the game ends, the user should be able to restart the game via a "Try again" button and functionality that restores everything to the inital state.

2. **Technical requiremens**
- Develop everything in HTML, CSS and JavaScript. Use external open-source libraries if they provide simplicity to the code.
- Make the code clean and well-structure with comments for easy reviewing.
- Make sure everything works in all major browsers.

3. **Game flow**
- When the game starts, the player position is x:250 y:820 and there are no enemies in the scenario.
- The user makes the player move horizontally with arrow keys, but the player cannot go outside the limits of the scenario.
- Enemies appear in the scenario from outside the scenario, but they are only visible when they enter the scenario limits.
-

## Prompt 1

Give me the prompts to create a web game like the classic Galaga game, that works with plain JavaScript in any browser.

Ask me all questions you need to provide a concise and well planned prompt.

--
Questions

1. Pixel retro graphics with open-source assets
2. no sound
3. should increase over time
4. keyboard controls are sufficient.
5. current session score
6. Create custom branding with the title "GalagIA"
7. no accesibility requirements needed.


## Prompt 2

Develop a browser-based game called "GalagIA" inspired by the classic Galaga, using only HTML, CSS, and plain JavaScript (no frameworks). The game must run in all major browsers and be contained in a single HTML file with all styles included inside the folder galaga-DFG. Use pixel-art retro graphics with open-source assets, placing all images and sprites in an "assets" folder.

Game Requirements:

The play area is 500x900px, centered on the page.
The player controls a spaceship at the bottom (start position x:250, y:820), moving left/right with arrow keys and shooting upwards with the spacebar.
Enemies (alien ships) spawn randomly from above, enter the play area, and shoot downwards.
Difficulty (enemy speed, spawn rate, and shooting frequency) increases over time.
If the player’s missile hits an enemy, the enemy is destroyed and the player gains points.
If an enemy missile or enemy ship hits the player, the game ends with a "Game Over" screen.
The game lasts a maximum of 2 minutes. If the player survives, show a "Congratulations" screen with the final score.
Show the current session score only (no persistent high scores).
After the game ends, provide a "Try again" button to restart and reset all game state.
Use custom branding with the title "GalagIA" on the main screen.
No sound or accessibility features are required.
Technical:

Code must be clean, well-structured, and commented for easy review.
Use open-source pixel-art assets for all graphics.
All assets must be placed in an "assets" folder.

Confirm with me every step of the process and ask me any questions before making any decision


----

Questions

1. classic galaga colors
2. I have no assets in mind
3. animated

-----

Questions
1, 2, 3, 6 and 7 are not working. for 6, use plain Javascript and CSS

---

Questions
1. ok
2. ok
3. ok
7. use CSS style


## Prompt 3

Update the size of the play area to 500x800px and adjust the position of the player after the change of size of the play area
