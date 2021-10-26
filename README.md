# Terraforming Pluto

Obviously inspired by Terraforming Mars

The December entry for my 2019 Boardgame Prototype Challenge (https://gist.github.com/andreasfrisch/74fc8bc0fe5b34672c1f5d8dae21f3e7)

## Why and what
The ideas behind Terraforming Mars are sound.
The game itself is, in my humble opinion not.
My main problems with Terraforming Mars is the time required to play and the presence of a board that does not do much for most of the game.

Terraforming Pluto aims to give the same idea of terraforming a planet, while cutting away most of the peripheral elements.

## What you need

* A printout of the cards in this repository.
* A printout of the game board in this repository.
* A printout of the tiles in this repository.
* A printout of the milestones in this repository.
* A printout of the action tiles in this repository.
* Around 15 cubes for each player in distinct colours. 
* An assortment of coins.

## Setup

* Place the game board in the middle of the table
* Shuffle the action tiles with their A-side up, and place them in a random order above the game board
* Place the action space cost-reminder tiles in order above the first 3 action tiles 
* Place the milestones next to the game board
* Place the coins next to the game board
* Shuffle the project cards and place them in a draw pile next to the game board
* Place all the terraforming tiles next to the board, sorted by type
* Each player chooses a colour, and takes all cubes of their colour
* Each player also receives 20 money and draws 3 project cards


## Taking a turn
During each turn, a player will take a single action from the available action tiles.
Then the player may optionally invalidate an action tile.
A player may forfeit both these actions in order to collect income.
Then play passes to the next player in clock-wise.

### Choosing an action
The player must choose one of the three available action tiles.
These tiles are indicated by the cost-reminder tiles above them.
The first available action tile is free to choose, but the next two costs the money indicated on the corresponding cost-reminder tile.

After paying for and performing the action, flip the action tile over, move it to the back of the queue, and advance all actions.

Whenever a player performs an action, projects that player controls (or sometimes projects controlled by other players) may trigger.

The available actions and their frequencies are:

#### Plant Forest (x2)
Pay the indicated amount of money and place a forest tile on the planet.
Then gain the indicated amount of terraforming points.

When placing a forest tile remember to place a cube of your color on it to indicate ownership.

#### Construct City (x1)
Pay the indicated amount of money and place a city tile on the planet.

When placing a city tile remember to place a cube of your color on it to indicate ownership.

#### Provide Water (x1)
Pay the indicated amount of money and place a water tile on the planet.
Then gain the indicated amount of terraforming points.

Water tiles are not owned by anyone and do not by themselves contribute to end game scoring.

#### Groom Projects (x2)
Discard any number of project cards from your hand.
Then draw that many project cards from the project deck.

Then draw 2 additional project cards.

#### Implement Project (x2)
Choose a project card from your hand and place it in your tableau, paying the indicated price.

#### Activate Tableau (x2)
Choose a project in your tableau with an activation diamond and activate it.

### Optionally flip an action tile
After performing their action, and after resolving all triggered effects, a player may flip an action tile.
This works exactly the same way as when choosing an action tile, but the player does not gain the effect.
Instead, simply flip the action tile and move it to the back of the action tile queue.
Choosing an action tile to flip follows the rules for selecting action tiles;
Only the first three action tiles can be chosen and choosing anything but the first costs money.

### Collecting income
Instead of choosing an action tile and optionally flipping a tile, a player may collect income.
When choosing this option, a player will take an amount of money from the supply equal to the largest previous income number on the terraforming track plus his current income bonus.
Players start with an income bonus of 10, but every lap of the terraforming track awards players with an additional income bonus of 10.

## End of the game
The game will end when the planet is completely terraformed (i.e. is covered in tiles)
The current player will finish their turn, and then all players calculate their scores.

## Scoring
Score is calculated as follows:

* Each player receives points equal to their Terraforming Rating
* Each player may receive additional points for their cards
* Each player get points for milestones they have completed
* Each forest on the planet is worth 1 point
* Each city on the planet is worth 1 point for each surrounding forest
