
# Vision Track

This is a Flutter-based mobile application that integrates a custom-trained machine learning model for real-time object detection. The app uses on-device inference for fast and efficient object recognition, allowing seamless interaction on mobile devices.

## Features
- Real-time object detection using a custom-trained machine learning model.
- Efficient on-device inference with optimized performance.
- User-friendly interface for easy interaction and visualization of results.
- Fast and accurate detection with improvements in model accuracy via hyperparameter tuning and data augmentation.

## Technologies Used
- **Flutter** for mobile app development.
- **TensorFlow/PyTorch** for training the machine learning model.
- **Dart** programming language for app development.
- **Python** for model training and data preprocessing.
- **OpenCV** for image processing (if applicable).

## Installation

### Prerequisites
- Flutter SDK: [Flutter Installation Guide](https://flutter.dev/docs/get-started/install)
- Python (for model training): [Python Installation Guide](https://www.python.org/downloads/)
- TensorFlow/PyTorch for model training:
  - Install TensorFlow: `pip install tensorflow`
  - Install PyTorch: `pip install torch torchvision`

### Clone the repository
```bash
git clone https://github.com/niranjan216/vision-track.git
cd vision-track
```

### Run the Flutter app
1. Install required Flutter dependencies:
   ```bash
   flutter pub get
   ```
2. Run the app on an Android or iOS device:
   ```bash
   flutter run
   ```

### Training the Model (optional)
If you'd like to retrain the model, follow these steps:

1. Prepare a custom dataset for object detection.
2. Train the model using TensorFlow or PyTorch (refer to `model_training.py`).
3. Once the model is trained, save the weights and integrate the model into the Flutter app under the `assets` folder.

### Model Optimization
- Hyperparameter tuning was performed to improve model accuracy.
- Data augmentation techniques such as rotation, flipping, and scaling were applied to increase the robustness of the model.

## Usage

- Open the app on your mobile device.
- Grant necessary permissions for camera access.
- The app will begin real-time object detection, displaying detected objects and their labels on the screen.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.


