# Hand Gesture Controlled Presentation


## Overview

The **Hand Gesture Controlled Presentation** project allows users to navigate through presentation slides using hand gestures. Leveraging computer vision techniques with OpenCV and cvzone, this application enables intuitive control over presentations without the need for a keyboard or mouse.

## Features

- **Gesture-Based Navigation**: Navigate through slides using hand gestures.
- **Real-Time Hand Detection**: Utilizes OpenCV's capabilities to detect and track hand gestures.
- **Annotations**: Allows users to draw annotations on the presentation slides using hand gestures.
- **User-Friendly Interface**: Displays slides in real-time with gesture recognition feedback.

## Demo
- [Live Demo](https://drive.google.com/file/d/1GDQ3MGd4mZb5pF-uyIVDAlMgvuIYDf5P/view?usp=sharing)


## Screenshots

<img width="1728" alt="CV10" src="https://github.com/user-attachments/assets/f964d8aa-e9b5-42eb-b60d-84c07495b280">


## Prerequisites

Make sure you have the following installed:

- **Python**: Version 3.x
- **OpenCV**: For video capture and image processing.
- **cvzone**: For hand tracking functionalities.
- **NumPy**: For numerical operations.

## Installation

Follow these steps to set up the project:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Pahinithi/Hand-Gesture-Controlled-Presentation-Computer-Vision-OpenCV
   cd Hand-Gesture-Controlled-Presentation
   ```

2. **Install the required packages**:

   ```bash
   pip install opencv-python cvzone numpy
   ```

3. **Add your presentation images**: Place your presentation images in the `Presentation` folder. The images will be displayed in sequence.

## Usage

1. **Run the application**:

   ```bash
   python main.py
   ```

2. **Gesture Controls**:
   - **Swipe Left**: Raise your index finger to move to the previous slide.
   - **Swipe Right**: Raise your thumb to move to the next slide.
   - **Draw Annotations**: Hold up your index and middle fingers to draw annotations on the current slide.
   - **Erase Last Annotation**: Raise all three fingers (thumb, index, and middle) to erase the last annotation.

3. **Exit the Application**: Press `q` to exit the application.

## Code Explanation

Here’s a brief overview of the main components of the code:

- **Camera Setup**: Initializes the camera feed and sets the resolution.
- **Hand Detector**: Uses the `cvzone.HandTrackingModule` to detect hand gestures.
- **Gesture Recognition**: Recognizes specific gestures to control slide navigation and annotations.
- **Image Display**: Displays the current slide and the annotations in real-time.

### Key Variables
- `gestureThreshold`: The height threshold for gesture detection.
- `buttonPressed`: Tracks if a button press (gesture) has occurred.
- `imgNumber`: Tracks the current slide number.
- `annotations`: Stores drawn annotations on the slides.

### Main Loop
The main loop captures frames from the camera, processes hand gestures, and updates the current slide and annotations accordingly.



## Acknowledgements

- **OpenCV**: An open-source computer vision and machine learning software library.
- **cvzone**: A library built on top of OpenCV that simplifies computer vision tasks.
- **NumPy**: A fundamental package for numerical computations in Python.

## License

This project is licensed under the MIT License.

## Contact

For any questions or support, please contact:

- **Name**: Pahirathan Nithilan
- **Email**: [nithilan32@gmail.com](mailto:nithilan32@gmail.com)
- **GitHub**: [Pahinithi](https://github.com/Pahinithi)

