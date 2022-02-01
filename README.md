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
<p align="center">
<img src="https://user-images.githubusercontent.com/70687643/152009300-acf72542-9b4c-4112-b95c-2e52df907e72.png" width =365">
<img src="https://user-images.githubusercontent.com/70687643/152004347-176ae085-5a5a-4998-baf3-278f300b4252.png" width =315">
</p>
<p align="center">
<img src="https://user-images.githubusercontent.com/70687643/152009318-be6bf05c-d3f0-4fd1-9db4-e4ab7eb7b88f.png" width =265">
<img src="https://user-images.githubusercontent.com/70687643/152009342-007cb95c-23a4-47b4-ab26-6cbfa041c6c3.png" width =465">  
<img src="https://user-images.githubusercontent.com/70687643/152006136-abebd144-b308-4ca4-b869-c897b410f640.png" width =475">
</p>


## Demo

https://user-images.githubusercontent.com/70687643/152028585-9c39e807-2896-4c27-9af0-7c274018833a.mp4



