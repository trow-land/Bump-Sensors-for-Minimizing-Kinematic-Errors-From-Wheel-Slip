# Software 3
This software package uses the PID controller output - PWM value to each wheel - to discern whent the robot has impacted an object. 
In order to maintain the demand speed when pushing the additional mass of the object, the controller must give a higher PWM value to the motors. Once the output value
surpasses a set threshold, we infer the robot has collided with the object and reset the x_position value in the kinematics. <br>

While the files are heavily commented to maximise readability, please feel free to contact me with any questions at: [zy22013@bristol.ac.uk](mailto:zy22013@bristol.ac.uk) or [tom_rowland@outlook.com](mailto:tom_rowland@outlook.com).
