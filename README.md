<h1 align=center><font size = 6>Advanced Drone Detection: YOLOv5 Implementation</font></h1>

<br>  

<img src="https://images.pexels.com/photos/1895900/pexels-photo-1895900.jpeg" height=550 width=1000 alt="https://www.pexels.com/"/>

<small>Image Credit: <a href="https://www.pexels.com/@rquiros/">Rodolfo Quirós</a></small>

<br>

<br>

## Overview
Welcome to the repository for our Final Year Project (FYP) on advanced drone detection using deep learning techniques. Drones, also known as unmanned aerial vehicles (UAVs), are increasingly prevalent in various industries, posing new challenges for security and privacy. In this project, we present our approach to detecting drones in real-time, leveraging the YOLOv5 architecture.

## Steps to run the project
- Clone the Repo
- Install Python on your system
- Install dependencies and requirements "pip install requirements.txt"
- Download or clone the yolov5 model on your system " https://github.com/ultralytics/yolov5 "
- Open app.py file and change the path of files
  model = torch.hub.load('ultralytics/yolov5', 'custom', path=r"C:\Users\Aqib\Documents\GitHub\Advance-Drone-Detection-System-Using-YOLOv5\best.pt", source='github')
  change this code of line with your path, if open in vs code right click on best.pt -> click copy path and paste it.
  gr.Video(r"C:\Users\Aqib\Documents\GitHub\Advance-Drone-Detection-System-Using-YOLOv5\Drone Detection.mp4", width=800, height=600)
  change the path of the sample video, if open in vs code right click on Drone Detection.mp4 -> click copy path and paste it.
- Run the project you will see this out put click on that link 127.0...
  ![image](https://github.com/user-attachments/assets/a0e32c1f-99fa-4dd5-9ff2-56aa248c0013)


### Why YOLOv5?
Due to system constraints, we opted to use the YOLOv5 trained model file (`best.pt`) instead of YOLOv8 for training. YOLOv5 offers comparable performance while requiring less computational power, making it ideal for our setup. Despite this deviation, our project remains focused on delivering accurate and efficient drone detection capabilities.

## About the Dataset
To train our model, we utilized a comprehensive dataset specifically curated for drone detection tasks. This dataset comprises annotated images captured in diverse environmental conditions, ensuring robust detection and classification of drones amidst varying backgrounds and scenarios.

## Methodology
Our methodology revolves around the utilization of the YOLOv5 architecture for drone detection. YOLOv5 is a state-of-the-art object detection model known for its simplicity and efficiency. By fine-tuning the pre-trained YOLOv5 model on our dataset, we aimed to achieve high detection accuracy while optimizing computational resources.

## Experimental Setup
For training and evaluation, we employed the Google Colab platform, harnessing its GPU acceleration capabilities to expedite model training and inference. This cloud-based environment provided the necessary computational resources for our deep learning tasks, overcoming limitations imposed by local hardware.

## Results and Insights
Our project culminated in the development of a robust drone detection model, capable of real-time inference with high accuracy. Through comprehensive testing and evaluation, we obtained insights into the model's performance across various environmental conditions, highlighting its effectiveness in practical scenarios.

## Project Impact and Future Work
As our Final Year Project, this endeavor represents a significant contribution to the field of drone detection and security. By leveraging advanced deep learning techniques, we've addressed critical challenges associated with the proliferation of drones, laying the groundwork for enhanced security measures in the future. Moving forward, we envision further refinement of our model and its integration into real-world applications to mitigate potential risks posed by drones.

<br>

## Contact Us
For inquiries and collaborations, feel free to reach out:

- Aqib Mehmood: aqibkhokhar169@gmail.com

Connect on LinkedIn:
[Aqib Mehmood](https://www.linkedin.com/in/aqib-mehmood-ak169/)
