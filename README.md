# Task-4-Hand-Gesture

# Hand Gesture Recognition

## Overview

This project implements a hand gesture recognition system that classifies different hand gestures from images using a convolutional neural network (CNN) based on transfer learning with MobileNetV2. The model is trained on the [LeapGestRecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog) dataset.

The system can be extended to real-time recognition via webcam, enabling intuitive human-computer interaction and gesture-based control.

---

## Features

- Automatic download of LeapGestRecog dataset using `kagglehub`
- Data augmentation for improved model generalization
- Transfer learning with MobileNetV2 pretrained on ImageNet
- Model training with fine-tuning capabilities
- Optional real-time webcam gesture classification demo

---

## Requirements

- Python 3.x
- TensorFlow 2.x
- OpenCV
- `kagglehub`
- Kaggle API token configured (if using Kaggle API alternatively)

---

## Setup & Usage

1. **Install dependencies** (can be done inside the script or notebook):

    ```bash
    pip install tensorflow opencv-python kagglehub
    ```

2. **Download the dataset** using the included code (uses `kagglehub`):

    The dataset will be downloaded and extracted automatically.

3. **Train the model**:

    Run the training script/notebook to load data, train with transfer learning, and fine-tune the model.

4. **Save the trained model**:

    The trained model will be saved as `hand_gesture_recognition_model.h5`.

5. **Optional real-time demo**:

    Uncomment and run the webcam demo block in the code to test live hand gesture recognition with your webcam.

---

## Dataset

- **LeapGestRecog Dataset**: A dataset of hand gestures for recognition tasks.
- [Dataset link on Kaggle](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)

---

## How to Run

- Run the main script or notebook in Google Colab or your local environment.
- For webcam demo, ensure your camera is accessible and run the demo section separately.
- Press `q` to quit the webcam window.

---

## Notes

- Make sure your Kaggle API token is configured if you are using Kaggle CLI or `kagglehub` for dataset downloading.
- Transfer learning speeds up training and improves accuracy.
- Data augmentation helps the model generalize better to variations.

---

## Future Work

- Extend recognition to video streams using temporal models (LSTM, 3D CNN).
- Integrate gesture recognition into robotics or IoT devices.
- Deploy the model on mobile or embedded platforms.

---

## License

The project uses the publicly available LeapGestRecog dataset. Please refer to the dataset's page for license details.

---

## Contact

For questions or suggestions, contact:

**Your Name**  
Email: your.email@example.com  
GitHub: [https://github.com/yourusername](https://github.com/yourusername)
