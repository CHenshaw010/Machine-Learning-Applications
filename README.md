## This repository contains Python files to create machine learning applications for various applications.

### Documentation:
- [Pathfinding Agent Design Defense](https://github.com/CHenshaw010/Machine-Learning-Applications/blob/main/Machine%20Learning%20Pathfinder%20Problem%20Design%20Defense.pdf)

### Pathfinding Agent Project:
- [Pathfinding Agent](https://github.com/CHenshaw010/Machine-Learning-Applications/blob/main/Machine%20Learning%20Pathfinder%20Problem.ipynb)

### Project Description:
Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
- The main goal of this project was to appropriately implement a Q-Training Algorithm to solve a pathfinding problem. Among the provided code were methods for the environment, experience replay, build model, and executing the game. The environment was created as a matrix that outlined available and blocked squares. The experience replay stored episodes containing game states that would later be used to train the accuracy of agent predictions for future actions. The build model was comprised of three layers, one input and two hidden, matching the maze size with a SReLU activation function, adam optimizer, and Mean Squared Error Loss function.
- Then it was necessary to implement a Q-Training Algorithm to identify the best possible navigation sequence to maximize rewards. The pathfinder agent had to accomplish a 100% win rate within an optimal number of epochs. Therefore, it was necessary for the agent to initially explore the environment to build a Q-table detailing rewards for any action given a state. This table also incorporated the penalties for each invalid action. The agent was designed to then exploit the Q-table and environment nine out of ten times and explore one out of ten times, as defined by the epsilon. This allowed the agent to perform actions that were proven to be the most beneficial in any state while still attempting to identify potentially advantageous routes. Subsequently, the agent was able to identify an optimal policy by continuously modifying Q-values for action-state pairs.

### Miscellaneous Machine Learning Applications (NOTE: Each machine learning application .ipynb files has a thorough problem analysis at the end of the document):
- [Various Machine Learning Theory](https://github.com/CHenshaw010/Machine-Learning-Applications/tree/main/Machine%20Learning%20Theory)
- [Cartpole](https://github.com/CHenshaw010/Machine-Learning-Applications/blob/main/Cartpole%20Problem.ipynb)
- [CIFAR-10](https://github.com/CHenshaw010/Machine-Learning-Applications/blob/main/Identifying%20CIFAR-10%20Images.ipynb)
- [Hand-written Digits](https://github.com/CHenshaw010/Machine-Learning-Applications/blob/main/Identifying%20Hand-written%20Digits.ipynb)

### Personal Notes:
Connect your learning from this course to the larger field of computer science:
- The learning gained throughout this course connects to the larger field of computer science by incorporating the emerging and powerful trend of artificial intelligence (AI). This trend has become increasingly valuable given its applications to medicine, self-driving vehicles, and finance, to name a few. Subsequently, it is necessary for a computer scientist to understand how to understand and implement appropriate methods to aid in solving extremely complex problems experienced by society. In working towards this goal, I approach a problem by detailing the problem, what it aims to solve, potential solutions, and any ethical concerns requiring solutions. This allows a developer to fully understand the requirements necessary and the processes performed by each method.
- It is also highly necessary, as a developer, to understand the ethical responsibilities of the end user and the organization. As technology continues to expand, it is necessary to ensure all development is done in a manner that prevents any harm to the user. This involves the security of user information, effectively protecting sensitive data, preventing vulnerabilities, and actively developing new systems through a security- and privacy-conscious approach to minimize the possibility of privacy loss and computer crime. Furthermore, it is necessary to utilize ethically secure work processes to protect the organization from otherwise preventable liability.
