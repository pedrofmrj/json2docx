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

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

Copyright (C) 2024 JSON to DOCX Converter

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.