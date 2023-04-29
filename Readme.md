# Ludum Dare 53

Theme: **Delivery**

Hear ye! Hear ye! Behold de Livery of Player One!

## de-Livery

Concept:
* Sway an entire city to your family's influence
* Choose your livery (name, emblem, and colors)
* Start with your family's dwellings
* Spread influence to the surrounding buildings until you control the entire city

Mechanics:
* Each building has an influence meter
* Influence spreads around the building in which you place your herald
* Each building has an effect
	- Houses add to your total influence
	- Taverns increase the rate at which your influence spreads
	- Cathedrals give you another herald
	- Constabularies give you defense against other influence
	- Guilds allow you to build a single building (extending your influence to new quarters of the city)
	- Schools increase your heralds range?
* Capture the entire city to win

Coolness:
* Design your own livery
* Area mechanics
* Growing a machine of influence

Difficulties:
* Custom livery
* Scaling up ticks
* Difficulty scaling well
* Generating maps
* Convincing people that the game conforms to the theme :)

### Implementation

#### Gameplay
* Buildings
	- Can be owned
	- Can receive influence ticks
	- Building type effects
	- Can build
* Heralds
	- Spreads influence in range
	- Can move from building to building
* AI
	- Chooses to spread influence
	- Focuses toward buildings of interest
* Custom livery
	- Can input a name
	- Can choose a color
	- Can draw an emblem
	- Applies livery to owned buildings
* HUD
	- Shows total influence
	- Shows building under attack
	- Shows number of heralds
* Generative maps?
	- Generates islands of buildings
	- Connects buildings with roads
	- Ensures sufficient separation for A
* Victory
	- Can lose when home captured
	- Can win when city captured
* Tutorial
	- Explains influence
	- Explains heralds
	- Explains each building


#### Assets
* Buildings
	- House
		* Model
		* Textures
	- Tavern
		* Model
		* Textures
	- Cathedral
		* Model
		* Textures
	- Constabulary
		* Model
		* Textures
	- Guild
		* Model
		* Textures
	- Homebase
		* Model
		* Textures
* Decoration
	- Trees
	- Walls
	- Main road
	- Side road
* Point of influence
	- Person to represent the influence moving
	- Highlight to indicate influence presence
	- Overlay of influence region? (maybe just flags)
* Sound
	- Music
	- Effects
		* Capture building
		* Lose building
		* Send herald
		* Arrive herald
		* Build building
		* Influence attack against you?

### Schedule

* Friday Evening
	- Concept selection
	- Planning
* Saturday Morning
	- Influence mechanics
	- Herald mechanics
	- AI implementation
	- Build mechanics
* Saturday Afternoon
	- Overflow mechanic implementation
	- Draw livery
	- HUD basics
* Saturday Evening
	- Building models
	- Decorative models
* Sunday Morning
	- Basically nothing
* Sunday Afternoon
	- Victory and loss
	- Tutorial
* Sunday Evening
	- Sound
	- Polish
	- Menus