Basic tutorial for training feed-forward neural networks with genetic algorithms

This code uses a genetic algorithm to train a feed forward neural network to learn to approximate the cosine function.

The only (necessary) dependencies are basic: numpy, random and math.

Note that this is written and published only with education purposes in mind, real-world training of neural networks is generally much more efficient with backpropagation.

Genetic algorithms are worth understanding because, while being time-consuming, they make no requirements for end-to-end differentiability, can handle discrete values (although not done here) and are easy to code.

Python 3