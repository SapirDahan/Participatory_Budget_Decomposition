# Participatory Budget Decomposition

This project solves the participatory budget decomposition problem using a flow network.

Each citizen must contribute an equal share to projects they support. A directed graph is built where:
- Source connects to citizens.
- Citizens connect to their preferred projects.
- Projects connect to the sink with edges equal to their required budgets.

A valid decomposition exists if the maximum flow equals the total required budget.