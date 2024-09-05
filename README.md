# Hidden Markov Model (HMM)

## Project Overview
This project uses a Hidden Markov Model (HMM) to track the movements of a criminal between two cities: Los Angeles (LA) and New York (NY). The goal is to predict the most likely sequence of cities based on partial observations and evidence.

## Key Components

- **Observation Sequence**: A series of sightings and non-sightings of the criminal in LA and NY.
- **HMM Parameters**:
  - **Transition Matrix**: Describes the probabilities of moving from one city to another.
  - **Emission Matrix**: Describes the likelihood of sightings in each city.
  - **Initial Probabilities**: The starting probabilities for each city.

## Algorithms Used

- **Forward/Backward Algorithms**: Calculate the probability of the observed sequence.
- **Baum-Welch Algorithm**: Optimizes the HMM parameters to fit the observation sequence.
- **Viterbi Algorithm**: Finds the most probable sequence of hidden states (cities) based on the observations.

## Comparison
We compared our implementation with the `hmmlearn` library, verifying the accuracy of our results.

## Outcome
The project demonstrates how to use HMMs for state prediction and model optimization using real-world data.
