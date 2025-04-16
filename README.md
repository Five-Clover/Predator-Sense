# Predator-Sense
PredatorSense is a monitoring and protection system that harnesses the power of machine learning and deep learning. It employs SSD MobileNet for efficient and accurate object detection in natural habitats
# System Performance
In [1], the AlexNet, VGG-16, and ResNet-50 models achieved a mean Average Precision (mAP) of 84.7% on the Snapshot Serengeti and NACTI datasets. Another study [2] using a self-collected dataset and a CCN model reported a slightly lower mAP of 77%. In comparison, our proposed system, which integrates SSD MobileNet with OpenCV and is trained on the Google Open Images dataset, achieved a competitive mAP of 85.53%.
# Min Average Percision Comparsion
![Screenshot 2025-04-16 184017](https://github.com/user-attachments/assets/698cfb08-c2b9-4655-9619-c939bec975e9) 

The total loss graph illustrates the model’s performance during training, showing a consistent decrease in loss as the number of iterations increases
# Total Loss Graph
![image](https://github.com/user-attachments/assets/b1013bf3-7b12-4b8a-a0cc-b4f802034a19)
# Detection
![image](https://github.com/user-attachments/assets/10565279-b2e0-4348-a8cb-b0861ff279fd) ![image](https://github.com/user-attachments/assets/c2916e34-b6ac-4a7d-a3f2-4bcb766ac7b8)


# Alert System
![image](https://github.com/user-attachments/assets/fee6ac1b-9749-4f5e-bb1e-d12b19615d41)

The system integrates Twilio's API to send SMS notifications. Upon detecting wildlife, an automated process triggers an alert message to a designated phone number, ensuring timely user notification
