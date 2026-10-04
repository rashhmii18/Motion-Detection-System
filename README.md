# Motion Detection Application

A real-time webcam-based motion detection desktop application built using Python and OpenCV. The application monitors a live camera feed, detects movement, and displays an alert message whenever motion is detected.

## Project Overview

The Motion Detection Application is designed to provide real-time movement monitoring through a connected webcam. It continuously analyzes live video frames to identify movement and immediately displays a visual alert, such as **"Motion Detected!"**, directly on the camera feed.

The application focuses on real-time monitoring and privacy. It does not record, save, or store video footage or captured images. All processing is performed locally on the computer.

## Features

* **Live Webcam Feed:** Accesses the connected camera and displays live video.
* **Real-Time Motion Detection:** Continuously analyzes video frames to identify movement.
* **Motion Alerts:** Displays an alert message when movement is detected.
* **Visual Status Indicator:** Shows whether motion is currently detected.
* **Start and Stop Monitoring:** Allows users to control camera monitoring.
* **Privacy-Focused:** Does not record or store video footage or images.
* **Local Processing:** Processes video frames directly on the computer without requiring an internet connection.

## Technologies Used

* Python
* OpenCV
* NumPy
* Tkinter
* Pillow
* PyInstaller

## How It Works

1. The application accesses the connected webcam.
2. The live camera feed is displayed on the application interface.
3. OpenCV continuously processes incoming video frames.
4. A background subtraction technique is used to identify changes between frames and detect movement.
5. When sufficient movement is detected, the application displays a motion alert.
6. Monitoring continues until the user stops the camera.

## Project Structure

```text
Motion_Detection_App/
│
├── main.py
├── camera.py
├── motion_detector.py
├── alert_system.py
├── gui.py
│
├── requirements.txt
├── README.md
│
└── assets/
    └── icons/
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd Motion_Detection_App
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python main.py
```

Make sure your webcam is connected and accessible before launching the application.

## Privacy and Security

Privacy is an important consideration in this application.

* No video recording is performed.
* No captured images or frames are permanently stored.
* No video footage is transmitted to external servers.
* All motion detection processing takes place locally.
* Camera access is released when monitoring stops or the application closes.

## Future Improvements

* Adjustable motion detection sensitivity.
* Improved detection accuracy under different lighting conditions.
* Optional sound notifications.
* Support for multiple camera devices.
* Customizable motion alert settings.
* Improved interface design and user experience.

