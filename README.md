# Workplace-Activity-Recognition-System

## Overview
The system will be capable of recognizing a wide range of activities such as sitting, standing, walking, lifting, typing, and more.
The system will provide real-time activity recognition, allowing for immediate feedback and alerts if any unusual or unsafe activities are detected.
The system will collect and analyze activity data over time, providing insights into employee productivity, and potential areas for improvement.
The system will be designed with privacy in mind, ensuring that sensitive personal information is not collected or stored.

## Objectives


1. **Enhance Workplace Productivity**  
   - Develop a real-time monitoring system to analyze employee activities and identify inefficiencies.  
   - Provide actionable insights to optimize workflow and improve overall productivity.  

2. **Accurate Activity Recognition**  
   - Utilize **YOLO-based deep learning models** (YOLOv8, YOLOv11) to detect and classify workplace activities with high precision.  
   - Ensure robust performance across diverse workplace scenarios.  

3. **Privacy-Compliant Monitoring**  
   - Implement a system that minimizes privacy intrusion while maintaining effective activity tracking.  
   - Adhere to data protection regulations and ethical AI practices.  

4. **Real-Time Processing & Deployment**  
   - Deploy the model using **Streamlit** for an interactive, user-friendly interface.  
   - Ensure low-latency inference for real-time activity recognition.  

5. **Handling Data Challenges**  
   - Address **dataset imbalance** by incorporating diverse activities.  
   - Optimize computational efficiency for training and inference (using **T4 GPU**).  

6. **Scalability & Integration**  
   - Enable integration with **HR and workplace management systems** for automated attendance and performance tracking.  
   - Explore future enhancements like **multi-modal data (audio, wearables)** for richer insights.  

7. **Performance Evaluation**  
   - Use **mAP50-95** as a key metric to assess model accuracy across different IoU thresholds.  
   - Continuously monitor and refine the system post-deployment.

## Feature Scope

The workplace activity recognition system has the potential to evolve and expand in various directions to enhance its capabilities, usability, and impact.

 Enhanced Activity Recognition:

 Integrate additional data sources, such as audio data, environmental sensors, and physiological data from wearables, to provide a more comprehensive understanding of 
 workplace activities.
 Develop models capable of recognizing fine-grained activities, such as "typing on a keyboard," "answering a phone call," or "gesturing during a meeting."
 Implement real-time feedback and alert systems that notify users or administrators of unusual or potentially hazardous     activities.

Integrate with Workplace Management Systems:
Integrate the activity recognition system with HR and payroll systems to automate attendance tracking and performance evaluation.
Use activity recognition to enhance security and access control systems, such as identifying unauthorized access or suspicious behavior.


This project aims to **improve organizational efficiency** while balancing **privacy, accuracy, and real-time usability**.  


