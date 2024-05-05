---
layout: page
title: Wind Tunnel Experiment
description: Assessment of the characteristics of an airfoil and a 3D wing using wind tunnel tests and numerical simulations.
img: assets/img/LTT-windtunnel-large.jpg
importance: 3
category: BSc Academic Work
related_publications:
---

Every produced aircraft, flying millions of people and goods worldwide every year, relies on the design of many engineers to ensure safe and efficient flight conditions. But when it comes to aerodynamics, how does one verify the design before testing with humans, or large investment into flying prototypes which otherwise may not even function? The most common techniques include computer simulations and wind tunnels, but they are both open to errors, inaccuracies, or differences from the real world results, especially in the case of simulations. It is also possible to test an airfoil, when planform dimensions are not yet chosen, or to test a full wing where the planform design has been chosen at this point. Often, wind tunnels are fully booked and are too expensive or inaccessible. In this case, it is vital to understand the differences between simulations and experimental results in order to predict what the real world results may be.   




This report aims to test, show results for, and compare the above tests for a NACA 64<sub>2</sub> A-015 airfoil, while also showing and explaining the key expected phenomena of the wing in each of the following cases:

<ul>
    <li>In the first case (the simulation case) the airfoil and wing are simulated in XFLR5, which is shown to overestimate the characteristics of the airfoil and wing due to simplifications, and underestimate the induced drag by the wing tip vortices in the finite wing case, as well as being unable to predict the effects of viscosity. </li>
    <li> In the second case (the experimental case) the airfoil is tested in the Low speed wind tunnel at the TU Delft. This case is much more accurate and capable of displaying characteristics including the stall characteristics of the wing than the simulation, especially in the airfoil case where the 2D simulation theory cannot predict separation or turbulence accurately.</li>
</ul>







Many flow phenomena were noted, and their occurrence with respect to angle of attack, location on the chord, and strength are compared and noted for each case. These include laminar and turbulent boundary layers, laminar separation bubbles, turbulent separation, stall, hysteresis, and flow reattachment. These phenomena are found and analysed using visible light cameras, electronic pressure scanners, infra red cameras and heat lamps, wake pressure rakes, and force balances.






These flow phenomena all have significant impact on the different polars observed for the airfoil and wing. The main findings were that a second linear part is initiated in the C<sub>l/L</sub>-α curve, the sudden drop in lift and moment coefficient and increase in drag coefficient due to laminar stall. However, the above mentioned account more for the experiment than the simulation. For the simulation the main finding was that it is quite accurate until stall for the 2D airfoil analysis as for the airfoil analysis the program did account for the viscous effects. While for the wing the viscous effects were interpolated from the airfoil analysis leading to bigger differences.






It is advised to use a combination of all methods when testing a wing, so as to streamline and minimise costs, and since this report has shown that particularly for the 3D case, there are a number of vital characteristics especially in the critical stall regions, but also even in the cruise regions of angles of attack which are not accurately modelled in XFLR5 simulations. Nevertheless, when taking that into account while being in the preliminary phase of the design it can be used as a reasonable indication of what to expect.




<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/WT_TU.pdf" width="1000" height="1000" type="application/pdf"></object>
