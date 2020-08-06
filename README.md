# TheThirdEye

Nav-Ujjwal-e-innovation-Hackathon Submission

## Contents

1. [Short description](#short-description)
1. [Description and Demo video](#description-and-demo-video)
1. [The Architecture](#the-architecture)
1. [Built with](#built-with)
1. [Authors](#authors)

## Short description

### What's the problem?


Eye sight plays a major role in collecting most of the information from the real world and that information will be processed by brain, visually impaired people suffer inconveniences in their daily and social life. Blindness or visual impairment is a condition that affects many people around the world. This condition leads to the loss of the valuable sense of vision. Worldwide there are millions of people who are visually impaired, where many of them are blind. The need for assistive devices was and will be continuous. There is a wide range of navigation systems and tools existing for visually impaired individuals. The blind person truly requires an identifying objects. 
In the existing system, there is only technology to detect the obstacle and to notify the blind by having some warning sound. 
The main objective of our project (THETHIRDEYE) is to provide a voice based assistance to blind people. Here we have developed an intelligent system that helps blind person to travel independently and works efficiently. Current navigation device for the visually impair focus on travelling from one location to another. Our project focuses on designing a device for blind people that help them to travel independently and also it must be comfortable to use. The proposed device is used for guiding individuals who are blind or partially sighted. The device is used to help blind people to move with the same ease and confidence as a sighted people.

### proposed system:
The proposed system consists of three main units:

 1. Virtual camera and Ultrasonic Sensor unit. 
 2. GPS Module unit. 
 3. Google Text to Speech unit.
 
“THETHIRDEYE” system is easy to understand and maintain. This system uses Raspberry pi, it is a small processing device which works as computer at relatively low cost. Blind and visually impaired people find difficulties in detecting obstacles during walking in the street. The system is intended to provide artificial vision and object detection, real time assistance via GPS by making use of Raspberry Pi. The system consists of ultrasonic sensors, GPS module, and the feedback is received through audio. Voice output works through TTS (text to speech). Whenever the obstacle is detected on the way through ultrasonic sensor placed on the stick, Camera gets triggered to capture the object which is on the way. The captured image is sent to IBM cloud to identify the type of the object and then it is intimated as voice command through speaker or via earphones connected with Raspberry pi. So that blind can able to identify the object in-front of them, this technology makes walking stick smarter. And also it contains walking stick indicator in case if they miss the stick through sound beeping, Navigating their way to home by redefining the users' home through voice command using the Google map navigator and to know the places near to their location like shops.
The aim of the overall system is to provide a low cost, efficient navigation and obstacle detection aid for blind which gives a sense of artificial vision by providing information about the environmental scenario of static and dynamic object around them, so that they can walk independently.
## Description and Demo video
Click The Icon Below <br>
[![Watch the video](https://youtu.be/MapIl5MninA)

## The Architecture

 See  [Solution Design Architecture and Data Model.pptx] (Solution Design Architecture and Data Model.pptx)
       
       1. When the person is walking ,the Logitech webcam connected to Raspberry Pi clicks pictures and sent to the IBM cloud.
       2.The visual recognition service is used to recognise the obstacle and the output is given in the form of text.
       3.The output is also stored in cloud object storage of IBM cloud.
       4.The google text to speech library is used to convert text into speech
       5.The output is given to the user through earphones connected to Raspberry Pi.
       6.The stick has a wifi module that keeps it connected to internet which allows it to send pictures to cloud.
 
 ### code
 
click the link below for IBM code
          https://github.com/Nav-Ujjwal-e-innovation-Hackathon/TheThirdEye/blob/master/code.py
click the link below for firesensor code 
          https://github.com/Nav-Ujjwal-e-innovation-Hackathon/TheThirdEye/blob/master/firesensor%20code
       
 ## Built with
 
   1. IBM Visual Recognition service: It is used to identif the imageof an object
   2.ARDUINO IDE: The Arduino software allows to write programs and upload into the board
   3. VNC VIEWER: It is used to control and remotely access our raspberrypie
   4. ANDROID STUDIO: It is used for development od android application that can be used by the guardian to track the person
   
## Authors

* Vaishnavi Rudraraju
* Nandu Tejaswini
   




