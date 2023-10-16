
# What Impact Will the Swiss Style Changes have on the Chance to See a Western team Win Worlds 2023?

This repo is to house project designed to explore what the 2023 League of Legends international tournament structure changes might have via a Stochastic Simulation. Anyone interested in either an application of stochastic simulation to explore a possible change in events or a League fan who wants to know more about the simulation can find the code and details here. I've done my best to detail each step within the notebook such that the process is readable for both non-scenario readers and non-simulation/non-statistics readers. The simulation makes multiple assumptions that simplify the events, which are outlined in the pre-amble of the file. There are multiple interesting extentions to this project to explore how different regions might suffer from fatugue or require a warm up though-out the tournament, how different seeds from regions have different strengths, and how different teams might be able to be classified as either Strong, Average or Weak representatives from a given region. Each of these would impact the results of the simulation if a suitable element of historical data were able to be effectively representated in the simulation.

This isn't an extremely complex project, especially to deploy. Everything can be run from the notebook =).




## Authors

I'm the only author of the project. This began as a side project to demostate an example of stochastic simulation that could be applied to current scenario, and developed into a full side project. If you catch any bugs or problems, feel free to ping me =).
- [@dvder10](https://www.github.com/dvder10)


## Overview

- Group each international match since 2015 by Region
- Construct Posterior Probability of Each Region win chance
- Use Posterior probabilities to constuct international matches and brackets
- Simulate typical historical tournament
- Simulate the new (as of writing) unobserved Swiss Structure
- Compare and discuss results across the simulations

