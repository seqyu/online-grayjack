# Online Grayjack
An online game of Grayjack (a variant of Blackjack / Twenty-One) made with Flask.

## Setting up an Online Grayjack server
> [!NOTE]
> Online Grayjack is not ready yet.

## A lil' refresh about Blackjack's rule
Blackjack is a pretty fun game often played in casinos where the goal is to be the player with the highest possible score. Max is 21, if you go over 21, you lose your bet.

You start by placing your bets, then the dealer gives you 2 cards.

You can chose to either get more cards, don't get more, or just fold if you feel like you are going to lose.

## Grayjack Rules
### Betting Round
The dealer deals each player two cards, each player is able to look at their own hands but not at other's.

After the dealer dealt all the cards, all players must bet at least one cheap of the lowest value. A player can also go all-in and bet all of their chips on the hand they have.

### Action Round
After locking in all of their bets, players enter the action round.

During this phase, players can request more cards at the risk of getting more points than the point limit, which is set at 21, and instantly losing their bet.

If a player feels like they are going to lose they can fold and keep their bet.

### Card values

Joker: Decided by the player holding the joker, can be a value from 1 to 10.

Queen/King/Jack: 10

9: 9

8: 8

7: 7

6: 6

5: 5

4: 4

3: 3

2: 2

Ace: 1

### Folding
Each player can only fold once per game, compared to Blackjack where players can fold once per hand.

### Losing
When a player has no chips left, they lose and are out of the game. There is no way to get back into the game.

## How Grayjack was born
It all started 175 years ago, in Le Grand Cercle casino in France. No actually it was just a regular tuesday afternoon on the 24th of june 2025.

I was playing Blackjack with a friend and he came up with an idea, being able to see your cards during the betting phase. I found this idea amazing and we played with it.

A few hands later I was in bad posture and decided to fold, and I came up with another rule to try and make the game a bit more balanced, you can only fold once per game, not per hand, to prevent abusing the folding mechanic.

At this very moment, the idea of Grayjack was born.

After our game we decided to think about new rules for our new variant of Blackjack, like jokers.
