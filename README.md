# Drowsiness Detection for Students while Studying

This project is a drowsiness detection system built using OpenCV library and implemented in Python. The purpose of this system is to monitor students while they are studying and alert them if they exhibit signs of drowsiness, thus promoting their alertness and concentration.

## Prerequisites

To run this project, you will need the following:

1. Python: Install Python on your machine. You can download the latest version of Python from the official Python website.

2. OpenCV: Install OpenCV library for Python. You can use pip, the package installer for Python, to install OpenCV. Run the following command in your terminal:

   ```
   pip install opencv-python
   ```

3. dlib: Install the dlib library for Python, which will be used for face and landmark detection. You can use pip to install dlib. Run the following command in your terminal:

   ```
   pip install dlib
   ```

4. Shape Predictor Model: Download the shape predictor model file (shape_predictor_68_face_landmarks.dat) from the dlib website. This model is used for facial landmark detection.

## Setup

Follow these steps to set up the project:

1. Clone the project repository to your local machine.

2. Place the shape predictor model file (shape_predictor_68_face_landmarks.dat) in the project directory.

## Usage

To use the drowsiness detection system, follow these steps:

1. Run the Python script `drowsiness_detection.py` using the following command in your terminal:

   ```
   python drowsiness_detection.py
   ```

2. The webcam will open, and the script will start detecting faces and facial landmarks.

3. The system will analyze the eye aspect ratio (EAR) of each eye to determine if the person's eyes are closed or open.

4. If the eyes are closed for a specified duration, the system will assume the person is drowsy and play an alarm sound to alert them.

5. The system will continue to monitor the person's eyes and provide real-time feedback.

6. Press 'q' to quit the drowsiness detection system.

## Customization

You can customize the drowsiness detection system to suit your specific requirements. Here are a few areas you might consider:

1. Threshold values: Adjust the eye aspect ratio (EAR) threshold values in the script to define when the eyes are considered closed or open based on your observations and preferences.

2. Alarm sound: Modify the alarm sound played when drowsiness is detected to a sound that is more effective for alerting the person.

3. Additional features: Enhance the system by adding more features, such as head pose estimation, head movement detection, or integrating it with other monitoring systems.

## Troubleshooting

If you encounter any issues while setting up or running the drowsiness detection system, consider the following troubleshooting steps:

1. Verify library installations: Make sure you have installed OpenCV and dlib libraries correctly by following the setup instructions.

2. Check webcam connection: Ensure that your webcam is connected and functioning properly.

3. Review script dependencies: Double-check that you have placed the shape predictor model file in the correct project directory.

4. Debugging: Utilize the debugging capabilities of your Python IDE or print statements in the code to identify and resolve any runtime errors or exceptions.

## License

This project is licensed. Feel free to modify, distribute, and use it in your own projects.

## Acknowledgments

We would like to acknowledge the developers of OpenCV and dlib libraries for providing the necessary tools and resources to build this drowsiness detection system.

If you have any questions or suggestions, please feel free to contact us in mail.
