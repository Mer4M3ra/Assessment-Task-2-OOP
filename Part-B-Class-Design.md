# Part B - Class Design
## Car Class
### Role
Stores the data used for comparison in the game
### Attributes
- Power: integer
- Fuel Efficiency: Float
- Year Manufactured: Integer
- Price: Float
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
- Cards: List<
Card >
### Methods
- Shuffle()
- DrawCard()
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
- 




