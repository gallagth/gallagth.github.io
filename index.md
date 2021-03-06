---
layout: page
title: Resume
---

## Skills & Interests

**Backend development**

Design and build scalable RESTful APIs, database creation, integration and management. Management of large scale backend infrastructure.

**Software project management**

Good knowledge of the constraints and requirements needed to ship high quality software projects, including coordinating with various stakeholders. Spent a lot of time onboarding and mentoring junior developers.

**DevOps**

Experienced in setting up automated CI / CD, management of Kubernetes clusters, creation of tools to help developers increase their velocity, etc.

**Android development**

Development on Android devices using the Android SDK. Experience with a wide variety of APIs, especially parts related to Location and Sensors.

**Robotics**

Designed and developed navigation, localization and mapping stacks for mobile robots. Deep knowledge and experience working with ROS.

**Location Based Services**

Experience with designing, implementing and testing indoor and outdoor positioning algorithms using various technologies.

**Android Open Source Project**

Good knowledge of how AOSP is structured and how to build and customize it.

**Embedded development**

Experience with developing for STM32 chips and chips designed for intensive computer vision algorithms.

## Technologies

**Languages**

Java, Kotlin, Python, C++, C, Perl, Objective-C, Bash, Rust, CMake, Makefile, Matlab, HTML, CSS, Javascript

**Tools**

Git, Jenkins, Gitlab, Kubernetes, Google Cloud (App Engine & Compute Engine)

## Experience

### Software Engineer at Stanley Robotics, Paris
**Aug. 2019 - now**

Mainly part of the backend development team, but sometimes “detached” to the SRE team, here are the main things I did at Stanley Robotics:

+ Finalize and deploy in production the split of a monolith application into several microservices, focusing mainly on the biggest service that manages all car movements on the parking, finds storage spaces for incoming cars, optimizes car locations, etc.
+ Extract the main “algorithmic” part of this service into a third party library, to allow sharing with a new standalone application created to be able to simulate and evaluate different algorithms performance.
+ Created from scratch an automated integration test framework in Python to automate the manual work of the QA team. The amount of tests run for each Release Candidate increased 10x and took half the time to execute.
+ Assist the SRE team on various tasks linked to developer pain points.
+ Take ownership of the migration of the infrastructure to kubernetes by running staging / dev environments on it rather than on “bare metal” managed through ansible.


### Backend Developer at Booking.com, Amsterdam
**Nov. 2017 - Aug. 2019**

As a backend developer in the New Product Development - Attractions team, I was mainly responsible for the following items:

+ Developing new features for the intranet and extranet websites used by internal users and attractions partners to build supply, manage content and access various business performance metrics.
+ Developing and shipping a new API for the Android Scanner app used by attractions partners to scan tickets at the entrance of the venues.
+ Shipping a new externally facing API for 3rd party providers to manage attractions supply.
+ Adding new dashboards and alerts to monitor the state of all our APIs.
+ Pushing for CI and provisioning infrastructure to run our unit and integration test suite on each commit.

### Software Engineer at Keecker, Paris
**Sep. 2013 - Oct. 2017**

First employee at Keecker, worked on almost all the software parts of the Keecker prototype and production unit, and the services to support it. Keecker is an autonomous robot with a projector running Android and controlled with a smartphone (see [keecker.com](http://www.keecker.com)). Some examples of what I did at Keecker include:

+ Integration of a 3rd party depth camera in the robot, customisation of the library provided by the vendor.
+ Design and develop a Keecker SDK for 3rd parties app and integrate it in our Android distribution. Wrote the first version of the developer website: [developer.keecker.com](http://www.developer.keecker.com).
+ Implement a fisheye camera dewarp algorithm on GPU and integrate it in Android's libcamera.
+ Develop a WiFi based localizer for the robot.
+ Automate the build and test of the robot's software to enable nightly builds and test reports.
+ Develop a solution for simulating Keecker, based on the Android emulator and Gazebo.
+ Develop an IPC library that uses Android's binder or shared memory to share point clouds or other data between processes without copies.
+ Porting ROS and main ROS tools to Android.
+ Create a bridge to output all robot's data to ROS topics to enable simple visualization and quick prototyping for control, localization or mapping algorithms.
+ Arduino and electronics in the early days to develop the 1st prototype, and to build a simple robotics platform to test new potential sensors for the next iterations.

### Research Assistant at the University of New South Wales, Sydney
**Jan. 2010 - Jul. 2013**

Principal software engineer for the SIMO (Simplified Information for Mobility and Orientation) project

+ Designed, implemented and tested an indoor positioning platform based on sensor fusion running fully on Android and partially on iOS.
+ Fundamental research on indoor positioning techniques (Wi-Fi, dead reckoning and sensor fusion techniques).
+ Designed and ran a survey among Australian Blind and Visually Impaired (BVI) to assess the needs and wants of this population in an info mobility product.
+ Implementation and test on Android/iOS of the user interface designed for the BVI.
+ Tutoring and undergraduate students supervision in various student projects.

### Intern at the University of New South Wales, Sydney
**Feb. 2009 - Sep. 2009**

+ Development of tools and procedures for Android/iOS to evaluate the performance of existing commercial Wi-Fi positioning systems (Ekahau, Skyhook).
+ Research on Wi-Fi/GPS fusion algorithms in urban environments.

## Education

### Ecole Nationale de l'Aviation Civile (ENAC), Toulouse
**Sep. 2006 - Sep. 2009**

+ M.Sc. Eng. in Aeronautical Telecommunications.
+ Coursework in radio navigation, operating systems IT, signal processing and
transmission, networks, radio communications, industrial IT and embedded systems.

### Université Paul Sabatier, Toulouse
**Sep. 2008 - Sep. 2009**

+ M.Sc. Eng. in Signal, Image, Acoustics and Optimisation.
+ Coursework in estimation, optimisation, image processing and classification.

## Projects

+ See Github page for a few software projects: [github.com/gallagth](https://github.com/gallagth)
+ **LYRA-8 (2019)**: assembled a DIY version of the [LYRA-8 synthesizer from SOMA synths](https://somasynths.com/lyra-organismic-synthesizer)
+ **IPIN 2012**: responsible for the successful bid and organisation of the 3rd International Conference on Indoor Positioning and Indoor Navigation, held at UNSW in November 2012.
+ **IGNSS (2011)**: coded a conference guide app for iOS and Android for the delegates of the IGNSS2011 conference.
+ **Multi GNSS software receiver (2008)**: this receiver was developed in C++ by ENAC, I added RAIM functionality and ran a performance assessment.
