# SegwaySystem <img src="https://user-images.githubusercontent.com/70687643/151966365-045f5b31-8008-42da-92f2-6ef38ff32c81.png" width ="35"> 
__[Updated: 1 Feb 2022] More detailed explanation to come...__


Welcome to the README of SegwaySystem, a built-in controller model of a pendulum system using bond graph theory.


## The Challenge
Designing a controller using 20sim and Matlab capable of accomplish:
1. Model a pendulum's physics.
2. Control the motor's electrical signal based on the model for:  
  ```
  a. Make segway stand still. 
  b. After disturbance ensure segway stand still. 
  c. Drive the segway, turn around and brake.  
  ```

## Controllers
* Following the controllers implemented in this model:  

> Pendulum model: models the physics behing free fall of a pendulum object.   
> Angle PID Controller:controlls the rotation of the wheels of the segway.  
> Velocity Wheel controller: limits how fast the wheel of the segway can accelerate. 

## Images
<p align="left">
<img src="https://user-images.githubusercontent.com/70687643/152004347-176ae085-5a5a-4998-baf3-278f300b4252.png" width =365">
<img src="https://user-images.githubusercontent.com/70687643/152006136-abebd144-b308-4ca4-b869-c897b410f640.png" width =475">
</p>


## Demo

https://user-images.githubusercontent.com/70687643/152005048-658f98d5-b57e-4019-9f46-8f85e9143d7c.mp4


