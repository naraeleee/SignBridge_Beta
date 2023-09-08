# Sign Bridge README

Sign Bridge is a Python application designed to help users learn and practice American Sign Language (ASL) alphabets through various interactive modules. This README file provides an overview of the application's functionality, its structure, and how to set it up and use it.

## Table of Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Installation](#installation)
4. [Usage](#usage)
   - [Home Screen](#home-screen)
   - [Multiple Choice](#multiple-choice)
   - [Learn Alphabets](#learn-alphabets)
   - [Webcam Quiz](#webcam-quiz)
   - [Sign to Text](#sign-to-text)
   - [Text to Sign](#text-to-sign)
5. [Application Structure](#application-structure)
6. [Modules](#modules)
   - [Home Screen](#home-screen-1)
   - [Multiple Choice](#multiple-choice-1)
   - [Learn Alphabets](#learn-alphabets-1)
   - [Webcam Quiz](#webcam-quiz-1)
   - [Sign to Text](#sign-to-text-1)
   - [Text to Sign](#text-to-sign-1)

## Introduction

Sign Bridge is an interactive Python application that focuses on helping users learn and practice American Sign Language (ASL) alphabets. It offers various modules that cater to different learning and practicing needs. Here's a brief overview of each module:

### Home Screen

The application starts with a home screen that provides options to access different modules.

### Multiple Choice

A quiz module where users are presented with images of ASL signs for alphabets and must choose the correct alphabet from multiple choices.

### Learn Alphabets

A module that allows users to learn ASL alphabets through images and descriptions.

### Webcam Quiz

An interactive quiz that uses a webcam to recognize ASL signs made by the user and provides instant feedback on correctness.

### Sign to Text

A feature that translates ASL signs captured through a webcam into text.

### Text to Sign

A feature that translates text input into ASL signs, which can be displayed on the screen.

## Dependencies

The Sign Bridge application relies on several Python libraries and frameworks. Make sure you have the following dependencies installed before running the application:

- PIL (Python Imaging Library): For working with images.
- os: For file and directory operations.
- random: For generating random choices in quizzes.
- tkinter: For creating the graphical user interface.
- pickle: For serialization and deserialization of Python objects.
- cv2 (OpenCV): For computer vision tasks and webcam access.
- mediapipe: For hand tracking and recognition.
- scikit-learn: For machine learning tasks like training a random forest classifier.
- numpy: For numerical operations.

You can usually install these libraries using pip, for example:

```shell
pip install pillow
pip install opencv-python
pip install mediapipe
pip install scikit-learn
pip install numpy
```

** Installation **

1. Clone the Sign Bridge repository to your local machine:

```shell
git clone https://github.com/yourusername/sign-bridge.git

cd sign-bridge

python main.py
```




## Usage

The Sign Bridge application provides several modules to help you learn and practice ASL alphabets. Here's a brief overview of how to use each module:

### Home Screen

The home screen provides options to access different modules: "Learn," "Multiple Choice," "Webcam Quiz," "Sign to Text," and "Text to Sign."

- Click on the buttons to navigate to the respective modules.

### Multiple Choice

In the Multiple Choice module, you'll be presented with an image of an ASL sign for an alphabet.

- Choose the correct alphabet from the multiple-choice options.
- Click "Next Question" to move to the next question.
- Your score and correctness will be displayed after each question.

### Learn Alphabets

In the Learn Alphabets module, you can explore ASL alphabets through images and descriptions.

- Use the "Next" button to view different alphabets.

### Webcam Quiz

The Webcam Quiz module uses your webcam to recognize ASL signs you make.

- Follow the on-screen instructions to start the quiz.
- Sign the displayed alphabet, and the application will provide instant feedback.
- Use 's' to skip a question and 'q' to end the quiz.
- After completing the quiz, you will receive your correctness score.

### Sign to Text

In the Sign to Text module, the application translates ASL signs captured through your webcam into text.

- Display an ASL sign, and the application will recognize and display the corresponding text.

### Text to Sign

The Text to Sign module allows you to input text, and the application will display the ASL signs for that text.

- Enter the text you want to see in ASL signs, and click "Translate."

