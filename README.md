# Automated Negotiating Agents Competition (ANAC) (Pappous Agent)
> Agent participating to local ANAC competition in Technical University of Chania 

## Table of contents
* [General Info](#general-information)
* [Implementation](#implementation)
* [Setup](#setup)
* [Screenshot](#screenshot)
* [Acknowledgements](#acknowledgements)

# Introduction
The project concerns participation of the agent in a Final Internal Competition ANAC. Genius is a negotiation environment that implements an open architecture for heterogeneous negotiating parties. Genius can be used to implement, or simulate, real life negotiations. 



# Description of Agent
General Idea. A heuristic agent that follows 4 basic rules for accepting bids.
1) Upper & Lower Bounds for expected utility. <br />
2) Differentiation of bounds in time. <br />
3) Own  & Opponent Bid History. <br /> 
4) Send Bid with Reservation Value at the end of the deal. <br />


# Decide Offer
1)First move of the player is chosen as the best possible <br />

2)Select Bid that have utility in a specific range <br />

3)The selected Bid depends on the evaluation of the previous move <br />

4)At the end of the negotiation the minimum offer touches the Reservation Value <br />

5)A bid history is used when the transaction is in the final stretch <br />


# Bounds
Upper Bound differ from 1 to 0.8 <br />

Lower Bound differ from 0.65 to 0.52  <br />


The implementation is a union of existed agents worked in ANAC agent. 

## Setup
Java Integrated Development Environment (Eclipse IDE)

# How to run
Genius can run on any machine running Java 8. Java 9 is not yet supported.

1. Download the file `genius-XXX.zip` from
```
http://ii.tudelft.nl/genius/?q=article/releases
```
and unzip it to your machine.

1. Install the environment, the file `genius-XXX.zip`


# Screenshot






## Acknowledgements
- This project was created for the requirements of the lesson Multiagent Systems

