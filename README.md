# JSON to DOCX Converter v1.0

A simple web application that converts JSON data to DOCX format using FastAPI backend and a clean HTML/JavaScript frontend with Tailwind CSS.

## Features

- Convert JSON data to DOCX format
- Simple and intuitive user interface
- Support for nested JSON structures
- Real-time JSON validation
- Automatic file download

## Tech Stack

- Backend: FastAPI (Python)
- Frontend: HTML, JavaScript
- Styling: Tailwind CSS

## Installation

1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
## Running the Application
Start the server:

```bash
uvicorn main:app --reload --port 9000
 ```

Access the application at: http://localhost:9000

## Usage

1. Open the application in your browser
2. Enter valid JSON in the text area
3. Click "Convert to DOCX" button
4. The converted DOCX file will automatically download

## Example JSON Input

{
    "name": "John Doe",
    "age": 30,
    "contact": {
        "email": "john@example.com",
        "phone": "123-456-7890"
    }
}