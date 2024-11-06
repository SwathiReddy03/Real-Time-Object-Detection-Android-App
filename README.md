# Real-Time Object Detection with TensorFlow Lite

This project implements a real-time object detection system using TensorFlow Lite and an Android application. The app uses the device's camera to detect objects in real-time and draw bounding boxes with labels and confidence scores.

## Features

- Real-time object detection using a pre-trained SSD MobileNet model.
- Displays detected objects' bounding boxes on the live camera feed.
- Shows labels and confidence scores for detected objects.
- Optimized for mobile devices with TensorFlow Lite for efficient performance.

## Requirements

- Android Studio
- Android device or emulator running Android 5.0 (Lollipop) or higher
- TensorFlow Lite model (`SsdMobilenetV11Metadata1`)

## Setup

1. Clone the repository or download the project files.
2. Open the project in Android Studio.
3. Make sure to set up your Android device or emulator with the necessary permissions:
    - CAMERA permission in the `AndroidManifest.xml`.
4. Build and run the app on a connected Android device.

## How It Works

- The app loads the TensorFlow Lite model and class labels from `labels.txt`.
- The camera feed is captured using `TextureView`, and each frame is processed.
- Detected objects are drawn with bounding boxes, class labels, and confidence scores on the live video stream.

### Camera Permissions

Ensure the app has `CAMERA` permissions to access the device camera for capturing real-time images.

### TensorFlow Lite Model

The app uses the pre-trained SSD MobileNet V1 model converted to TensorFlow Lite format for efficient object detection. The model identifies a variety of objects such as vehicles, animals, furniture, and more.

## Results

Here are some results of the object detection:

### Images


<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/SwathiReddy03/Real-Time-Object-Detection-Android-App/blob/main/results/img1.jpg" width="300"/>
  <img src="https://github.com/SwathiReddy03/Real-Time-Object-Detection-Android-App/blob/main/results/img2.jpg" width="300"/>
  <img src="https://github.com/SwathiReddy03/Real-Time-Object-Detection-Android-App/blob/main/results/img3.jpg" width="300"/>
</div>

   



### Videos

A short clip showcasing real-time object detection.

- [Download Video 1](https://github.com/SwathiReddy03/Real-Time-Object-Detection-Android-App/raw/main/results/result_video_1.mp4)
- [Download Video 2](https://github.com/SwathiReddy03/Real-Time-Object-Detection-Android-App/raw/main/results/result_video_2.mp4)


