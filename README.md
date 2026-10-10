
# Deep Fake Detection Using LSTM

## 🧠 Overview

This project focuses on detecting deepfake videos using Long Short-Term Memory (LSTM) networks. By analyzing sequential facial features across video frames, the model learns to identify temporal inconsistencies commonly found in manipulated videos. A Flask web interface allows users to upload videos and check whether they are real or fake.

**Note:** Extract `templates.zip` to obtain the required HTML template files.

## 🚀 Features

- 📹 Upload video files through a simple web interface.
- 👤 Detect and extract faces from video frames.
- 🧠 Analyze video sequences using an LSTM-based deep learning model.
- ✅ Classify videos as Real or Fake.
- 🌐 Provide a user-friendly web interface powered by Flask.

## 🔧 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/varshinisakthivel6/DeepFake--Detection.git
```

### 2. Navigate to the Project Directory

```bash
cd DeepFake--Detection
```

### 3. Extract the Template Files

Unzip `templates.zip` and ensure the required HTML files are available in the correct project directory.

### 4. Install Dependencies

If the repository contains a `requirements.txt` file, run:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Application

Run the Flask application using the appropriate Python entry-point file. For example, if the main file is `app.py`:

```bash
python app.py
```

Open the local URL displayed in the terminal to access the web interface.

## 🛠️ Technologies Used

- Python
- Flask
- Long Short-Term Memory (LSTM)
- Deep Learning
- Computer Vision

## 📌 Project Goal

To identify potentially manipulated videos by analyzing facial features and temporal patterns across video frames.

## 🤝 Contributions

Contributions and suggestions are welcome. Feel free to fork the repository and submit a pull request.
