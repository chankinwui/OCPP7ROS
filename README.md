# Introduction
Did you see Electrical Vehicle (EV) around you 5 years ago? How about today?
Do you see robots around you?Probably you have seen in some indoor locations, such as restaurant,shopping mall and factory. 

I am sure that "they" will go outside some years later for whatever reasons. Nowadays, there are some examples already, such as the "dog", delivery drones and patrol polices.
I think the day like in the "Big Hero 6" and "RoboCop" is not too far away from us. But what are the EVs and robots in common? They both need energy and thus charging!

The de facto standard  protocol for EV charging is OCPP (Open Charge Point Protocol), while almost all robots support ROS (Robot Operating System). 
Unfortunately they cannot talk to each other right now.

In this project, we are going to implement a gateway between OCPP (version 2.0.1) and ROS (version 2). Simulators (EV,AC/DC charger,robot)following the protocols will be implemented too. Some basic knowledge of each technology is assumed.
![1667316115855](https://user-images.githubusercontent.com/3295412/199270033-2c4082f4-c211-46e0-9ba8-b9f0a565e3c3.png)



