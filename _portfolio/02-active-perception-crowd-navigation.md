---
title: "Active Perception for Robot Navigation in Crowds"
excerpt: "Robotics and Mechatronics Laboratory, University of Miami · November 2026–present<br/>Helping a robot with a narrow camera decide where to look as it moves through a crowd, by modeling where and how often pedestrians it has not seen yet will appear."
collection: portfolio
permalink: /portfolio/active-perception-crowd-navigation/
---

**Robotics and Mechatronics Laboratory, University of Miami** · Graduate Researcher · November 2026–present

A robot moving through a crowd with a forward-facing camera sees only a cone in front of it. People approaching from the side are detected late, so the robot has to plan around pedestrians it has not seen yet. This lab project studies active perception: the robot chooses where to point its camera as it moves, so that it sees the people who matter most for the path it plans to take.

I work on the model of pedestrians the robot has not seen yet, which tells the tracker and planner where and how often new people are likely to appear.

* **Appearance analysis:** extracting where, when and how fast new pedestrians enter each scene of the public ETH and UCY pedestrian datasets.
* **Arrival model:** a Poisson arrival process with a map of where arrivals happen, built both as a grid and as a kernel density estimate, and scored on held-out parts of each recording.
* **Robot's point of view:** replaying the recordings past a simulated robot camera to separate people who are new to the scene from people who were already there and walked into view.
* **Tracker integration:** packaging the model as a drop-in replacement for the arrival map in the lab's pedestrian tracker, and checking its effect on tracking accuracy.

## Plans

* Model arrival rates that change over time and with the crowd around the robot, since people tend to arrive in waves and groups.
* Extend the field-of-view analysis to a robot that moves and turns, and to pedestrians hidden behind other pedestrians.
* Measure the effect of these changes in the lab's tracking and navigation experiments.

*Results and figures coming soon.*
