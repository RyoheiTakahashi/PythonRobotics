# PythonRobotics

Python sample codes for robotics algorithm.

# Requirements

- numpy

- scipy

- matplotlib

- [pyReedsShepp](https://github.com/ghliu/pyReedsShepp) (Only for reeds sheep path and RRTStarCar_reeds_sheep)

# Path Planning

Path planning algorithm.

## Model Predictive Trajectory Generator

This script is a path planning code with model predictive trajectory generator.

### Path optimization sample:

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/ModelPredictiveTrajectoryGenerator/kn05animation.gif)

### Lookup table generation sample:

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/ModelPredictiveTrajectoryGenerator/lookuptable.png?raw=True)

see: 
- [Optimal rough terrain trajectory generation for wheeled mobile robots](http://journals.sagepub.com/doi/pdf/10.1177/0278364906075328)

　

## State Lattice Planning

This script is a path planning code with state lattice planning.

This code uses the model predictive trajectory generator to solve boundary problem.


### Uniform polar sampling results:

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/StateLatticePlanner/Figure_1.png)

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/StateLatticePlanner/Figure_2.png)

### Biased polar sampling results:

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/StateLatticePlanner/Figure_3.png)

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/StateLatticePlanner/Figure_4.png)

### Lane sampling results:

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/StateLatticePlanner/Figure_5.png)

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/StateLatticePlanner/Figure_6.png)



## RRT 

Rapidly Randamized Tree Path planning sample.

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/RRT/animation.gif)

This script is a simple path planning code with Rapidly-Exploring Random Trees (RRT)

see (in Japanese) :

[PythonによるRapidly-Exploring Random Trees (RRT)パスプランニングサンプルプログラム - MyEnigma](http://myenigma.hatenablog.com/entry/2016/03/23/092002) 

## RRTStar

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/RRTstar/animation.gif)

This script is a  path planning code with RRT \*

- [Incremental Sampling-based Algorithms for Optimal Motion Planning](https://arxiv.org/abs/1005.0416)


## RRT Car 

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/RRTCar/animation.gif)

Path planning for a car robot with RRT and dubins path planner.


## RRTStarCar

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/RRTStarCar/animation.gif)

Path planning for a car robot with RRT\* and dubings path planner.


## RRTStarCar_reeds_sheep

![Robotics/animation.gif at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/RRTStarCar_reeds_sheep/animation.gif))

Path planning for a car robot with RRT\* and reeds sheep path planner.

## Dubins path planning

A sample code for Dubins path planning.

[Dubins path - Wikipedia](https://en.wikipedia.org/wiki/Dubins_path)

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/DubinsPath/figures/figure_1.png?raw=True)
![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/DubinsPath/figures/figure_13.png?raw=True)
![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/DubinsPath/figures/figure_15.png?raw=True)

## Reeds Shepp planning

A sample code with Reeds Shepp path planning.

![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/ReedsSheppPath/figure_1-4.png?raw=true)
![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/ReedsSheppPath/figure_1-5.png?raw=true)
![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/ReedsSheppPath/figure_1-7.png?raw=true)

## Closed Loop RRT\*

A sample code with closed loop RRT\*.

![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/CRRRTStar/Figure_1.png?raw=True)
![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/CRRRTStar/Figure_4.png?raw=True)
![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/CRRRTStar/Figure_5.png?raw=True)

see:

- [Motion Planning in Complex Environments
using Closed-loop Prediction](http://acl.mit.edu/papers/KuwataGNC08.pdf)

- [Real-time Motion Planning with Applications to
Autonomous Urban Driving](http://acl.mit.edu/papers/KuwataTCST09.pdf)

- [[1601.06326] Sampling-based Algorithms for Optimal Motion Planning Using Closed-loop Prediction](https://arxiv.org/abs/1601.06326)

# Path tracking

Path tracking algorithm samples.

## Pure pursuit tracking

Path tracking simulation with pure pursuit steering control and PID speed control.

![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathTracking/pure_pursuit/Figure_1-3.png?raw=True)
![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathTracking/pure_pursuit/2Figure_1-2.png?raw=True)
![PythonRobotics/figure_1-5.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathTracking/pure_pursuit/4Figure_1-2.png?raw=True)


## Rear wheel feedback control

Path tracking simulation with rear wheel feedback steering control and PID speed control.

![PythonRobotics/figure_1.png at master · AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathTracking/rear_wheel_feedback/animation.gif)

# License 

MIT

# Author

Atsushi Sakai ([@Atsushi_twi](https://twitter.com/Atsushi_twi))

