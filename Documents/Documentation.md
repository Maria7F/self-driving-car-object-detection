# Self Driving Car Object Detection

## Abstract
We all know self-driving cars is one of the hottest areas of research and business for the tech giants. What seemed like a science-fiction, a few years ago, now seems more like something which is soon to become a part and parcel of life. The reason, I am saying “soon to be” is because of the fact that even though companies like Tesla, Nissan, Cadillac do have self-driving car assistance software, but, they still require a human to keep an eye on the road and take control when needed. However, it is fascinating to see how far we have come in terms of innovation and how fast technology is advancing. So much so, that now, with the help of basic deep learning, neural network magic...

## Design 
This project is one of the T5-Batch 3 Data Science sadaya BootCamp requirements ,The dataset was sourced from Roboflow , The Roboflow Model Library contains pre-configured model architectures for easily training computer vision models Deep Learning has revolutionized Computer Vision, and it is the core technology behind capabilities of a self- driving car. Convolutional Neural Networks (CNNs) are at the heart of this deep learning revolution for improving the task of object detection. A number of successful object detection systems have been proposed in recent years that are based on CNNs. In this paper, an empirical evaluation of three recent meta-architectures: SSD (Single Shot multi- box Detector), R-CNN (Region-based CNN) and R-FCN (Region-based Fully Convolutional Networks) was conducted to measure how fast and accurate they are in identifying objects on the road, such as vehicles, pedestrians, traffic lights, etc. under four different driving conditions: day, night, rainy and snowy for four different image widths: 150, 300, 450 and 600. The results show that region- based algorithms have higher accuracy with lower inference times for all driving conditions and image sizes. The second principle contribution of this paper is to show that Transfer Learning can be an effective paradigm in improving the performance of these pre-trained networks. With Transfer Learning, we were able to improve the accuracy for rainy and night conditions and achieve less than 2 seconds per image inference time for all conditions, which outperformed the pre-trained networks.

## Data
The dataset contains 97,942 labels across 11 classes and 15,000 images. There are 1,720 null examples (images with no labels) and eighth columns (Filename, width, height, class, xmin, ymin, xmax, ymax)
All images are 1920x1200 (download size ~3.1 GB). We have also provided a version down sampled to 512x512 (download size ~580 MB) that is suitable for most common machine learning models

## Algorithm
* Data manipulation and cleaning
    * Applied feature Selection by dropping unnecessary columns.