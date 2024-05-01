# Ai_Final_Project

Tic Tac Toe Multi-Agent Implementation

# OVERVIEW:

In the popular classic game Tic Tac Toe, two players alternately place their symbols (X and O) on a three-by-three grid with the goal of creating a line of three of their symbols that runs either horizontally, vertically, or diagonally. In this study, we investigate several AI agents for playing Tic Tac Toe, such as adversarial search using Min-Max Algorithm and Alpha-Beta Pruning, and reinforcement learning using Q-Learning.

# OBJECTIVES:

Create artificial intelligence (AI) agents that can play Tic Tac Toe with various strategies.
Apply the Min-Max Algorithm with Alpha-Beta Pruning for adversarial search and Q-Learning for reinforcement learning.
Consider variables like win percentage, average number of moves in a game, training duration, and adaptability to various opponents when assessing each algorithm's effectiveness.
The goal should be for AI agents to behave like humans and  strategic thinking.


# METHODS:

Q-Learning

A well-liked reinforcement learning method based on the Bellman Equation is called Q-Learning. By selecting the optimal course of action based on prior experiences, the agent gains the ability to maximize rewards. Through trial and error, the objective is to raise the "Q" value, which stands for the predicted cumulative payoff. Based on the rewards it receives from each action, the Q-Learning agent updates its Q-table while exploring the game arena. To ensure ongoing learning and progress, it might employ exploration strategies like ε-greedy or softmax to strike a balance between known and unknown actions.


Adversarial Search

Adversarial search algorithms mimic potential results of actions in a competitive context. One example is Min-Max with Alpha-Beta Pruning. These algorithms build decision trees to assess the optimal move in light of possible opponent reactions. While Alpha-Beta Pruning optimizes the search by removing branches that are unlikely to effect the final decision, hence reducing the computing complexity, Min-Max Algorithm assesses potential moves recursively. By weighing the options available to the opponent and choosing the one that will increase its chances of winning or decrease its chances of losing, the adversarial search agent seeks to discover the best move.



# OVERVIEW OF AGENTS:


Q-Learning Agent:

makes decisions using reinforcement learning.
makes use of past experiences to optimize gains.
strives to raise the "Q" value with every activity.
balances known and unknown actions using an exploration-exploitation technique.
may use methods to efficiently manage vast state spaces, such as neural networks or function approximation.


Utilizing Alpha-Beta Pruning Agent in Min-Max Algorithm:

uses adversarial search to find the best course of action.
builds decision trees to assess potential results.
effectively reduces the search space by using Alpha-Beta Pruning.
chooses the optimal course of action after taking the opponent's possible actions into account.
In larger game trees, depth-limited search may be used for efficiency.
It is possible to estimate the desirability of board states using evaluation functions.


# DELIVERABLES:

Comprehensive documentation that explains the algorithms, implementation specifics, and usage guidelines for the Q-Learning and Adversarial Search Agents.
Each AI agent's implementation is included in Python files with comprehensible comments and documentation.
Access to the GitHub repository for the project in order to collaborate and evaluate code.
a YouTube video and presentation slides that show how the project was carried out, complete with gameplay samples and performance analysis.



# METHODS OF EVALUATION:


Win Rate               : The proportion of games that you win versus various opponents, such as AI agents that are random, heuristic-based, or otherwise. To take variability into consideration, several trials had 
                          to be carried out.
                          
Average Moves per Game : Indicates how well the agent makes decisions by taking into account both winning and losing outcomes. A lower average move set suggests a more tactical and effective gameplay style.

Training Time          : The amount of time needed, including the number of episodes or iterations required for convergence, for AI agents to learn and get better. Computational efficiency can be evaluated by 
                          comparing training times.
                          
Performance Against Different Foes : evaluating a player's ability to adjust to various playing styles and tactics, as well as their strengths and weaknesses in relation to each opponent. It is important to 
                                     assess performance against a variety of opponents in order to guarantee generalizability.
                                     
Human-Like Behavior    : Assessment of adaptable gaming and strategic thinking, pattern recognition, and decision-making akin to that of human players. Agents should play with flexibility and originality.




This exhaustive assessment guarantees a complete comprehension of every AI agent's potential and efficacy in the game of Tic Tac Toe, offering valuable perspectives on their performance and possible avenues for enhancement. To further hone the agents and investigate cutting-edge tactics, more research and analysis might be done.
