Blackjack Game
Author: Mohammed Al-Mokhtar
Email: mohammed.a.mohtar01@gmail.com

Description
This is a Python implementation of the classic card game Blackjack. In this game, you play against the dealer, trying to get as close as possible to 21 points without going over. The game includes standard Blackjack rules, such as doubling down, hitting, and standing.

Rules
Card Values:
Kings, Queens, and Jacks are worth 10 points.
Aces are worth either 1 or 11 points.
Cards 2 through 10 are worth their face value.
Gameplay:
(H)it to take another card.
(S)tand to stop taking cards.
On your first play, you can (D)ouble down to increase your bet but must hit exactly one more time before standing.
In case of a tie, the bet is returned to the player.
The dealer stops hitting at 17.
How to Run the Game
Clone the Repository:
git clone https://github.com/iamohammed1/BlackJack

Navigate to the Project Directory:
cd blackjack-game

Run the Game:
python blackjack.py

How to Play
You start with $5000 and can bet a portion of your money on each round.
The game will deal two cards each to you and the dealer.
You can choose to hit, stand, or double down according to the game rules.
The goal is to have a hand value closer to 21 than the dealer without exceeding 21.
Example Code
Here's a small snippet showing how the game initializes a deck of cards:

python

def getDeck():
    deck = []
    for suit in (HEARTS, DIAMONDS, SPADES, CLUBS):
        for rank in range(2, 11):
            deck.append((str(rank), suit)) # Add numbered cards
        for rank in ('J', 'Q', 'K', 'A'):
            deck.append((rank, suit)) # Add face and ace cards
    random.shuffle(deck)
    return deck
Requirements
Python 3.x
No external libraries are required.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions or suggestions, feel free to contact me at mohammed.a.mohtar01@gmail.com.
