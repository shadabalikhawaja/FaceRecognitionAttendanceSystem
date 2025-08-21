# FaceRecognitionAttendanceSystem

## Overview

FaceRecognitionAttendanceSystem is a project designed to automate attendance tracking using facial recognition technology. This system simplifies the attendance process in educational institutions and workplaces by accurately identifying individuals through their facial features.

## Features

- **Real-time Face Recognition**: Utilizes advanced algorithms to detect and recognize faces in real time.
- **Attendance Tracking**: Automatically records attendance based on recognized faces.
- **User-Friendly Interface**: Simple and intuitive interface for easy navigation and operation.
- **Voice Notifications**: Provides audible feedback when attendance is taken.
- **Data Security**: Ensures that personal data is stored securely and complies with privacy regulations.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - OpenCV
  - scikit-learn
  - pandas
  - NumPy

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dg1198/FaceRecognitionAttendanceSystem.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd FaceRecognitionAttendanceSystem
   ```

3. **Install the required libraries**:
   You can install the necessary libraries using pip:
   ```bash
   pip install opencv-python scikit-learn streamlit pandas numpy pywin32
   ```

4. **Extract the necessary files**:
   - Extract `attendance.zip` and `data.zip` into the project directory. This should create the necessary directories for attendance and Haar Cascade files.

5. **Directory Structure**:
   Ensure your directory structure looks like this:
   ```
   /FaceRecognitionAttendanceSystem
   ├── app.py
   ├── add_faces.py
   ├── test.py
   ├── data/
   │   ├── haarcascade_frontalface_default.xml
   │   ├── faces_data.pkl
   │   └── names.pkl
   └── Attendance/
       └── Attendance_*.csv
   ```

## Usage

1. **Add Faces**:
   - Run `add_faces.py` to capture and save your face data. This will prompt you to enter your name and start capturing your facial images.

   ```bash
   python add_faces.py
   ```

2. **Run the Attendance System**:
   - Start the attendance tracking system by running `test.py`. This will begin video capture and recognize faces in real-time.

   ```bash
   python test.py
   ```

3. **Take Attendance**:
   - Press the 'o' key to record attendance when a face is recognized.
   - Press 'q' to quit the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
