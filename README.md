# Chatbot

A simple chatbot application built using Python, Flask, and a trained neural network model.

## Features

- **Natural Language Understanding**: Interprets user input using a trained neural network model.
- **Web Interface**: Provides an interactive chat interface via a Flask web application.
- **Intent Recognition**: Classifies user messages into predefined intents.
- **Customizable Responses**: Easily extendable with new intents and responses.

## Project Structure

The repository contains the following key files and directories:

- `app.py`: Main Flask application file.
- `chatbot_model.h5`: Pre-trained model file for intent classification.
- `classes.pkl`: Pickled list of intent labels.
- `generate_json.py`: Script to generate JSON data for training.
- `intents.json`: JSON file containing training data.
- `nltk.txt`: Text file for NLTK data.
- `requirements.txt`: Python dependencies for the project.
- `runtime.txt`: Specifies the Python runtime for deployment.
- `train.py`: Script to train the chatbot model.
- `utils.py`: Utility functions for preprocessing and other tasks.
- `words.pkl`: Pickled list of stemmed words.
- `templates/`: Directory containing HTML templates for the web interface.
- `static/`: Directory for static files like CSS and JavaScript.

## Installation

**1. Clone the repository:**

```bash
git clone https://github.com/nick10h/chatbot.git
cd chatbot
```
**2. Chatbot Setup and Usage**:

**Set up a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate
```
**3. Install dependencies:**
```bash
pip install -r requirements.txt
```
**4. Download NLTK data:**
```bash
python -m nltk.downloader punkt
```
**5. Train the model:**
```bash
python train.py
```
**6. Run the Flask application:**
```bash
python app.py
```
The application will be accessible at http://127.0.0.1:5000/.


