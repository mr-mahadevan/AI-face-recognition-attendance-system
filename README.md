# Face Recognition Attendance System

Welcome to the Face Recognition Attendance System repository! This project uses facial recognition technology to automate and streamline the attendance tracking process.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Running in PyCharm](#running-in-pycharm)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

The Face Recognition Attendance System is designed to automatically record attendance using facial recognition. This system captures images of individuals, processes these images to recognize faces, and logs attendance data efficiently. It is ideal for educational institutions, workplaces, and events where monitoring attendance is crucial.

## Features

- **Automatic Face Detection:** Captures and recognizes faces in real-time.
- **Attendance Logging:** Records attendance data automatically and accurately.
- **User Management:** Add, update, and remove user data for attendance tracking.
- **Reports Generation:** Generate attendance reports for analysis.

## Installation

To set up the Face Recognition Attendance System, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/face-recognition-attendance-system.git
    cd face-recognition-attendance-system
    ```

2. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Set up the database:**
    ```sh
    python setup_database.py
    ```

4. **Run the application:**
    ```sh
    python main.py
    ```

## Usage

1. **Add Users:**
   - Capture images of users and add their details to the system for recognition.
   - Ensure that images are clear and taken from various angles for better accuracy.

2. **Record Attendance:**
   - Launch the application and start the face recognition module.
   - The system will automatically detect faces and log attendance.

3. **Generate Reports:**
   - Access the reports section (```.cv```) file to view and generate attendance reports for specified periods.

## Running in PyCharm

To run this project in PyCharm, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/face-recognition-attendance-system.git
    cd face-recognition-attendance-system
    ```

2. **Open the project in PyCharm:**
   - Launch PyCharm.
   - Click on `File` > `Open` and select the cloned repository folder.

3. **Configure the Python interpreter:**
   - Go to `File` > `Settings` > `Project: face-recognition-attendance-system` > `Python Interpreter`.
   - Click on the gear icon and select `Add`.
   - Choose the Python interpreter you want to use (it should be the one where you installed the dependencies).

4. **Install the required dependencies:**
   - Open the terminal within PyCharm (`View` > `Tool Windows` > `Terminal`).
   - Run the following command:
     ```sh
     pip install -r requirements.txt
     ```

5. **Set up the database:**
   - In the terminal, run:
     ```sh
     python setup_database.py
     ```

6. **Run the application:**
   - In PyCharm, locate `main.py` in the project explorer.
   - Right-click on `main.py` and select `Run 'main'`.

## Contributing

We welcome contributions to improve the Face Recognition Attendance System! If you have suggestions for enhancements or have found a bug, please open an issue or submit a pull request.

1. **Fork the repository.**
2. **Create a new branch:**
    ```sh
    git checkout -b feature-branch
    ```
3. **Make your changes and commit them:**
    ```sh
    git commit -m 'Add new feature'
    ```
4. **Push to the branch:**
    ```sh
    git push origin feature-branch
    ```
5. **Open a pull request.

## License

This project is not licensed.

## Acknowledgements

- [OpenCV](https://opencv.org/) for image processing.
- [dlib](http://dlib.net/) for the machine learning toolkit.
- [Face Recognition](https://github.com/ageitgey/face_recognition) library for the face recognition functionality.

Thank you for using the Face Recognition Attendance System!
