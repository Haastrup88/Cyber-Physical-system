# Cyber-Physical-system
This model shows a discrete Time simulation of a ground Vehicle. 
The two inputs were considered force/thrust and angular velocity.
The model includes three states; Horizontal position(x1), Vertical position(x2), and orientation(x3).
The transfer model is as shown below;
x1plus=x1+ d*sin(x3)*v1
x2plus=x2+ d*cos(x3)*v1
x3plus=x3+ c*v2

c & d are constant called sampling time. All these defined the transfer functions 'G' of the Ground Vehicle.

