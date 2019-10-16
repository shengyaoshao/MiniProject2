
# Mini project2
## Introduction
The topic for this project is the autonomous wheelchair. Wheelchairs give many people with disabilities the freedom to move around. But for those with both leg and arm disabilities, using the wheelchair on their own is extremely challenging. Creating an autonomous wheelchair using the ROS platform might be the solution to this problem.\
\
ROS is short for Robot Operating System. But unlike what the name suggests, ROS is not an operating system in the conventional sense; it is an open-source platform for users to design, implement, and test their robot projects. Being an open-source platform, it has a ton of existing resources users can use to help build their projects.  ROS also provides users with tools and libraries for obtaining, creating, writing, and running codes across multiple computers. 
## Reference
https://pdfs.semanticscholar.org/6b87/5426f812f8225c2bb20755ebe855cf5e09fb.pdf ROS-based Autonomous Navigation Wheelchair using Omnidirectional Sensor. International Journal of Computer Applications (0975 – 8887). Journal about a prototype autonomous wheelchair.\
http://wiki.ros.org/ROS/Introduction Basic introduction of ROS form the ROS official website.
## Analysis of the ROS-based Autonomous Navigation Wheelchair
The ROS-based Autonomous Navigation Wheelchair consists of hardware and software. For the hardwares, they chose the Bora wheelchair model which was electric powered and had an embedded system that can communicate with other systems. they also used the GPSB board to control the wheelchair's directions and speed. An Omnidirectional Camera was mounted on top of the wheelchair to provide vision data for the system to configure the surroundings, distance as well as obstacles in almost 360 degrees. Multiple sensors were placed on the wheelchair to detect the surroundings as a supplement to the Omni directional camera.\
\
The research group had two main algorithm, the vision based localization algorithm and collision avoidance algorithm. The vision based localization algorithm consisted of camera calibartion, features detection and correspndence, and essential matrix and 3D trangulation. The collision avoidance algorithm fuses data from the US/IR platform to detect and avoid obstacles on the way.\
\
For the use of ROS, there are pros and cons\
\
Pros:
1. ROS supports many languages like python and C++
2. ROS is open-source which means there are many exsisting resources to use
3. Easy integration of different tools
\
Cons:
1. There are two versions of ROS, ROS1 and ROS2, some software may not support both.
2. ROS can only be used on a limited numbers of OS.
## Recommendations
I highly recommend using ROS for robot projects. There are a lot of tools and libraries to realize the goals of the autonomous wheelchair project. And the report about the autonomous from International Journal of COmpter Applications could also be a guidence for this project.
## Conclusion
ROS has its advantages and disadvantages, but the advantages greatly weigh over the disadvantages. It has a collaborative and informative community, it supports many languages so the developers can choose whichever the language that suits their projects best. The massive libraries and tools give the developers opportunities to explore better solutions to their problems and more angles to view their projects.
