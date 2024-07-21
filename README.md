# cat_dog_classifier

This project is here to help me learn about tensor flow in flutter, Gotta tell you even
though this is a shitty app but I love it, because a machine is determining whether the
photo taken is cat's photo or dog's photo.

Disclaimer: donot try with your own photo. 😁


# World's Simplest Cat/Dog Classifier

This project demonstrates how to integrate TensorFlow Lite (TFLite) with a Flutter application. The app uses a pre-trained TFLite model to perform image classification.

## Features

- Load and run TFLite models in a Flutter app.
- Perform image classification using a pre-trained model.
- Display classification results in the app.

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) (version 2.0 or higher)
- [Android Studio](https://developer.android.com/studio) or [Xcode](https://developer.apple.com/xcode/) for iOS development
- A pre-trained TFLite model (you can use any model compatible with TFLite)

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/HimalThapaMagar/Most-Simple-Cat-Dog-Classifier.git
    ```

2. **Install dependencies:**

    ```sh
    flutter pub get
    ```

3. **Add your TFLite model:**

    - Place your `.tflite` model file in the `assets` directory.
    - Update the `pubspec.yaml` file to include the model in the assets section:

    ```yaml
    assets:
      - assets/your_model.tflite
    ```

### Running the App

1. **Connect a device or start an emulator.**

2. **Run the app:**

    ```sh
    flutter run
    ```

## Usage

1. **Select an image** from your device or capture a new one using the camera.
2. **Run the model** to classify the image.
3. **View the results** displayed on the screen.

## Project Structure

- `lib/main.dart`: The main entry point of the application.
- `assets/`: Directory to store the TFLite model and other assets.

## Dependencies

- [tflite](https://pub.dev/packages/tflite): A Flutter plugin for TensorFlow Lite.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Acknowledgements

- [TensorFlow Lite](https://www.tensorflow.org/lite)
- [Flutter](https://flutter.dev/)

