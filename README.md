# Blackjack Game 🃏

A simple Python implementation of the classic Blackjack card game using Jupyter Notebook.

## How to Play
1. Create and shuffle a deck of 52 cards.  
2. Player places a bet (must not exceed available chips).  
3. Deal two cards each to player and dealer.  
4. Show both player cards and one dealer card (other remains hidden).  
5. Player chooses to Hit (take another card) or Stand.  
6. If player’s hand exceeds 21 → Bust.  
7. If player Stands, dealer plays (must hit until value ≥ 17).  
8. Determine winner and update chips.  
9. Option to play again.

## Card Values
- Number cards = face value  
- Face cards (J, Q, K) = 10  
- Ace = 1 or 11 (whichever is favorable)

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/phantomxcode/BlackjackGame.git
   ```
2. Open Jupyter Notebook and run:
   ```bash
   jupyter notebook "Blackjack Game.ipynb"
   ```
