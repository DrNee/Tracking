# Tracking

In this project, completed for CS188 (Introduction to Artificial Intelligence), the goal is to use Pacman's faulty sensors (that we can model using probabilities) to have him locate and eat invisible ghosts. 

In order to do so, I make use of Bayesian Networks (BNs) and Hidden Markov Models (HMMs). After building these models within the game's context, I implemented exact inference, approximate inference (sampling the Bayes Net via Rejection Sampling, Likelihood Weighting, etc.), HMM exact filtering (time elapse + observation weighting), and a Joint Particle Filter for the HMM. 

All of this effort allowed me to create belief distributions about the location of the invisible ghosts, based on which Pacman could move and track down the ghosts.

![Imgur](https://i.imgur.com/szteVMb.png)
![Imgur](https://i.imgur.com/OgToQlb.png)
