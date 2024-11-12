# Multi-Sensor-Fusion-for-Advanced-Perception-and-Estimation-
The objective is to create a system that accurately estimates the distance to vehicles using a combination of image analysis and sensor data fusion. By employing YOLO for vehicle detection in images and integrating RADAR and LiDAR data, the system will project point cloud information onto images, filter relevant points, and estimate distances to detected vehicles. The fusion of RADAR and LiDAR data aims to capitalize on the strengths of each sensor type. The accuracy of distance estimates will be evaluated using metrics like mean absolute error and root mean square error, ensuring the system’s reliability and effectiveness across diverse scenarios


##**Step 1: Object Detection with YOLOv8**##

![Screenshot 2024-07-15 014657](https://github.com/user-attachments/assets/b270d9a8-f3f1-4377-8e71-12a65df098e0)




Step 2: Project Point Cloud

![image](https://github.com/user-attachments/assets/f1911f40-db16-4ceb-a6bc-85941594129e)



![Screenshot 2024-07-15 014707](https://github.com/user-attachments/assets/8951ddf4-ace9-49df-96f1-821deecae933)








Step 3: Filter points in Bounding boxes





![Screenshot 2024-07-15 014718](https://github.com/user-attachments/assets/84e31a04-3d9d-4df0-9cd3-23b64d61c217)







Step 4: Estimate the Distance





![Screenshot 2024-07-15 014731](https://github.com/user-attachments/assets/6a72fe80-ae00-46e9-add5-d7b911d9099c)







Step 5: Weighted Average Sensor Fusion




![Screenshot 2024-07-15 014748](https://github.com/user-attachments/assets/df07ea7d-9acb-4b3e-b98e-ce08ad0465e8)

