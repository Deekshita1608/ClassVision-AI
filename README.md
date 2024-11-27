# Attendance Report Generator from CCTV Footage

This repository provides the source code for a deep learning model that generates attendance reports by analyzing CCTV footage. 

## Features
- Detects faces from CCTV images.
- Matches detected faces with stored identifiers (e.g., roll numbers).
- Generates detailed attendance reports based on the captured footage.

## Privacy Notice
To maintain privacy and comply with data protection policies:
- **Only the code** is provided in the public domain.
- The dataset used for training and testing is not included.
- If you intend to use this code, you must supply your own dataset, ensuring it complies with privacy regulations and ethical standards.

## Requirements
- Python 3.7+
- Deep learning framework (e.g., TensorFlow or PyTorch)
- YOLO v8
- OpenCV for image processing

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/attendance-generator.git
   ```
2. Prepare your dataset and update the configuration file with dataset paths.

## Limitations
- The model requires a pre-labeled dataset for optimal performance.
- It may need fine-tuning for different environments or camera setups.
