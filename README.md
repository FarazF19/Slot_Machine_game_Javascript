# Slot Machine Game

This is a simple slot machine game implemented in Node.js. Players can deposit money, choose the number of lines they want to bet on, place a bet, spin the slot machine, check if they've won, receive their winnings, and continue playing until they run out of money or choose to stop.

## Features

- Deposit money: Players can start the game by depositing an initial amount of money.
- Choose number of lines: Players can choose how many lines they want to bet on (up to 3).
- Place a bet: Players can place a bet on each line they've chosen.
- Spin the slot machine: The slot machine generates random symbols for each line.
- Check winnings: The game checks if the player has won based on the symbols generated.
- Receive winnings: Players receive winnings based on their bets and the symbols generated.
- Balance checking: Players can check their balance and decide whether to continue playing.
- Play again: Players can choose to play again after each round.

## Usage

1. **Deposit money**: Enter the amount of money you want to start the game with.
2. **Choose number of lines**: Enter the number of lines you want to bet on (1 to 3).
3. **Place a bet**: Enter the bet amount for each line.
4. **Spin the slot machine**: Symbols will be randomly generated for each line.
5. **Check winnings**: Any winnings will be displayed.
6. **Balance checking**: Your current balance will be shown, and you can choose to play again or quit.

## How to Run

1. Clone this repository to your local machine.
2. Make sure you have Node.js installed.
3. Open a terminal and navigate to the project directory.
4. Run `npm install` to install dependencies.
5. Run `node slot-machine.js` to start the game.

## Example

$ node slot-machine.js
Enter a deposit amount in $: 100
You have a balance of $100
Enter number of lines: 3
Enter Bet: 5
A | C | D
B | D | B
A | A | A
You won, $15
Do you want to play again (y/n)? y
You have a balance of $110
Enter number of lines: 2
Enter Bet: 10
C | B | A
A | D | D
You lost!
You have a balance of $100
Enter number of lines: 1
Enter Bet: 20
C | C | D
You lost!
You have a balance of $80
Enter number of lines: 3
Enter Bet: 25
A | A | B
C | D | C
B | B | A
You won, $35
Do you want to play again (y/n)? n