# VISION AI - AI Object Detector

**VISION AI** is a web application built with **Next.js** and **TensorFlow.js** AI that leverages open-source AI for object detection. This application allows users to detect objects in real-time using their webcam, with an auto-detect mode that starts recording upon detecting a person. User controlled recordings and screenshots are also achieved through this application. The recorded videos and pictures are saved directly to the user's system.

## Features

- **Real-time Object Detection**: Utilize **TensorFlow.js** for accurate object detection directly in the browser.
- **Auto-Detect Mode**: Automatically detects when a person is in view and starts recording.
- **Recording Functionality**: Uses the **MediaRecorder API** to record video and save it to the user's system.
- **Webcam Access**: Integrates the **react-webcam** package for seamless access to the user's webcam.
- **Alarm Sound**: Plays an alert sound encoded in Base64 when an object is detected.
- **Modern UI**: Employs **Shadcn** for a sleek and responsive user interface.

  ### Usage

1. **Access the Webcam**: Allow the application to access your webcam when prompted.
2. **Start Detection**: Click the "Start Detection" button to begin object detection.
3. **Auto-Detect Mode**: If enabled, the application will automatically start recording when a person is detected.
4. **Recording**: Recorded videos will be saved directly to your system.

### Configuration

- **Base64 Alarm Sound**: The alarm sound used for notifications is encoded in Base64. Modify the `alarmSoundBase64` variable in `utils/audio.ts` if you wish to change the sound.

### Technologies Used

- **Next.js**: A React framework for server-rendered applications.
- **TensorFlow.js**: An open-source library for machine learning in JavaScript.
- **MediaRecorder API**: Provides video recording functionality.
- **react-webcam**: A React component for accessing the webcam.
- **Shadcn**: A UI framework for building modern and responsive interfaces.

## Getting Started

**Run the Development Server**

```bash
npm run dev
# or
yarn dev
```

## Author
[@Tushar Ranjan](https://github.com/TusharRanjan2401)

