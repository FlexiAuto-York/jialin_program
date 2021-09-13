# Jialin-Zhou-Project
This is Jialin Zhou's dissertation project in The University of Sheffield
This project aims to develop an algorithm to make a swarm of aerial robots find and aggregate in a load with unknown shape.

This includes
(1) Coppeliasim
    
    a. According to the different method, different ROS message is implemented in these scenes.
    
    b. The interface has been recomplied with customized ROS message
    
(2)ROS_Programme

    a. this includes low-level controller and swarm algorithms(PFSM, Manta Ray and B&F)

    b. this includes 2 ROS nodes, only in Manta Ray method, the node "Manta best position" should be runed
    
    c. when different method is transfered, the different swarm algorithm's controller should be modified in "drone.h"

It has been proved in following three shapes
![S](https://user-images.githubusercontent.com/81184853/133011966-42fb4cda-430b-450c-9dc9-7815f9167c82.png)
![Screenshot from 2021-08-28 00-13-55](https://user-images.githubusercontent.com/81184853/133011981-6a6d0706-720e-49cd-9d3a-f89ea427ffe8.png)
![Screenshot from 2021-08-28 18-22-08](https://user-images.githubusercontent.com/81184853/133011985-cc125a23-3023-4f92-9823-a03c8b084038.png)
