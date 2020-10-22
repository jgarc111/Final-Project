## Team Roles
Matt Kubisa: Software Lead
John Garcia: Frontend Specialist (GUI)
Nestor Fernandez: Backend Specialist (Game Mechanics)

## Main Idea For Project:
Our current objective for the final project is to create a playable version of the board game Monopoly.

## What does a monopoly game need?
The basic requirements for a Monopoly game are listed in order of how essential they are to a working game:
* Establishing, displaying and updating the game board as a visual element.
* Being able to roll dice and land on spaces.
* Keeping track of all player’s money.
	* includes dealing out the money at the start of the game
	* taking away money with property purchases, landing on other’s property (”paying rent”), or chance/community chest cards
* kicking out a player when they declare bankruptcy
* option to purchase properties the player lands on
* Keeping track of which players own what properties
* keeping track of which players are in jail, and including the multiple ways the player can enter jail...
	* Rolling doubles three times
	* landing on “go to jail” space
	* drawing “go to jail” chance/community chest card
* and exit jail...
	* rolling doubles in jail
	* using “get out of jail free” card (game must know if player has this in his possession)
	* paying $50 after three turns in jail
* A part of the code that keeps track of all the potential chance/community chest cards, as well as a way to draw from these cards when appropriate.
* detecting when a player has a monopoly (owns all properties of a certain color), and allowing them to build houses/hotels on their turn
	* must also increase rent prices based on how many houses are built
* taking out mortgages on properties (getting money for owned properties at the cost of not getting anything when other players land on that space)
	* also ending/paying off mortgages 
* Computer controlled opponents, who have the ability to roll the dice, move their pieces, and keep track of their own money.

## Things that need to be displayed on the screen
* The game board.
* each player’s name.
* each player’s location on the board.
* each player’s money and properties they own.
* ability to let player choose their piece at the start of game, and display it on screen (if this feature is added)


## miscellaneous ideas
* maybe each player can have their own inventory, which keeps track of
	* amount of money they have
	* what properties they own
	* if they have get out of jail free card
* computer controlled opponents should be one of the final additions to the game to focus on, due to it not being necessary to have a working game. Two human players can instead take turns until AI is developed, if ever. It is not necessary for having a working game.
* A network based API is required for the project.
	* One idea I (software lead) had for this is that we can make some aspect of the game change based on the current weather, such as a community chest/chance card or whether or not the railroads run in certain conditions. A weather API would be used for getting current weather data.
	* this idea doesn’t have to be used; feel free to come up with other ideas 

> Written with [StackEdit](https://stackedit.io/).
