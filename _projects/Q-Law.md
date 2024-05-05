---
layout: page
title: Implementation and Improvements of the Q-Law
description: Development of a computing software to generate near-optimal low-thrust trajectories, performed at the German Aerospace Agency.
img: assets/img/DLR_Research.png
importance: 2
category: Independent Research
related_publications: veithen2024QLaw
---

Electric propulsion enables ambitious and affordable space missions by substantially reducing the fuel mass required in comparison to lower specific impulse propulsion. However, the optimisation of the according transfer trajectories is particularly challenging due to their typically low thrust characteristics, resulting in many-revolution transfers with many local minima and highly non-linear dynamics. By optimising its weights using the PIKAIA genetic optimiser, the Q-Law guidance algorithm is able to provide near-optimal low-thrust trajectories with minimal computational effort which can be used either as initial guess for the optimisation to ensure a faster convergence or directly for mission analysis. During his internship, the author worked on the implementation of an initial guess generation software for low-thrust trajectories using the Q-Law. Based on an initial implementation, the coasting mechanism of the control law was added, enabling a new type of low-thrust trajectory design. Following, the Modified Equinoctial Elements (MEE) and Keplerian formulations of the Q-Law were implemented to supplement the already available AMEE formulation. Finally, as the control law does not permit to target a specific position in the final orbit, the initial guess was found to be very poor for optimisations where such final position is a constraint. Such a constraint could be the geographical longitude when acquiring a geostationary orbit, but also the position within a constellation of LEO or MEO satellites or within a rendezvous scenario. Therefore, a predictor-controller approach was devised and implemented to enable Q-Law six-element targeting capabilities in any bounded final orbit.


The coasting mechanism permits to spare propellant mass in exchange for a longer time of flight, but the required propellant mass decrease gets smaller as the time of flight increases. Following, there is not one superior formulation, meaning that all must be considered to find the best initial guess for a given transfer design problem. Finally, the predictor-controller approach is successful for GEO and eccentric orbits, permitting to target a specific position in the final orbit for a 0.2% mass increase on average. However, it was found to struggle significantly for the circular case, with only 10% of the propagations converging to the final orbit at the correct position (against 90% for GEO and 60% for eccentric cases). Overall, the work presented in this report resulted in a complete state-of-the-art implementation of the Q-Law.


Further work on the computing software and the developments of the Q-Law should include the implementation of a minimum burn arc length, tuning of the PIKAIA optimiser settings and consideration of multiple seeds in the genetic optimisation, further analysis of the fast element targeting algorithm to better understand the influence of each parameter, and the investigation of solutions reducing or removing the thrust chattering phenomenon.


The details of this work are company-protected but the devised predictor-controller approach for 6th element targeting was presented at the International Symposium on Space Flight Dynamics in April 2024. The related paper can be found below.
