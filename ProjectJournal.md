# Assessment Task 2
## Part A - **Data Selection and Game Attributes**
### <u>Attributes</u>


| Rank | Attribute | Higher or Lower Wins? | Why it was Chosen | Fair / Unfair Considerations |
|------|----------|----------------------|------------------|------------------------------|
| **1** | **Power (kW)** | Higher | Power was chosen because it strongly represents vehicle performance and creates exciting competition between cards. | Fair because different vehicles show noticeable variation in power. Unfair if high-power cars dominate too often. |
| **2** | **Fuel Efficiency (L/100km)** | Lower | Fuel efficiency introduces strategy by allowing practical vehicles to compete with performance-focused vehicles. | Fair because lower fuel consumption rewards efficiency. Unfair if efficiency becomes more valuable than every other attribute. |
| **3** | **Year Manufactured** | Higher | Year was selected because newer vehicles generally include improved technology, features and design. | Fair because newer vehicles often offer advantages. Unfair because older premium vehicles may become undervalued. |
| **4** | **Price (AUD)** | Higher | Price reflects market value and perceived quality while adding another comparison category. | Fair when balanced with other attributes. Unfair if expensive vehicles automatically become the strongest cards. |
| **5** | **Kilometres Travelled (km)** | Lower | Kilometres represent vehicle condition and reliability, adding depth beyond performance. | Fair because lower kilometres often indicate better condition. Unfair because older but reliable vehicles may be disadvantaged. |
| **6** | **Fuel Capacity (L)** | Higher | Boot capacity was included to allow practical and family vehicles to remain competitive. | Fair because it increases diversity in gameplay. Unfair if players ignore practical categories and focus only on performance. |
## Part B - Class Design
### Car Class
#### Role
Stores the data used for comparison in the game
#### Attributes
- Power: integer
- Fuel Efficiency: Float
- Year Manufactured: Integer
- Price: Float
- Kilometres Travelled: Integer
- Fuel Capacity: Integer
#### Methods
- GetAttributes(Attribute)
- DisplayInfo()
- CompareAttribute(Other Car, Attribute)
---
### Card Class
#### Role
Represents a playable card that contains a car
#### Attributes
- ID: Integer
- Car: Car
### Methods
- ShowCard()
---
### Deck Class
#### Role
Stores all cards and manages distribution
#### Attributes
- Cards: List<
Card >
#### Methods
- Shuffle()
- DrawCard()
- AddCard()
---
### Player Class
#### Role
Represents each player and stores their hand
#### Attributes
- Player Name: String
- Hand: List < Card >
- Score: Integer
#### Methods
- PlayCards()
- ReceiveCard(Card)
- ChooseAttribute()
- GetScore()

---
### Game Class
#### Role
Controls overall gameplay





