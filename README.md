
# What Impact Will the Swiss Style Changes have on the Chance to See a Western team Win Worlds 2023?

This repo is to house a project designed to explore what the 2023 League of Legends international tournament structure changes might have via a Stochastic Simulation and has slowly developed into a full-fledged side-project that I have worked on occasionally alongside my PhD. Anyone interested in either an application of stochastic simulation to explore a possible change in events or a League fan who wants to know more about the simulation can find the code and details here. I've done my best to detail each step within the notebook such that the process is readable for both non-scenario readers and non-simulation/non-statistics readers. The simulation makes multiple assumptions that simplify the events, which are outlined in the preamble of the file. There are multiple interesting extensions to this project to explore how different regions might suffer from fatigue or require a warm-up throughout the tournament, how different seeds from regions have different strengths, and how different teams might be able to be classified as either Strong, Average or Weak representatives from a given region. Each of these would impact the results of the simulation if a suitable element of historical data were able to be effectively represented in the simulation. This project was posted on Reddit for anyone in the League space to dig into should they wish, link is **here eventually**.

This isn't an extremely complex project to deploy. Everything can be run from the notebook =).

I began putting together a Stochastic Simulation to explore what the Swiss changes might have on Worlds, 


## Authors

I'm the only author of the project. This began as a side project to demonstrate an example of a stochastic simulation that could be applied to the current scenario and developed into a full side project. If you catch any bugs or problems, feel free to ping me =).
- [@JordanJHood](https://www.github.com/JordanJHood)


## Overview

- Group each international match since 2015 by Region
- Construct Posterior Probability of Each Region win probabilities
- Use Posterior probabilities to construct international matches and brackets
- Simulate a typical historical tournament
- Simulate the new (as of writing) unobserved Swiss Structure
- Compare and discuss results across the simulations

## Highlight Results
The introduction of the Swiss stage gives Western teams a 33% relative increase in the estimated chance of winning Worlds versus a Swissless simulation (up from 1.5% to 2.1%), and a further relative improvement of a Western team making it to finals by approximately 50% (from 6.8% to 10.24%). We also observe that the Swiss stage has improved the chances of a Western team making it through to the knockout stage, with the odds of at least one Western team making it out improving from 84.5% to 96.7%.
