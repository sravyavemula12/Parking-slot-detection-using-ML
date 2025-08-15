Parking Slot Detection using Deep Learning
Features

VGG16-based Transfer Learning for classification

Grid-based detection (20×16 slots = 320)

Two-class output: Empty / Occupied

Confidence thresholding for better accuracy

Visual output with bounding boxes

Tech Stack

Python 3.x

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

How It Works

Data Preparation: Dataset split into empty and occupied for train/test.

Model Training: VGG16 backbone, frozen layers, data augmentation.

Slot Detection: Image divided into grid → slots classified → results drawn.

Usage

Install dependencies:

pip install tensorflow opencv-python matplotlib numpy


Place dataset (train_data.zip) in project folder.

Run script:

python parking_detection.py

Output

Terminal shows total, occupied, and empty slot counts.

Displays processed image with colored slot boxes.

Future Improvements

YOLO-based slot detection

Real-time video analysis

Higher-resolution training for accuracy
