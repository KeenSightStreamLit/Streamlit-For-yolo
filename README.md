# KeenSight Object Detection using YOLOv8

This repository contains code for performing object detection using YOLOv8, a state-of-the-art deep learning model. The implementation utilizes Python with various in-built and external packages to facilitate easy development and deployment of the model.

## Setup Instructions

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/KeenSightStreamLit/Streamlit-For-yolo.git
```

2. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

3. Run the main script:

```bash
python main.py
```

## Usage

Upon running the script, you will be presented with a Streamlit-based user interface for configuring and utilizing the object detection functionality.

### Model Configuration

- Select the task type (Detection or Segmentation).
- Adjust the model confidence threshold using the slider.

### Image/Video Configuration

- Choose the source type (Image or Video).
- Upload an image or select a video file.
- Press the "Detect Objects" button to run the detection algorithm.
- View the detected objects overlaid on the image/video.
- Explore detection results in the expandable section.

## Repository Structure

The repository is structured as follows:

- `main.py`: Contains the main code for running the object detection application.
- `settings.py`: Includes configuration settings and constants used throughout the application.
- `helper.py`: Provides helper functions for loading models and processing inputs.
- `logo.png`: Logo image used in the user interface.

## Acknowledgements

This project makes use of several open-source libraries and frameworks, including:

- `pathlib` for handling file paths.
- `PIL` (Python Imaging Library) for image processing.
- `streamlit` for building interactive web applications.

## Support

For any questions or issues regarding this project, feel free to reach out to the maintainer(s) listed in the repository.

Happy detecting! 🚀
