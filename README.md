# GuessThat
Guess that will be a game where a user is given a clue one at a time and the user will try and guess what the category thing is. For each clue given when the user guesses the item the amount of points they receive is less each time. Each of the clues will give more detailed then the one before. The goal of the game is to guess all the categories and have the most amount of points. 

## Installation Instructions

### Prerequisites
- Language - Node.js v18+, Python 3.10+

### Steps
1. Clone the repository
```bash
   git clone https://github.com/yourusername/guess-that.git
   cd guess-that
```
2. Install dependencies
```bash
   npm install
```
3. Run the game
```bash
   npm start
```
5. Open your browser to `http://localhost:3000` (or wherever it runs)

## Usage Examples

### A single round
The game reveals one clue at a time. Guess correctly early for more points — 
each subsequent clue reduces the value of a correct guess.

Clue 1 (100 pts): "This is found in the kitchen."
> Your guess: ___

Clue 2 (75 pts): "It's used to measure temperature."
> Your guess: ___

Clue 3 (50 pts): "It's a common tool in baking."
> Your guess: thermometer

Correct! You earned 50 points.
 
## Community Channels 
- **Bug reports & feature requests:** [Open an issue]
- **Questions & discussion:** [GitHub Discussions]


