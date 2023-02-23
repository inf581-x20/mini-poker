# mini-poker

## Cards 
"Cards" is a class that defines the environment's deck of cards and implements the "hands" function, which is responsible for dealing cards to both players during the game. This class plays a critical role in simulating our game.

## Random-Mean Attacker
A "Random-Mean Attacker" is a type of opponent player in poker who determines their bets based on a certain condition. Specifically, if the value of their hand is less than the mean of all possible hand values, they will place bets randomly between 1 and 5. However, if the value of their hand is greater than or equal to the mean of all possible hand values, they will place bets randomly between 6 and 10.

## Deterministic Attacker
A "Deterministic Attacker" is a type of player in poker who determines their bets based on the value of their hand. In other words, their betting behavior is deterministic and can be predicted based on the strength of their hand.

## Human 
Human is a class where we define the human interaction with the computer, the agent.

## ThompsonSamplin, UCB1 and Exp3 agents
ThompsonSamplin, UCB1 and Exp3 represent the Multi-Arm bandit algorithms covered in the course. 

## tdLearning agent
tdLearning represent the Q-learning algorithm covered in the course. 

## play function
The "play" function is the primary function used to run a mini-poker game between an attacker and an agent. The function takes four parameters: "agent," "attacker," "display," and "human." The "display" parameter determines whether or not the final worth of the agent and attacker is printed. The "human" parameter is used to display the progress of the game when playing against a human player.
