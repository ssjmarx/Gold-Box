# Licenses

This folder contains the licenses for third-party libraries used in The Gold Box project.

## Included Libraries

### Flask 2.3.3
- **License**: BSD 3-Clause License
- **File**: `Flask-BSD-3-Clause.txt`
- **Copyright**: (c) 2010, Armin Ronacher
- **Website**: https://flask.palletsprojects.com/

Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications.

### Flask-CORS 4.0.0
- **License**: MIT License
- **File**: `Flask-CORS-MIT.txt`
- **Copyright**: (c) 2014 Cory Dolphin
- **Website**: https://flask-cors.readthedocs.io/

A Flask extension for handling Cross Origin Resource Sharing (CORS), making cross-origin AJAX possible.

### python-dotenv 1.0.0
- **License**: BSD 3-Clause License
- **File**: `python-dotenv-BSD-3-Clause.txt`
- **Copyright**: (c) 2014, Saurabh Kumar, 2013, Ted Tieken, 2013, Jacob Kaplan-Moss
- **Website**: https://github.com/theskumar/python-dotenv

A Python module to read key-value pairs from a .env file and set them as environment variables.

## Usage in The Gold Box

All three libraries are used in the Python backend (`backend/server.py`) to:

1. **Flask**: Provide the web server and API endpoints
2. **Flask-CORS**: Enable secure cross-origin requests from the Foundry VTT frontend
3. **python-dotenv**: Load environment variables from .env files for secure configuration management

## Compliance

The Gold Box project is licensed under CC-BY-NC-SA 4.0, which is compatible with both the BSD 3-Clause and MIT licenses used by these dependencies. All license requirements are properly followed and attribution is provided where required.
