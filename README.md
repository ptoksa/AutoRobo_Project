# AutoRobo Project
Many of the work processes and tasks demand great precision, error-free operations and high quality outcomes. Humans are not at their best in these actions. Due to this human frailty, a lot of duties can be assigned to be carried out by automatized platforms. Healthcare and hospice operations retain processes which can be assisted by mobile robots. The service architecture model developed in Tampere University, Pori, consists of a novel mobile cloud robotic platform in the support of patient work. The ecosystem, OpenCRP, holds an open-source cloud-computing platform, software frameworks and a physical multi-robot environment for the automation or assisting of preprogrammed work processes.
## Goal
Mobile robots with service-oriented functions are stepping to our lives in hospitals, hospices and industries where robots can help to assist or perform all the arduous working duties. Many laborious processes can be identified and automatized, e.g. in hospital medicine delivery and food servery to ward for patients. The service architecture model presents a pilot and demonstration environment for multiple open-source mobile robots sharing their collected data with each other via a private cloud. In addition, the presented platform introduces a novel ecosystem based on an open-source software frameworks and robots.

## DiaVire Pilot Project
The pilot project will specifically identify applications for health care and pilot the robotics solution to be implemented in Kuntoutuskoti DiaVire. The Autonomous Robot Ecosystem project utilizes the technical environment implemented in the OpenCRP (Cloud Robotic Platform) project.

Turtlebot2 was used as a mobile robot with Kinect Xbox 360 3D sensor. The mobile robot is controlled by a laptop computer running the Linux operating system, which has an open source ROS operating system developed for robot control. The mobile robot operates in a wireless network, moves in a given area completely autonomously, and the robot can be monitored and controlled from a remote device. The robotics solution can also utilize the information sent by IoT devices and sensors.

The robot's interface is designed to work in a web browser and is used on the touchscreen installed on the robot. The user interface has a memory game, news, audiobook and room guidance. In addition to the visual instructions in the user interface, the robot also uses speech to guide the person. In addition, the robot's camera can be utilized in subject recognition. With these features, the purpose of the robotics solution is to transfer part of the routine of the nursing staff to the robot, utilizing a robotics solution to activate and guide patients with memory disorder or general aging people, as well as control tasks.

## Robot Platform Hardware and Software
* Ubuntu 18.04 + ROS Melodic + TurtleBot2 + MS Xbox Kinect / RealSense 435 / A2 RPLidar + Google Tensorflow 1.14
* Additional Robot On-Board Hardware: Jetson Nano, 10” USB Touchscreen, external speakers
* ROS: gmapping, AMCL, rviz, rosbridge 2.0, rqt graph, TurtleBot launch-files
* Programming Software: Python 2.7 / 3, YAML, PGM (Portable Greyscale Map), HTML, JavaScript (modifications for Brain Farmer memory game)

## ERDF
ERDF project information (in finnish): https://www.eura2014.fi/rrtiepa/projekti.php?projektikoodi=A73560
