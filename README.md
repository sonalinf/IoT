# ECE 558 Project #3 -- Building an IoT Home Automation System
## <b>This assignment is worth 100 points.  Demos on Thu, 21-Nov.  Deliverables due to GitHub and D2L on Sat, 23-Nov by 10:00 PM.  </b>

### <i> We will be using GitHub classroom for this assignment.  You will do your development using the integrated support for Git and GitHub in Android Studio.  You should submit your assignment before the deadline by pushing your final Android Studio projects and other deliverables to your shared GitHub repository for the assignment.</i>

## After completing this assignment students should have:
- Learned to apply Android to control and monitor a device remotely using the internet
- Gained experience with Google Android Things and Firebase
- Gained experience with embedded systems hardware using an off-the-shelf single-board computer and commonly available components


### Introduction

Although ECE 558 is entitled Embedded Systems Programming all we have produced so far has been software running on an Android device. That’s about to change. Project #3 has both a hardware and a software component to it and provides a chance for you to gain experience building an application for the Internet of Things (IoT). For hardware we will be using a Raspberry PI 3 (RPI3), a few resistors, a tri-color (RGB) LED, a PIC microcontroller, an analog temperature sensor and DC hobbyist motor. You will use your Android device to run an app that shares information with the RPI3 across a WiFi or Bluetooth link. Both the control app running on the RPI3 and the user interface app running on the Android device will be programmed in Java using Android Studio and the Android framework.  

The deliverables for this project will be a demo for the T/A or instructor, a design report for the project, and your Android Studio projects.  Since the demos will likely be held at WCC it may be best to use the WiFi hotspot functionality in a phone or tablet to network the remote device to the RPI3

We will be using GitHub classroom for this assignment, only we will enable the Team functionality in GitHub classroom.   After creating/joining a team in GitHub classroom each team member will do their development in a local Git repository on their PC that will be linked to a shared private repository on GitHub.  

## GitHub Deliverables
Push your deliverables to your private GitHub repository for the assignment.  The repository should include:
- Your design report (.pdf preferred).
- A final version of your Android projects. We will use these to grade your effort.  “Neatness counts” for this project - we will grade the quality of your code.  You code should be well structured, indented consistently (Android Studio helps with that) and you should include comments describing what long sections of your code do.    Comments should be descriptive rather than explain the obvious (ex:  //set a to b when the actual code says a = b; does not provide any value-added).

## D2L Deliverables
We would also like you to submit an archive of your GitHub repository to your Project #3 dropbox.  This is easy to do.  Click on the <i>Clone or Download</i> button for your GitHub repository and <i>Download ZIP</i>.  There is a chance that your .zip file will be too large t upload to D2L - if that happens, thanks for trying.

## List of files:
- docs/project3.pdf - The write-up for the project.
- docs/project3_hardware.pdf - Description and details about the hardware used in tis project. Includes information on how to configure your RPI3 for Android Things and WiFi.
- docs/project2_software.pdf - Description and details about the software portion(s) of this project.  Includes some basic information on configuring Firebase
- hardware/datasheets - datasheets for some of the hardware components used in the project.
- hardware/iot_schematic.pdf - schematic for the hardware system
- hardware/iot_wiring_dgm.pdf - wiring diagram for the hardware system
android-things-setup-utility.zip - install utilities.  Also available from the Tools menu on the Android Things Console.
- README.md - this file
