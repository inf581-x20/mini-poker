# mini-poker

## Cards 
It is where we define our environment cards and the function hands that deal the cards to both players.

## Random-Mean Attacker
Random-Mean Attacker is a player, an opponent, who takes bets in {1,...,5} when his hand is less than the mean and in {6,...,10} otherwise.

## Deterministic Attacker
Deterministic Attacker is a player who takes bets as a translation of the value of his hand.

## Human 
Human is a class where we define the human interaction with the computer, the agent.

## ThompsonSamplin, UCB1 and Exp3 agents
ThompsonSamplin, UCB1 and Exp3 represent the Multi-Arm bandit algorithms covered in the course. 

## tdLearning agent
tdLearning represent the Q-learning algorithm covered in the course. 

## play function
play is the main function to run a mini-poker game between an attacker and an agent. It takes agent, attacker, display and human respectively as parameters. The display parameter is to print or not the final worth of the agent and the attacker, in the other hand the human parameter is to print the state of advancement of the game while playing against a human player.
