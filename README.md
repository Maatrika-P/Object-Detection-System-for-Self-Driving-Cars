# Self-Driving Car Object Detection and Segmentation 🚗📷

🚗💡 This project focuses on developing advanced object detection and segmentation systems for self-driving cars. Utilizing the BDD100K dataset, we aim to enhance a car's ability to perceive and comprehend its environment, ensuring safer autonomous driving.

## Overview

In recent years, self-driving cars have emerged as a transformative technology with the potential to reshape transportation systems. The foundation of autonomous vehicles is their ability to perceive and understand the environment. Object detection and segmentation are fundamental components of a self-driving car's perception system, as they allow the vehicle to identify and comprehend its surroundings, including other vehicles, pedestrians, traffic signs, lane markings, and obstacles.

## Dataset

📂 Leveraged the BDD100K dataset, which provides a diverse collection of images and annotations, including object detection, instance segmentation, and panoptic segmentation. This dataset serves as the cornerstone for training and testing our self-driving car perception system.

- Dataset source: [BDD100K Dataset](https://bdd-data.berkeley.edu/), https://paperswithcode.com/dataset/idd , https://universe.roboflow.com/object-detection-dp5wa/yolo-v8-indian-roads-dataset , https://data.mendeley.com/datasets/nfc34n8svj/2 , https://universe.roboflow.com/indian-road-dataset/indian-roads-detection , https://www.google.com/search?q=object+detection+driving+dataset+india&sca_esv=3697c3e79dce3da7&sca_upv=1&sxsrf=ADLYWIKnXd6LtvPglW3Iql_Np4QG8qLyeA%3A1718294240043&ei=4BZrZtKpArLvseMP5qu34Ag&ved=0ahUKEwjSmbDu-NiGAxWyd2wGHebVDYwQ4dUDCBA&uact=5&oq=object+detection+driving+dataset+india&gs_lp=Egxnd3Mtd2l6LXNlcnAiJm9iamVjdCBkZXRlY3Rpb24gZHJpdmluZyBkYXRhc2V0IGluZGlhMgUQIRigATIFECEYoAFIkiJQrghY_iBwA3gBkAEAmAG6AaAB3QiqAQMwLje4AQPIAQD4AQGYAgqgAvsIwgIKEAAYsAMY1gQYR8ICBhAAGBYYHsICCxAAGIAEGIYDGIoFwgIIEAAYgAQYogTCAgUQIRifBcICBxAhGKABGAqYAwCIBgGQBgiSBwMzLjegB_Qr&sclient=gws-wiz-serp#ip=1 , 

## Models Experimenting with 

🔍 We will explore various models for object detection and segmentation, with a primary focus on the following:

1. **Faster R-CNN**: A region-based Convolutional Neural Network (CNN) that excels in object detection. It's known for its balance between speed and accuracy, making it suitable for real-time applications.

2. **Mask R-CNN**: An extension of Faster R-CNN, Mask R-CNN also provides instance segmentation. This model is essential for recognizing and differentiating objects within the same class.

3. **U-Net**: its a convolutional neural network architecture designed for semantic segmentation tasks, featuring a U-shaped encoder-decoder structure to capture fine-grained image details.

## Setting Up

🚀 Follow these steps to set up and use the project:

1. **Clone the Repository**: Clone this repository to your local machine:

   ```bash
   gh repo clone Maatrika-P/Object-Detection-System-for-Self-Driving-Cars
   
2. **Install Dependencies**: Navigate to the project directory and install the required Python packages:
   
   ```bash
   pip install -r requirements.txt

3. **Explore Notebooks**: Open the Jupyter Notebooks provided in the repository to train and evaluate the models for self-driving car object detection and segmentation.

4. **Data Preprocessing**: Follow the instructions in the notebooks to load and preprocess the BDD100K dataset.

5. **Train the Model**: Execute the training sections in the notebooks to train the models on the dataset.

6. **Evaluation**: Evaluate the models' performance using the provided metrics in the notebooks.

7. **Testing**: Further, implement testing on real-world driving scenarios if necessary.

8. **Documentation**: Modify the project documentation to suit your specific use case.

## Milestones

🎯 Key milestones for this project:

- Dataset Preparation and Preprocessing
- Model Selection and Architecture Implementation
- Model Training and Performance Evaluation
- Real-world Testing on a Self-Driving Car Platform

## Roadblocks
🚧 Potential roadblocks:

- Limited Hardware Resources
- Fine-tuning Models for Specific Car Platforms
- Ensuring Real-time Performance on Self-Driving Car Hardware
- Handling Varying Lighting and Weather Conditions
- Project Completion and Documentation

## Conclusion
📈 By exploring Faster R-CNN and Mask R-CNN, we aim to develop advanced object detection and segmentation systems for self-driving cars, contributing to safer and more efficient autonomous driving technology.

## Acknowledgments
🙏 We acknowledge the creators of the BDD100K dataset and the machine learning community for their valuable contributions.


## Contribution
Contributions are welcome. Whether you want to suggest improvements, submit bug reports, or add new features, feel free to open an issue or create a pull request.

Join us in revolutionizing self-driving car technology with advanced object detection and segmentation. 🚗🤖🛣️
