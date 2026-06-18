# Part B - Class Design
## Car Class
### Role
Stores the data used for comparison in the game
### Attributes
- Power: integer
- Fuel Efficiency: Integer
- Year Manufactured: Integer
- Price: Integer
- Kilometres Travelled: Integer
- Fuel Capacity: Integer
### Methods
- GetAttributes(Attribute)
- DisplayInfo()
- CompareAttribute(Other Car, Attribute)
## Card Class
### Role
Represents a playable card that contains a car
### Attributes
- ID: Integer
- Car: Car
### Methods
- ShowCard()

## Deck Class
### Role
Stores all cards and manages distribution
### Attributes
- Cards: Integer
### Methods
- Shuffle()
- AddCard()

## Player Class
### Role
Represents each player and stores their hand
### Attributes
- Player Name: String
- Hand: List < Card >
- Score: Integer
### Methods
- PlayCards()
- ReceiveCard(Card)
- ChooseAttribute()
- GetScore()

## Game Class
### Role
Controls overall gameplay
### Attributes
- Deck
- player1: Flow
- Player2: Flow
- Round Number: Integer
### Methods
- StartGame()
- Win()
- Lose()





