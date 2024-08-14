# RouletteAnalysis

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Dataset Description](#dataset-description)
4. [Data Visualisation](#data-visualisation)
5. [Results](#results)
6. [Conclusions](#conclusions)
7. [Future Work](#future-work)
8. [References](#references)

## Introduction
Roulette has been played for hundreds of years. The game has given players the potential to make quick money but great reward doesn't come without risk. Though the saying "The house always wins" exists, players continue to search for strategies to tip the scales and beat the odds. The ability to gain even a slight advantage over the house, given the law of large numbers, would allow players to potentailly change their fate.

This project aims to analyse the Martingale strategy to determine whether or not it gives a roulette player the ability to beat the game, outline the specific requirements and potenial ROI. By exploring the simulation of this strategy, we can answer questions such as:

- Can a player guarantee a profit from roulette?
- What would the player require to be successful?
- What are the limitations of this strategy?
- Can this strategy be optimised?

Through comprehensive data analysis, this project will provide a detailed understanding of the Martingale strategy. The findings from this analysis can help players, looking to leverage the Martingale strategy, gain an understanding and raise awarness to casinos of the potential.

The data used will be gathered from a locally created instance of the game. Data collected and monitored will include bank roll, time elapsed, profit/loss, multiplier, iteration and bet. By leveraging this data, I will determine the potential success /failure of the strategy.

## Objectives
- Analyse the results of the Martingale strategy.
- Identify potential strengths and weaknesses.
- Determine whether or not the stratgy is successful.
- Calculate the ideal bankroll to expected return.

## Dataset Description
### Source
- The dataset will be created by pulling results from my instance of the game.
  
### Features
- `ID` : The ID of the bet.
- `Time`: The time the spin ended.
- `Balance`: The players balance after the bet is made.
- `Multiplier` : How much the intial bet is being multiplied by.
- `Iteration` : How many times the bet has been doubled from the base amount.
- `Red` The amount the player has bet on the specified colour: .
- `Black` The amount the player has bet on the specified colour: .
- `1-18` The amount the player has bet on the specified range: .
- `19-36` The amount the player has bet on the specified range: .
- `Odd` The amount the player has bet on odd: .
- `Even` The amount the player has bet on even: .

## Data visualisation

## Results

## Conclusion

## Future work

## References
