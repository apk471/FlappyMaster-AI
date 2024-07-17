# FlappyMaster AI

An AI that plays flappy bird! Using the NEAT python module.

## Demo Link

<a href="https://drive.google.com/file/d/1KuZac2kwFwbl0BjqMcfwssmzGxOduhLU/view?usp=sharing">Video Link Click Here</a>

## Neural Network Architecture

The NEAT (NeuroEvolution of Augmenting Topologies) Python module utilizes a feedforward neural network architecture for training AI agents to play Flappy Bird. The neural network consists of an input layer, one or more hidden layers, and an output layer.

The input layer receives information about the game state, such as the bird's position, the distance to the next pipe, and the bird's velocity. This information is used to make decisions on whether to flap or not.

The hidden layers perform computations on the input data, applying weights and biases to the inputs and passing the results through activation functions. These hidden layers enable the network to learn complex patterns and make more accurate predictions.

The output layer produces the final decision of whether to flap or not. It typically consists of a single neuron that outputs a value between 0 and 1, representing the probability of flapping. If the output value is above a certain threshold, the AI agent flaps; otherwise, it does not.

During the training process, NEAT evolves the neural network's structure and adjusts the weights and biases to optimize the AI agent's performance in playing Flappy Bird.

## Instructions And Installation

Simply run app.py and watch an AI start training itself to play the game of flappy bird!

```bash
git clone https://github.com/apk471/FlappyMaster-AI.git
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```
