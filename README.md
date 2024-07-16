
# Real-Time Fire Detection App

Welcome to the Real-Time Fire Detection Flask App! This application leverages YOLOv8 (You Only Look Once) for instant fire detection directly from your webcam feed. Built on the Flask web framework for Python, it offers a seamless and user-friendly experience.

## Technologies Used

- **YOLOv8:** Utilized for real-time object detection, specifically trained for detecting fires.
- **Flask:** Web framework used to build the backend server and serve the detection results.
- **Python:** Programming language used for backend logic and integration of YOLOv8.
- **HTML/CSS/JavaScript:** Frontend technologies for the user interface and interaction with the Flask backend.

## Features

- **Real-Time Fire Detection:** Instant detection of fires from live webcam feeds.
- **User-Friendly Interface:** Simple and intuitive web interface for easy interaction.
- **Scalability:** Capable of handling real-time detection across various environments.
- **Accessibility:** Can be accessed and utilized from any device with a web browser and webcam.

## Getting Started

### Prerequisites

Ensure you have Python and pip installed. Additionally, you may need to install virtualenv:

```bash
pip install virtualenv
```

### Installation

1. Clone the repository:

```bash
git clone [https://github.com/TheKingOo/YOLOv8-Fire-Detection-Webcam-App-with-Flask.git](https://github.com/bhavvyayy/Fire-Detection.git)
cd fire_detection
```

2. Create and activate a virtual environment:

```bash
# On Windows
python -m venv venv

# On macOS/Linux
python3 -m venv venv

# Activate the virtual environment
# On Windows
.\venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

### Usage

1. Run the Flask app:

```bash
python app.py
```

2. Open your web browser and go to `http://127.0.0.1:5000/` to access the app.

