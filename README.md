# Sign Language Recognition

A real-time web-based application focused on recognizing hand gestures through computer vision and machine learning. The system combines **React.js** with **MediaPipe** and a trained recognition model to process webcam input and identify predefined gestures.

## Overview

The application demonstrates the integration of machine learning and modern web technologies for real-time gesture recognition. Hand landmarks are detected through MediaPipe and processed by a trained model to determine the corresponding gesture.

The modular architecture allows the system to be extended with additional gestures, improved models, and enhanced communication features.

## Key Capabilities

* Real-time webcam-based gesture detection
* Hand landmark tracking using MediaPipe
* Machine learning-based gesture classification
* Interactive React.js interface
* Redux-based state management
* Firebase integration
* Custom-trained recognition model
* Extensible application architecture

## Technology Stack

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| React.js         | Frontend development    |
| JavaScript       | Application logic       |
| MediaPipe        | Hand landmark detection |
| Machine Learning | Gesture classification  |
| Redux            | State management        |
| Firebase         | Application services    |
| HTML & CSS       | Interface and styling   |

## System Workflow

```text
Webcam Input
     ↓
Hand Detection
     ↓
Landmark Extraction
     ↓
Machine Learning Model
     ↓
Gesture Classification
     ↓
Recognized Output
```

## Project Structure

```text
Sign-Language-Recognition/
│
├── public/
│   └── trained_model/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   └── ...
│
├── Code For Training the Model/
├── package.json
├── package-lock.json
├── .env.example
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites

* Node.js
* npm
* Modern web browser
* Webcam

### Installation

```bash
git clone https://github.com/YOUR-USERNAME/Sign-Language-Recognition.git
cd Sign-Language-Recognition
npm install
```

### Configuration

Create a `.env` file using `.env.example` as a reference and configure the required application credentials.

Sensitive configuration files should not be committed to the repository.

### Run Locally

```bash
npm start
```

The application can then be accessed through the local development server.

## Model

The recognition system uses a custom-trained machine learning model for gesture classification. The training resources are included in the repository to support further experimentation and model improvement.

## Future Scope

The system can be extended to support a larger gesture vocabulary, sentence-level interpretation, improved recognition accuracy, multilingual support, and voice-based output.

## License

This project is intended for educational and research purposes.
