# Go2Bot-OpenAI-Integration

This project integrates the Unitree Go2 robot with an OpenAI-powered dashboard, allowing for seamless control and interaction through a Flask-based web application.

This repository contains the code and resources for integrating the Unitree Go2 quadruped robot with OpenAI, developed as part of a summer research project in the Department of Applied Data Science. The project aims to enhance human-robot interaction by enabling the Go2 robot, affectionately named "Sparky," to respond to voice commands and perform tasks using advanced AI and robotics techniques.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

The **Go2Bot-OpenAI-Integration** project provides an interactive dashboard to control and monitor the Unitree Go2 robot. The dashboard leverages the power of OpenAI models to enhance robot interaction, providing capabilities such as voice commands, real-time monitoring, and more.

## Features

- **Real-time Control**: Control the Unitree Go2 robot through a web interface.
- **Voice Command Support:** Leverages OpenAI’s Large Language Models (LLMs) to convert human language into actionable commands that the robot can execute.
- **AI-Driven Task Execution:** The robot is capable of understanding complex instructions and performing tasks autonomously.
- **Modular Design**: Easily extendable architecture with support for additional features and sensors.
- **Full-Stack Development:** Combines Python SDKs, Flask for the backend, and JavaScript-based UI for a complete web interface that controls the robot.

## Installation

### Prerequisites

- Python 3.8+
- Flask
- pip (Python package installer)

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/Go2Bot-OpenAI-Integration.git
    cd Go2Bot-OpenAI-Integration
    ```

2. Install the required Python packages:

    ```bash
    pip install -r go2_dashboard/requirements.txt
    ```

3. Install additional dependencies (if any):

    ```bash
    python get-pip.py
    ```

## Usage

### Running the Application

1. Navigate to the project directory:

    ```bash
    cd go2_dashboard
    ```

2. Start the Flask application:

    ```bash
    python app.py
    ```

3. Access the dashboard by navigating to `http://localhost:5000` in your web browser.

### Available Endpoints

- `/`: Main dashboard page.
- `/control`: Interface for controlling the robot.
- `/monitor`: Real-time data and status monitoring.

## Directory Structure

The project is structured as follows:

```
Go2Bot-OpenAI-Integration/
│
├── go2_dashboard/
│   ├── app.py                 # Main Flask application
│   ├── app_dashboard.py       # Dashboard-specific routes and views
│   ├── requirements.txt       # Python dependencies
│   ├── static/                # Static files (CSS, JS, images)
│   ├── templates/             # HTML templates for rendering views
│   ├── unitree_sdk2py/        # SDK for Unitree Go2 robot integration
│   ├── scripts/               # Additional scripts and utilities
│   ├── images/                # Image assets used in the project
│   ├── sounds/                # Audio files used in the project
│   └── README.md              # Sub-directory specific README
│
├── get-pip.py                 # Script to install pip
├── .gitignore                 # Git ignore rules
├── .gitmodules                # Git submodules configuration
└── README.md                  # Project README (You are here)
```

## Configuration

You may need to configure certain environment variables or settings before running the application. Check the `app.py` and `app_dashboard.py` files for specific configuration options.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your proposed changes.

## Acknowledgments

- [Unitree Robotics](https://www.unitree.com/) for their SDK and documentation.
- [OpenAI](https://www.openai.com/) for providing the models used in this project.

Special thanks to Professor @Simon Shim for his guidance and support throughout this project, and to the DroneBlocks support team for their valuable insights into the SDK capabilities.