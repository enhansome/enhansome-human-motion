# Awesome Human Motion with stars

> 🏃‍♀️ A curated list about human motion capture, analysis and synthesis.

## Contents

* [Introduction](#introduction)
* [Human Models](#human-models)
* [Datasets](#datasets)
* [Data Processing](#data-processing)
* [Pose Estimation](#pose-estimation)
* [Motion Analysis](#motion-analysis)
* [Motion Synthesis](#motion-synthesis)
* [Researchers, Institutes, Projects](#researchers,-institutes,-projects)
* [Commercial Projects](#commercial-projects)
* [Journals](#journals)
* [Conferences](#conferences)
* [Videos](#videos)

## Introduction

* [Human Pose and Motion](https://github.com/daitomanabe/Human-Pose-and-Motion) ⭐ 55 | 🐛 1 | 📅 2018-07-05 - A gentle introduction.

## Human Models

* [SMPL](http://smpl.is.tue.mpg.de/) - SMPL is a realistic 3D model of the human body that is based on skinning and blend shapes and is learned from thousands of 3D body scans.
* [MakeHuman](http://www.makehumancommunity.org) - MakeHuman is an open source (AGPL3) tool designed to simplify the creation of virtual humans using a Graphical User Interface, also commonly referred to as a GUI.

## Datasets

* [Human 3.6M](http://vision.imar.ro/human3.6m/description.php) - Large Scale Datasets and Predictive Methodsfor 3D Human Sensing in Natural Environments
* [SURREAL](https://github.com/gulvarol/surreal) ⭐ 618 | 🐛 17 | 🌐 Lua | 📅 2021-06-04 - Learning from Synthetic Humans, CVPR 2017
* [CMU](http://mocap.cs.cmu.edu/) - Carnegie Mellon University Motion Capture Database
* [Berkley MHAD](http://tele-immersion.citris-uc.org/berkeley_mhad#hard) - \[📷🎥🎤🤾‍♀️⌚️🤹‍♀️]\[👨‍🦰👩]\[👧👵] - The Berkeley Multimodal Human Action Database (MHAD) contains 11 actions performed by 7 male and 5 female subjects in the range 23-30 years of age except for one elderly subject.
* [COCO](http://cocodataset.org) - \[📷]\[👨‍🦰👩]\[👧👵] - COCO is a large-scale object detection, segmentation, and captioning dataset.
* [HDM05](http://resources.mpi-inf.mpg.de/HDM05/) - HDM05 contains more than three hours of systematically recorded and well-documented motion capture data in the C3D as well as in the ASF/AMC data format.
* [KIT Whole-Body Human Motion Database](https://motion-database.humanoids.kit.edu/)
* [CGVU Interaction Database](http://www.ipab.inf.ed.ac.uk/cgvu/InteractionDatabase/interactiondb.html) - This is the project page for creating a database of interactions between a character and an object/objects.

### Description

* Sensors and Data Types - 📷(image), 🎥(video), 🎤(audio), 🤾‍♀️(Motion Capture), ⌚️(IMU or wearables), 🤹‍♀️(Kinect or similar)
* Sex - 👨‍🦰(male), 👩(female)
* Age - 👧(young), 👵(eldery)

## Data Processing

### Recording

* [Unity Humanoid Mocap CSV](https://github.com/mariusrubo/Unity-Humanoid-Mocap-CSV) ⭐ 28 | 🐛 0 | 🌐 C# | 📅 2021-07-30 - Use .csv files to record, play and evaluate motion capture data.
* [KinectMotionCapture](https://github.com/apalkowski/KinectMotionCapture) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2016-07-27 - A simple software for capturing human body movements using the Kinect camera.

### Data Conversion

* [video to bvh](https://github.com/Dene33/video_to_bvh) ⭐ 401 | 🐛 26 | 🌐 Jupyter Notebook | 📅 2019-06-17 - Convert human motion from video to .bvh.
* [MotionCapturePy](https://github.com/taiyoshoe/MotionCapturePy) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2017-09-24 - Converts motion capture data from ASF and AMC files to Cartesian numpy arrays in python. Also plots a moving human frame using matplotlib.

### Misc

* [Motion Annotation Tool](https://github.com/matthiasplappert/motion-annotation-tool) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2021-06-10 - Crowd-sourced Annotation of Human Motion.

## Pose Estimation

### Lectures

* [Human Pose Estimation 101](https://github.com/cbsudux/Human-Pose-Estimation-101) ⭐ 356 | 🐛 3 | 📅 2019-05-14 - Basics of 2D and 3D Human Pose Estimation.
* [Object Keypoint Similarity](http://cocodataset.org/#keypoints-eval) - This page describes the keypoint evaluation metrics used by COCO.

### Papers

* [Papers with Code](https://paperswithcode.com/task/pose-estimation) - A collection of papers addressing several tasks of pose estimation with code available.
* [Human Pose Estimation Papers](https://github.com/Bob130/Human-Pose-Estimation-Papers) ⭐ 133 | 🐛 0 | 📅 2019-11-06 - A collection of papers addressing 2D and 3D human pose estimation.

### Implementations

* [AlphaPose](https://github.com/MVIG-SJTU/AlphaPose) ⭐ 8,592 | 🐛 304 | 🌐 Python | 📅 2024-05-13 - Real-Time and Accurate Multi-Person Pose Estimation\&Tracking System.
* [DensePose](https://github.com/facebookresearch/DensePose) ⚠️ Archived - A real-time approach for mapping all human pixels of 2D RGB images to a 3D surface-based model of the body
* [VideoPose3D](https://github.com/facebookresearch/VideoPose3D) ⚠️ Archived - Efficient 3D human pose estimation in video using 2D keypoint trajectorie.
* [Human Shape and Pose](https://github.com/akanazawa/hmr) ⭐ 1,666 | 🐛 19 | 🌐 Python | 📅 2023-07-10 -  End-to-end Recovery of Human Shape and Pose - CVPR 2018
* [3d-pose-baseline](https://github.com/una-dinosauria/3d-pose-baseline) ⭐ 1,457 | 🐛 32 | 🌐 Python | 📅 2020-09-26 - A simple baseline for 3d human pose estimation in tensorflow. Presented at ICCV 17.
* [3Dpose\_ssl](https://github.com/chanyn/3Dpose_ssl) ⭐ 414 | 🐛 10 | 🌐 C++ | 📅 2020-02-07 - 3D Human Pose Machines with Self-supervised Learning.
* [3d\_pose\_baseline\_pytorch](https://github.com/weigq/3d_pose_baseline_pytorch) ⚠️ Archived - A simple baseline for 3d human pose estimation in PyTorch.
* [3dpose\_gan](https://github.com/DwangoMediaVillage/3dpose_gan) ⭐ 143 | 🐛 12 | 🌐 Python | 📅 2018-07-12 - The authors' implementation of Unsupervised Adversarial Learning of 3D Human Pose from 2D Joint Locations.
* [3D-HourGlass-Network](https://github.com/Naman-ntc/3D-HourGlass-Network) ⭐ 56 | 🐛 0 | 🌐 Python | 📅 2018-10-28 - 3D HourGlass Networks for Human Pose Estimation Through Videos.
* [3d-pose-estimation](https://github.com/latte0/3d-pose-estimation) ⭐ 52 | 🐛 0 | 🌐 Python | 📅 2017-10-31 - VNect: Real-time 3D Human Pose Estimation with a Single RGB Camera.
* [adversarially\_parameterized\_optimization](https://github.com/jackd/adversarially_parameterized_optimization) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2017-11-21 - GAN-based 3D human pose estimation.

## Motion Analysis

### Implementations

* [GaitAnalysisToolKit](https://github.com/csu-hmc/GaitAnalysisToolKit) ⭐ 121 | 🐛 49 | 🌐 Python | 📅 2025-03-15 - Tools for the Cleveland State Human Motion and Control Lab.
* [sensormotion](https://github.com/sho-87/sensormotion) ⭐ 94 | 🐛 0 | 🌐 Python | 📅 2025-05-18 - Python package for analyzing sensor-collected human motion data (e.g. physical activity levels, gait dynamics).
* [Human-detection-system-with-raspberry-Pi](https://github.com/OmalPerera/Human-detection-system-with-raspberry-Pi) ⭐ 59 | 🐛 3 | 🌐 Python | 📅 2018-01-28 - A motion detection system with RaspberryPi, OpenCV, Python.
* [Posture and Fall Detection System Using 3D Motion Sensors](https://github.com/Health-Devices-Research-Group/Posture-and-Fall-Detection-System-Using-3D-Motion-Sensors) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2018-06-05 - This work presents a supervised learning approach for training a posture detection classifier, and implementing a fall detection system using the posture classification results as inputs with a Microsoft Kinect v2 sensor.
* [motion classification](https://github.com/matthiasplappert/motion-classification) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2016-07-11 - The code written during my Bachelor Thesis "Classification of Human Whole-Body Motion using Hidden Markov Models".
* [humanMotionClassification](https://github.com/ltecot/humanMotionClassification) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2017-03-09 - Experiments in classifying human actions using the UCF action databased.
* [human motion classification](https://github.com/kubapok/human-motion-classification) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2018-01-31
* [motion visualization](https://github.com/matthiasplappert/motion-visualization) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2016-02-12 - A simple visualizer for human whole-body motion using three.js
* [HumanMotionVisualiser](https://github.com/BayesTech/HumanMotionVisualiser) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2019-02-17 - This project is for visualising human motion data captured from Kinect V2 for further data analysis.
* [human motion analysis](https://github.com/dfsdfb/human-motion-analysis) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2016-10-23

## Motion Synthesis

### Implementations

* [Skills from Videos](https://github.com/akanazawa/motion_reconstruction) ⭐ 330 | 🐛 12 | 🌐 Python | 📅 2022-09-16 - Motion Reconstruction Code and Data for Skills from Videos (SFV)
* [Character Animation](https://github.com/AliJalalifar/Character_Animation) ⭐ 113 | 🐛 4 | 🌐 Python | 📅 2018-01-31 - A Re-implementation of the paper "A Deep Learning Framework for Character Motion Synthesis and Editing".
* [Auto Conditioned RNN motion](https://github.com/papagina/Auto_Conditioned_RNN_motion) ⭐ 67 | 🐛 9 | 🌐 Python | 📅 2019-03-03 - Implementation of Auto-Conditioned Recurrent Networks for Extended Complex Human Motion Synthesis.
* [eccv18\_mtvae
  ](https://github.com/xcyan/eccv18_mtvae) ⭐ 39 | 🐛 3 | 🌐 Python | 📅 2021-08-01 - Tensorflow Implementation of ECCV'18 paper: Multimodal Human Motion Synthesis.
* [Merel MoCap GAIL](https://github.com/ywchao/merel-mocap-gail) ⭐ 39 | 🐛 0 | 🌐 Shell | 📅 2018-12-13 - An implementation of "Learning human behaviors from motion capture by adversarial imitation".
* [GAN motion Prediction](https://github.com/amoghadishesha/GAN-motion-Prediction) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2019-02-11 - An LSTM based GAN for Human motion synthesis.
* [Human Motion Synthesis](https://github.com/tomatosoldier/Human-Motion-Synthesis) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2017-12-14 - Human motion synthesis using Unity3D.
* [Adversarial Learning for Modeling Human Motion](https://github.com/lucaskingjade/Motion_Synthesis_Adversarial_Learning) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2019-02-20 - This repository contains the open source code which reproduces the results for the paper: Adversarial learning for modeling human motion.
* [MotionSynthesis2Maya](https://github.com/ArashHosseini/MotionSynthesis2Maya) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2018-03-14 - create a Maya Pipeline based on Motion Synthesis.
* [motionSynth](https://github.com/utkarshmall13/motionSynth) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2018-06-02 - Deep Human Motion Synthesis.

## Researchers, Institutes, Projects

### People

* [Daniel Holden](http://theorangeduck.com/) - My name is Daniel Holden. I'm a programmer, writer, and digital artist currently working as a Machine Learning researcher at Ubisoft Montreal. My interests are Computer Graphics, Game Development, Theory of Computation, and Programming Languages.
* [Gustavo Boehs (3DeepLearner)](https://3deeplearner.com/) - Deep Learning for Technical Artists in Animation, VFX, and Games.
* [Arash Hosseini](https://forknwork.wordpress.com/) - R\&D Engineer and ML Enthusiast.
* [Sebastian Starke](http://www.starke-consult.de/portfolio/index.html) - Ph.D. student in Character Animation and Artificial Intelligence at the University of Edinburgh, School of Informatics, Institute of Perception, Action and Behaviour, supervised by Dr. Taku Komura.

### Institutes and Projects

* [Uni Bonn: Physics-based motion analysis and synthesis](http://cg.cs.uni-bonn.de/en/projects/motion-analysis-and-synthesis/) - Physically-based analysis and synthesis of (human) motions have a number of applications. They can help to enhance the efficiency of medical rehabilitation, to improve the understanding of motions in the realm of sports or to generate realistic animations for movies.
* [Max Planck Institute for Intelligent Systems: Perceiving Systems](https://ps.is.tuebingen.mpg.de/code) - We combine research on computer vision, computer graphics, and machine learning to teach computers to see us and by understanding our behavior learn to be more human.
* [FAU: Biomechanical Simulation for the Reconstruction and Synthesis of Human Motion](https://www.mad.tf.fau.de/research/projects/biomechanical-simulation/) - In this project, we investigate musculoskeletal modeling and simulation to analyze and understand human movement and performance. Our objective is to reconstruct human motion from measurement data for example for medical assessments or to predict human responses for virtual product development.
* [USC Institute for Creative Technologies: SmartBody](http://smartbody.ict.usc.edu/) - SmartBody is a character animation platform originally developed at the USC Institute for Creative Technologies. SmartBody provides locomotion, steering, object manipulation, lip syncing, gazing, nonverbal behavior and retargeting in real time.

## Commercial Projects

* [wrnch.ai](https://wrnch.ai/) - wrnch is a computer vision / deep learning software engineering company based in Montréal, Canada, a renowned hub for AI.
* [Qinematic](https://www.qinematic.com/) - Qinematic has developed software for 3D markerless motion capture and human movement analysis since 2012.
* [DeepMotion](https://www.deepmotion.com) - DeepMotion’s solutions bridge physical and digital motion for virtual characters and machines. Using physics simulation, computer vision, and machine learning, DeepMotion reconstructs realistic motion from real-world examples.

## Journals

* [Computers in Biology and Medicine](https://www.journals.elsevier.com/computers-in-biology-and-medicine)
* [Informatics in Medicine Unlocked](https://www.journals.elsevier.com/informatics-in-medicine-unlocked)
* [Image and Vision Computing](https://www.journals.elsevier.com/image-and-vision-computing)
* [Clinical Biomechanics](https://www.journals.elsevier.com/clinical-biomechanics)
* [Signal Processing: Image Communication](https://www.journals.elsevier.com/signal-processing-image-communication)
* [Artificial Intelligence in Medicine](https://www.journals.elsevier.com/artificial-intelligence-in-medicine)

### Journal Ranking

* [Google Scholar](https://scholar.google.com/citations) - Top publications by category and/or language.

## Conferences

* [ICRA](https://dblp.org/db/conf/icra/index) - International Conference on Robotics and Automation
* [MICCAI](https://dblp1.uni-trier.de/db/conf/miccai/) - Medical Image Computing and Computer-Assisted Intervention
* [CVF](https://www.thecvf.com) - The Computer Vision Foundation

### Conference Ranking

* [Conference Rank](http://www.conferenceranks.com/) - Look up the rank of your conference.
* [Google Scholar](https://scholar.google.com/citations) - Top publications by category and/or language.

## Videos

### Two Minute Papers

* [We Can All Become Video Game Characters With This AI](https://www.youtube.com/watch?v=Y73iUAh56iI) - The paper "Vid2Game: Controllable Characters Extracted from Real-World Videos" is available here: [https://arxiv.org/abs/1904.08379]()

### CVPR 2019

* [Oral Session 2-1C: Motion & Biometrics](https://www.youtube.com/watch?v=1DW1FSMs76k)
* [Oral Session 1-1C: Action & Video](https://www.youtube.com/watch?v=JwaBi_2JFeU)
* [Oral Session 1-2B: Synthesis](https://www.youtube.com/watch?v=9GR8V-VR4Qg)
* [Oral Session 3-1A: Applications](https://www.youtube.com/watch?v=ts4ogdJW4_8)
* [Oral Session 3-2B: Face & Body](https://www.youtube.com/watch?v=fNlMGWm7bbk)

## Credits

This list benefits massively from the research work of [**Loreen Pogrzeba**](https://www.researchgate.net/profile/Loreen_Pogrzeba).

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, derikon has waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
