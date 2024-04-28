# Stock Trading Bot Using Reinforcement Learning

## Introduction
This project utilizes Deep Q-Learning, a form of reinforcement learning, to train a stock trading bot on historical stock price data of S&P 500 companies. The bot learns optimal trading strategies by maximizing cumulative returns over time.

## Dependencies
1. Python 3.x
2. TensorFlow
3. Keras
4. Pandas
5. NumPy
6. yfinance
7. Matplotlib
8. scikit-learn

## Usage
1. Open the Stock_Trading.ipynb notebook in Google Colab.
2. Run each cell in the notebook sequentially.
3. You can modify the notebook as needed to experiment with different parameters, architectures, and datasets.

##  Model

The stock trading bot utilizes a Deep Q-Learning (DQN) model for making trading decisions. Here's an overview of the model architecture and its functioning:

1. **Architecture:** The DQN model consists of multiple fully connected layers, typically with Rectified Linear Unit (ReLU) activation functions.
2. **Input:** The input to the model is a vector representing the current state of the environment, which includes historical stock price data for multiple companies.
3. **Output:** The output of the model is a vector representing the estimated Q-values for each possible action the agent can take.
4. **Training:** During training, the model is updated using the Bellman equation, which iteratively improves the Q-value estimates based on observed rewards and predicted future rewards.
5. **Target Model:** To stabilize training, a target model is used by periodically updating its weights with the weights of the main model.
6. **Customization:** The architecture and hyperparameters of the DQN model, such as the number of hidden layers, number of neurons per layer, learning rate, discount factor, etc., can be customized based on the requirements of the trading task and the characteristics of the data.

## Contributing
Contributions to this project are welcome. Please feel free to submit bug reports, feature requests, or pull requests.
