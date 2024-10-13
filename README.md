# Intellicoders Project

Intellicoders is a Flask-based web application that integrates basic JavaScript functionality. The project is designed to handle file uploads, interact with the Azure OCR API, and display results directly on the web interface.

## Features
- **File Upload**: Drag-and-drop or click to upload files.
- **Azure OCR Integration**: Send uploaded files to Azure OCR API for text extraction.
- **JavaScript Functionality**: Basic JavaScript integrated and served via Flask.

## Setup Instructions

### 1. Clone the Repository
Clone this repository to your local machine using: git clone url



### 3. Set Up a Virtual Environment
Set up a virtual environment in the `/Backend` folder: python -m venv venv


### 4. Activate the Virtual Environment
Activate the virtual environment:
- On macOS/Linux:
    ```
    source venv/bin/activate
    ```
- On Windows:
    ```
    .\venv\Scripts\activate
    ```

### 5. Install Dependencies
Install the required dependencies: pip install flask requests

### 6. Run the Flask App
Run the Flask application: python run.py


## Gitignore Files

The following files and directories should be included but have been left out: intellicoders/Backend/app/config.py



## How It Works

### 1. File Upload
The user can upload files via a drag-and-drop interface or by clicking a button. The uploaded files are sent to the Flask backend for processing.

### 2. Azure OCR API
The uploaded file is sent to the Azure OCR API for text extraction. The extracted text is then sent back to the frontend and displayed on the web interface.

### 3. JavaScript Integration
The project includes basic JavaScript functionality, such as handling file uploads and toggling dark mode, which is served via Flask.

---

This README should provide a comprehensive guide to setting up and understanding the Intellicoders project. If you have any questions or need further assistance, feel free to reach out!













