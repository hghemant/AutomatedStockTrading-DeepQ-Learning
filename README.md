# Deep-Q-Stock-Trading


Please find the project inside a Zip file with multiple folders:

State: Contains the state.py file.
Agent: Contains the Agent.py file.
Trading.ipynb: This file includes the following functionality:
Data pre-processing (3.1)
Agent training with 51 episodes, using the following parameters:
Stock1_name: Apple (aapl.us)
Stock2_name: Amazon (amzn.us)
episode_count: Number of episodes for agent training
Start_balance: Initial starting cash ($10,000)
Training: Number of records used for trading (number of days per episode)
Test: Number of days for the test run
Evaluation and final program that predicts the total portfolio value for one episode (3.3)
Models are saved in the model directory. To execute the program, run the Trading.ipynb file with the specified input parameters and examine the results.

There are also other files available: Testing-Google n Walmart.ipynb and Testing-IBM n GE.ipynb. These can be used to test the model generated in Trading.ipynb, which is stored in the Models directory.

References:

MACHINE LEARNING FOR TRADING: GORDON RITTER: https://cims.nyu.edu/~ritter/ritter2017machine.pdf

Financial Trading as a Game: A Deep Reinforcement Learning Approach: Huang, Chien-Yi https://arxiv.org/pdf/1807.02787.pdf

Convergence of Q-learning: a simple proof: Francisco S. Melo: http://users.isr.ist.utl.pt/~mtjspaan/readingGroup/ProofQlearning.pdf

https://medium.com/@chinmaya.mishra1/deep-dive-in-to-reinforcement-learning-10fa30b418f9

David Silver’s lectures about deep reinforcement learning

