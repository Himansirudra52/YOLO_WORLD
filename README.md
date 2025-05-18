# YOLO-World Object Detection with Custom Dataset and Enhanced Prompt Embedding
This project extends the YOLO-World object detection model to detect 15 custom object classes created by mixing COCO and LVIS datasets. Additionally, it introduces a custom prompt embedding technique to improve detection accuracy in open-vocabulary settings.
Features
1. Custom YOLO-World model trained on 15 mixed-class dataset (COCO + LVIS)

2. Extra prompt embedding module added for performance boost

3. Achieves improved zero-shot/generalized object detection accuracy

4. Trained and tested in Google Colab

5. Model evaluation and visualizations included

# Dataset
Custom dataset: 15 classes

Combination of COCO and LVIS annotations

Converted to YOLO format for training

# Architecture Enhancements
Modified prompt encoder

Custom vocabulary alignment layer

Visualization support added using OpenCV and Matplotlib

# Training & Evaluation

Platform: Google Colab

Optimizer: AdamW

Metrics: mAP, zero-shot accuracy

Hardware: T4 GPU

# How To Run

!git clone https://github.com/your-username/yolo-world-custom

Open yoloworld_custom.ipynb in Google Colab

# Future Work

Expand to 50 classes

Deploy model on web using Flask

Model quantization for edge devices

