# YOLOv3: Object Detection in Real-Time Video Stream

This project demonstrates the use of YOLOv3 (You Only Look Once version 3) for real-time object detection in video streams. YOLOv3 is a state-of-the-art deep learning model known for its balance between speed and accuracy in detecting objects within images and videos.

## Key Features

- **Real-Time Detection**: Processes video frames quickly enough for real-time applications.
- **Multi-Class Detection**: Detects multiple objects from a predefined set of classes (e.g., people, vehicles, animals).
- **High Accuracy**: Provides accurate object localization and classification in each frame.

## How It Works

1. **Load the Model**: The YOLOv3 model is loaded using pre-trained weights and configuration files. These files define the architecture and parameters of the model.

2. **Prepare Video Stream**: Captures frames from a video source (e.g., webcam, video file) for processing.

3. **Preprocess the Frame**: Each frame is resized and normalized to fit the input requirements of the YOLOv3 model.

4. **Run Detection**: The preprocessed frame is passed through the YOLOv3 network to obtain bounding boxes, class labels, and confidence scores for detected objects.

5. **Postprocess and Display**: Detected objects are highlighted with bounding boxes and labels, and the processed frame is displayed in a window to show real-time results.

6. **Handle Output**: Continuously processes video frames and updates the display until the user stops the stream.

## Requirements

- **Python**: Programming language used for the project.
- **OpenCV**: Library for video capture, image processing, and display.
- **YOLOv3 Model Files**:
  - [YOLOv3 Weights](https://pjreddie.com/media/files/yolov3.weights)
  - [YOLOv3 Config](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
  - [COCO Names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)

This project demonstrates how YOLOv3 can be integrated into real-time systems for various applications, such as surveillance, autonomous vehicles, and interactive video analysis.

