## Flexbus
This repo implements an interesting research direction being pursued at NYU's C2Smart lab around flexible, dynamic bus routing.

In particular, we set up a series of potential routes with one branching point. The idea is the bus will choose to run any one of these 3 routes based on the current user demand. This approach helps to minimize decisions. Then, we define an integer linear program (ILP) to make the decision of which route to take, based on wait and travel-time-cost for each user (including walking if the bus runs a route that would drop them off farther from their ultimate destination).
