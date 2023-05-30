<div align='center'>
  <h1>Assignment Project with YoloV8</h1>
</div>
<p>Object Detection project repository to show different experiments.</p>

# Experiment Names 
- Assignment Experiment-1
- Assignment Experiment-2
- Assignment Experiment-3

### Assignment Experiment-1
In this project:
- An object detection model trained on Colab and The model YoloV8 used for training.
- Data was separated as train, test and validation (%70 used for training, %20 used for validation and lastly %10 used for test).
- Data Augmentation wasn't added.
- The model trained for 300 epochs.

Parameters that I used:
- lr: 0.01
- optimizer: SGD
- image size: 640x640
- device: GPU
- batch size: 2
- epochs = 300


### Assignment Experiment-2 
In this project:
- An object detection model trained on Colab and The model YoloV8 used for training.
- Data was separated as train, test and validation (%70 used for training, %20 used for validation and lastly %10 used for test).
- Data Augmentation Added. (Rotate 90° (clockwise, counter-clockwise, upside down), %20 Crop, Rotation(between -15° and +15°), Shear(±15° Horizontal, ±15° Vertical)
- The model trained for 100 epochs.

Parameters that I used: 
- lr: 0.01
- optimizer: SGD
- image size: 640x640
- device: GPU
- batch size: 8
- epochs = 100

### Assignment Experiment-3 (Will be Added)
In this project:
- An object detection model trained on Colab and The model YoloV8 used for training.
- Data was separated as train, test and validation (%70 used for training, %20 used for validation and lastly %10 used for test).
- Data Augmentation Added. (Rotate 90° (clockwise, counter-clockwise, upside down), %20 Crop, Rotation(between -15° and +15°), Shear(±15° Horizontal, ±15° Vertical), Blur(Up to 2.5px), Saturation(Between -25% and +25%))
- The model trained for 100 epochs.

Parameters that I used:
- lr: 0.01
- optimizer: SGD
- image size: 1280x1280
- device: GPU
- batch size: 8
- epochs = 100

### Important Notes:
- Trained Model Weights weren't shared due to the memory limitation of GitHub.
