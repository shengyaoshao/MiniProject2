
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

### Team Paper Reviews

#### Yanyu Zhang
Yanyu's report mainly introduces ROS to the viewers. In the first part of his report, he introduces the concept of ROS, some of the features of ROS, and how versatile it is. The second Part of his report is about the main core concept of ROS, Master and Nodes.He mentioned how to install and use ROS as well as its pros and cons which would be very useful for those who are thinking about using ROS for their robot projects. The last part of the report briefly talked about self-driving wheelchair based on ROS.

#### Yu Liu
Yu's report first introduces the concept of ROS, its architecture, integration and core componets. He also briefly discusses the autonomous wheelchair project. The wheelchair could perform almost perfectly when moving on a straight line but have trouble when turning depending on how complex the path is. Then he compares the advantages and disadvantages of ROS. The author believes ROS is powerful enough to develop a self-driving wheelchair.

#### Matthew Boyd
Matthew's report compares ROS 1 and ROS 2. The introduction shares the background  knowledge about these two versions of ROS. The analysis prat of the report uses a chart to show the readers how ROS 1 differs from ROS 2 in multiple ways. In the recommendations section, based on the user / project type, the author briefly explains which version would be more favorable. In the references, the author lists all the sources and discusses how these websites can be useful when learning how to use ROS and how to choose between ROS 1 and ROS 2. The author believes that both ROS 1 and ROS 2 are great for robot projects, and even though the future will be ROS 2's, but ROS 1 isn't going to be replaced any time soon for there are so many tutorials, projects, repositories and experts in ROS 1 which make ROS 1 a great starting point for those who are new.

#### Haik Martirosyan
Haik's report focuses on two uses of ROS in the medical field. The first one is its use in surgery (da Vinci Surgical Robot) and the second is the autonomous navigation wheelchair based on ROS. In the first section, the author addresses the advantages of doing surgeries with the help of robots. The research shows that using da Vinci Surgical Robot doesn't affect the surgical results or oncological rate for liver surgery for colorectal liver metastases. The author points out that this research is limited due to the shortage of data and the lack of comparision between different medical centers but only between the traditional way and new way. Overall, the author believe this report successfully shows the benefits of using robots to assist surgery if the surgeon is experienced. In the second section, the author disscusses a the implementation of autonomous wheelchair. There are many factors that can affect the performance such as sensor or algorithm. The author believes there are still a lot of room for improvement comparing to the surgical robot for this idea is more recent.
