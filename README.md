# AI-Powered-Navigation-System-for-Autonomous-Vehicles
**Real-time object detection and navigation mapping using YOLOv3 and OpenCV**  

## **Overview**  
This project applies **computer vision** to autonomous driving by using **YOLOv3** and **OpenCV** to create a **live navigation map** from a dashcam feed. The system detects **cars and pedestrians**, maps them to their respective lanes, and provides a scaled distance representation for better situational awareness.  

## **Features**  
 **1) Real-time Object Detection:** Identifies cars and pedestrians using YOLOv3.  
 **2) Navigation Map Rendering:** Displays detected vehicles at scale and correct lane positioning.  
 **3) Adaptive Road Conditions Handling:**  
          A) Vehicles on the opposite lane appear on the map but are not considered for navigation.  
          B) If no divider is present, objects are mapped accurately.    

## **Installation**  
1️) **Clone the Repository:**  
```sh
git clone https://github.com/Renuka4443/AI-Powered-Navigation-System-for-Autonomous-Vehicles.git
cd AI-Powered-Navigation-System-for-Autonomous-Vehicles
```
2️) **Install Dependencies:**  
```sh
pip install -r requirements.txt
```
3️) **Download YOLOv3 Weights:**  
🔗 [YOLO Weights](https://pjreddie.com/darknet/yolo/) -> Place in the project folder.  



Move the weights file to the project directory.  

## **Usage**  
Run the script to start the navigation system:  
```sh
python AI_Driven_Dashcam_Navigation.py
```

## **Future Improvements**
 1) Optimize Object Detection – Modify YOLO to detect only relevant objects for autonomous navigation.
 2) Boost Performance – Train a custom lightweight model to achieve higher FPS.
 3) Enhanced Visualization – Improve the mapping system to provide better driving insights. 

## **Demo**  
🚀 A sample demo video will be added soon.  


