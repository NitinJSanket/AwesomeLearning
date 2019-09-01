# AwesomeLearning
Good courses, tutorials and websites to learn from.

## Courses
- [CMSC 733: Classical and Deep Learning Approaches for Geometric Computer Vision at UMD](http://prg.cs.umd.edu/cmsc733): The only course in the world which requires students to solve each project with  both classical and deep learning approach.
	- Homework 0: Pb lite boundary detection
	- Homework 1: Camera calibration
	- Project 1: Panorama stiching + Supervised and Unsupervised Deep Homography
	- Project 2: Face Swap +  Position Map Regression Network
	- Project 3: Structure from Motion 
	- Project 4: SfM Learner

- [CMSC 426: Computer Vision at UMD](https://cmsc426.github.io/): Arguably the hardest computer vision undergraduate course in the world. 
	- Homework 1: Linear Least Squares
	- Project 1: Color Segmentation using GMM
	- Project 2: Panorama Stitching
	- Project 3: RotoBrush (tracking felixble boundaries)
	- Project 4: Factor graph (GTSAM) based SLAM

- [CMSC 828T: Vision, Planning and Control in Aerial Robotics at UMD](https://cmsc828t.github.io/): UMD's version of MEAM 620 course at UPenn. Added Factor graph (GTSAM) based SLAM. 
	- Project 1: Implementation of A* based path planner, trajectory parametrization and following in simulation
	- Project 2: Factor graph (GTSAM) based SLAM 
	- Project 3: Flying through a known window using Parrot ARDrone 2

- [ENAE 788M: Hands On Autonomous Aerial Robotics](http://prg.cs.umd.edu/enae788m): Hands on and competition targetted version of CMSC 828T. 
	- Project 1a: Attitude estimation using Madgwick Filter
	- Project 1b: Attitude estimation using Unscented Kalman Filter
	- Project 2: Trajectory Following on the PRG Husky (Modified Parrot Bebop 2)
	- Project 3a: Flying through known colored windows
	- Project 3b: Detecting and landing on a circular bullseye target
	- Project 4a: Stereo Visual Odometry
	- Project 4b: Obstacle avoidance from front-facing monocular camera using pose form down-facing stereo visual odometry
	- Project 5: The final race
 
- [MEAM 620: Advanced Robotics at UPenn](https://alliance.seas.upenn.edu/~meam620/wiki/index.php?n=Main.HomePage): The full fledged version of the [Coursera's Robotics: Aerial Robotics](https://www.coursera.org/learn/robotics-flight?ranMID=40328&ranEAID=a1LgFw09t88&ranSiteID=a1LgFw09t88-3NmR539bPIQy37Hr_goZig&siteID=a1LgFw09t88-3NmR539bPIQy37Hr_goZig&utm_content=10&utm_medium=partners&utm_source=linkshare&utm_campaign=a1LgFw09t88) course. Covers concepts of quadrotor dynamics, controls and computer vision needed for quadrotor autonomy. The projects are given below:
	- Project 1: Implementation of A* based path planner, trajectory parametrization and following in simulation and on hardware.
	- Project 2: April Tag based pose estimation (given tag positions in the world frame), then using EKF to estimate velocities using optical flow **AND** SLAM with bundle adjustment (2016 offering) along with replacement of EKF by ESKF.
	- Project 3 (2015 offering): Implementation of CAPT and D-CAPT for multi-robot assignment **OR** implementing project 2 on hardware **OR**  estimation and control of Parrot Bebop.

- [CIS 581: Computer Vision and Computational Photography at UPenn](https://alliance.seas.upenn.edu/~cis581/wiki/index.php?title=CIS_581:_Computer_Vision_%26_Computational_Photography): The full fledged version of the [MIT edx's Robotics: Vision Intelligence and Machine Learning](http://www.edx.org/course/robotics-vision-intelligence-machine-pennx-robo2x) course. Covers concepts of convolution, edge detection, triangulation, TPS, RANSAC, seam carving, feature extraction and detection
	- Project 1: Canny Edge detection
	- Project 2: Image Morphing
	- Project 3: Image Mosaicing/Panorama Stitching
	- Project 4: Face Replacement

- [CIS 580: Machine Perception at UPenn](https://alliance.seas.upenn.edu/~cis581/wiki/index.php?title=CIS_581:_Computer_Vision_%26_Computational_Photography): The full fledged version of the [Coursera's Robotics: Perception](https://www.coursera.org/learn/robotics-perception?ranMID=40328&ranEAID=a1LgFw09t88&ranSiteID=a1LgFw09t88-Kg9dRKdVocU3NjuBiCQmZg&siteID=a1LgFw09t88-Kg9dRKdVocU3NjuBiCQmZg&utm_content=10&utm_medium=partners&utm_source=linkshare&utm_campaign=a1LgFw09t88) course. Covers concepts of 3D multi-view geometry including camera calibration, epipolar geometry, vanishing points, PnP, triangulation and Bundle Adjustment. Different variations of the following projects can be found on the [2019 offering](https://sites.google.com/seas.upenn.edu/cis580spr19/homeworks?authuser=0) of the course.
	- Homework 1: Dolly Zoom, Vanishing Points and Homography 
	- Homework 2: Single View Meterology
	- Project 3: Camera Calibration
	- Project 4: Structure from Motion
	
- ESE 650: Learning In Robotics at UPenn: The full fledged version of the [Coursera's Robotics: Estimation and Learning](https://www.coursera.org/learn/robotics-learning?ranMID=40328&ranEAID=a1LgFw09t88&ranSiteID=a1LgFw09t88-ofxEBfiJLwefUcivk8Ee5Q&siteID=a1LgFw09t88-ofxEBfiJLwefUcivk8Ee5Q&utm_content=10&utm_medium=partners&utm_source=linkshare&utm_campaign=a1LgFw09t88) course. Covers concepts of baeysian filtering for various applications.
	- Project 1: [Gaussian Mixture Models based color segmentation for Barrel Detection](https://github.com/NitinJSanket/ESE650Project1)
	- Project 2: [Unscented Kalman Filter based orientation estimation for panorama stitching](https://github.com/NitinJSanket/ESE650Project2)
	- Project 3: [Hidden Markov Models for Guesture recognition using IMU data](https://github.com/NitinJSanket/ESE650Project3)
	- Project 4: [SLAM on LIDAR Data using Particle Filters and Scan Matching](https://github.com/NitinJSanket/ESE650Project4)
	- Project 5: [Imitation Learning to learn costs for path planning](https://github.com/NitinJSanket/ESE650Project5)
	- Project 6: [ICP on RGB-D data for object reconstruction](https://github.com/NitinJSanket/ESE650Project6) **OR** Plane Fitting on RGB-D data using Mean-shift **OR** Fast IK planning of robotic arms

- [AUTONAVx: Autonomous Navigation for Flying Robots](https://jsturm.de/wp/teaching/autonavx-slides/): A toned down but more hands-on version of the MEAM 620 course at UPenn.
	- Refer for good and simple to understand slides for vision on quadrotors 

- [CSCI 5980: Multiview 3D Geometry in Computer Vision at UMN](https://www-users.cs.umn.edu/~hspark/CSci5980/csci5980_3dvision.html): Different variant of CIS 580 course at UPenn.
	- Refer for more polished slides (math explained more clearly with better figures) than CIS 580


## Tutorials


## Blogs


