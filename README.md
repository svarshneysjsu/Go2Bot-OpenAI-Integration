# Go2Bot-OpenAI-Integration

## Overview

This repository contains the code and resources for integrating the Unitree Go2 quadruped robot with OpenAI, developed as part of a summer research project in the Department of Applied Data Science. The project aims to enhance human-robot interaction by enabling the Go2 robot, affectionately named "Sparky," to respond to voice commands and perform tasks using advanced AI and robotics techniques.

## Key Features

- **Voice Command Processing:** Leverages OpenAI’s Large Language Models (LLMs) to convert human language into actionable commands that the robot can execute.
- **Gesture Recognition:** Implements computer vision techniques to recognize and respond to human gestures, providing a more intuitive control mechanism.
- **AI-Driven Task Execution:** The robot is capable of understanding complex instructions and performing tasks autonomously.
- **Full-Stack Development:** Combines Python SDKs, Flask for the backend, and JavaScript-based UI for a complete web interface that controls the robot.
- **Real-World Applications:** Includes use cases such as task automation, interactive communication, and advanced robotics research.

## Project Structure

```
├── app/
│   ├── static/
│   ├── templates/
│   ├── routes.py
│   ├── main.py
│   └── ...
├── sdk/
│   ├── unitree_sdk.py
│   └── ...
├── scripts/
│   ├── gesture_recognition.py
│   ├── ai_integration.py
│   └── ...
├── README.md
└── requirements.txt
```

- **`app/`**: Contains the Flask application files, including static assets and templates for the web interface.
- **`sdk/`**: Includes custom Python SDK scripts for interacting with the Go2 robot.
- **`scripts/`**: Contains the Python scripts for gesture recognition, AI integration, and other functionalities.
- **`requirements.txt`**: Lists the dependencies required to run the project.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Go2Bot-OpenAI-Integration.git
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd Go2Bot-OpenAI-Integration
   ```
   
3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Start the Flask server:**
   ```bash
   python app/main.py
   ```

2. **Access the web interface:**
   Open your web browser and navigate to `http://localhost:5000`.

3. **Interact with Sparky:**
   - **Voice Commands:** Type or speak your commands into the chatbot interface.
   - **Gesture Recognition:** Use predefined gestures to control the robot.
   - **AI Interaction:** Watch as the robot executes complex tasks based on your inputs.

## Skills Gained

- **Robotics Programming**
- **Artificial Intelligence (AI) Integration**
- **Python Development**
- **Full-Stack Web Development (Flask, JavaScript)**
- **Human-Robot Interaction (HRI)**

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or new features.

## Acknowledgments

Special thanks to Professor @Simon Shim for his guidance and support throughout this project, and to the DroneBlocks support team for their valuable insights into the SDK capabilities.
