# etee-controllers-with-meta-quest-pro

_HOW TO USE ETEE CONTROLLER WITH META QUEST PRO HEADSET?_

Virtual reality (VR) technology has evolved, with different manufacturers adopting distinct tracking systems for their headsets. For example, Oculus headsets utilize an inside-out tracking system that is compatible with Oculus controllers. This system relies on built-in cameras in the headset to track the user's movements.   
  
In contrast, other VR systems like those from Tg0 and HTC use an external base station approach for tracking. These systems require additional hardware called base stations, which are placed around the room to track the user's movements and the positions of the controllers. While this setup offers greater precision, it is more complex compared to inside-out tracking systems.
Due to these fundamental differences, combining hardware from different systems (e.g., using Etee controllers with a Meta Quest Pro headset) is not natively supported due to compatibility issues. However, specialized software solutions can make this possible.  
  
One such solution is [OpenVR Space Calibrator](https://github.com/pushrax/OpenVR-SpaceCalibrator), which acts as a bridge, enabling the integration of different VR hardware systems. This software allows users to calibrate and align tracking data from disparate systems, making it possible to use, for example, the Etee controller (by Tg0) with an Oculus headset.  
  
The following tutorial requires 2 HTC Vive headsets. This requirement is because the Vive headsets have built-in RF (radio frequency) receivers that can connect to and track the movements of the controllers. In this tutorial, these 2 HTC Vive headsets are used as a substitute for purchasing dongles for tracking purposes. Using dongles eliminates the need for additional headsets. One HTC Vive headset can track two devices, so if you are not going to use Vive headsets, you need to purchase dongles additionally.


**Prerequests**:   
  
Hardware:  
•	Meta Quest Pro Headset  
•	2 Etee Controllers  
•	3 Etee Trackers  
•	2 HTC Vive Headsets  
•	HTC Vive Link Box  
  
Software  
•	Oculus App  
•	Steam Link (for Meta Quest Pro)  
•	Steam and Steam VR  
•	 [OpenVR Space Calibrator](https://github.com/pushrax/OpenVR-SpaceCalibrator) 

💥 _STEP BY STEP PROCESS_  💥
    
1.	Make sure all required software is installed.  
2.	Turn off your HTC Vive Link box to avoid conflicts with your Meta Quest Pro Headset.  
3.	Launch the Steam VR application on your PC.   
4.	Turn on your Meta Quest Pro headset.  
5.	Install Steam Link to your Meta Quest Pro Headset.  
6.	Use Steam Link to establish a connection between your Meta Quest Pro Headset and Steam VR. 
7.	Turn on your HTC Vive Link box.   
8.	Connect each of the two Vive Headsets to your computer BUT unplugged the HDMI cable from both Vive Headsets which will allow you to use the tracking capabilities of the Vive Headsets without their visual displays.   
9.	Connect your two Etee controllers paired with your two etee trackers to the Steam VR.    
10.	Attach the third Etee tracker on the Meta Quest Pro headset. This tracker will be used for hand tracking.   
11.	Launch the OpenVR Space Calibrator app on your PC and calibrate your Meta Quest Pro Headset and the tracker attached to it.   

