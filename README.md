# COGS Robot AR
Continued development of the COGS robot/IoT app

Goals for development:
* Improved UI
* Manual control of the robot
* Hololens/controller support because why not lmao
* Performance/Technical improvements for robot code

# Installation
Tested with Unity 2018.2.16 installed with Vuforia 7.5

Installed with both Vuforia and Android Build Components

# Releases
Each release includes both an APK to test out the project and a zip file of starter code to work through the workshop

# Building for Android
* Ensure that Unity is installed with Android Build Components
* In the player settings, uncheck AndroidTV support
* Follow the instructions for Building here: https://unity3d.com/learn/tutorials/topics/mobile-touch/building-your-unity-game-android-device-testing?playlist=17138
  * I used Unity's internal build system instead of gradle, it shouldn't really matter though.

# Building the Robot
* I used a Particle photon to control the robot
* To build the robot, mostly follow this guide https://docs.google.com/document/d/1ZbvWbrLAp_iHPgDpoouUpZCBtnHmlw-4PE3RyQugldU/edit
  * I didn't use the photoresistors, but otherwise every thing is the same. Motors and ultrasonic sensors are both plugged into the digital ports on the photon. See code definitions to get specific ports used.
* Use 
`git clone -recursive https://github.com/ubcemergingmedialab/VuforiaIoT.git`
to get the robot code
