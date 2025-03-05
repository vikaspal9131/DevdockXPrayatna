# Skitech Streamlit

## Project Overview
This project is a Streamlit-based application designed for diagnosing ECG signals using machine learning techniques. It includes backend services for handling model predictions, API endpoints for interaction, and unit tests for ensuring reliability.

## Features
- ECG signal diagnosis using ML models
- REST API endpoints for model interaction
- User authentication and profile management
- Image and report retrieval
- Streamlit-based frontend

## Installation
### Prerequisites
Ensure you have Python installed (recommended: Python 3.8 or later).

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd skitech-streamlit
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application
### Start the Streamlit App
```bash
streamlit run app.py
```

### Running Tests
Execute unit tests using:
```bash
python -m unittest discover tests
```

## Project Structure
```
- backend/        # Contains the backend logic and API endpoints
- tests/          # Unit tests for API endpoints and ML models
- app.py          # Streamlit application entry point
- requirements.txt # Project dependencies
- setup.py        # Package setup configuration
```

## API Endpoints
| Endpoint                 | Method | Description                         |
|--------------------------|--------|-------------------------------------|
| `/api/project`           | GET    | Get project details                |
| `/api/project/docs`      | GET    | Retrieve documentation URL         |
| `/api/model`             | GET    | Get model details                  |
| `/api/model/metrics`     | GET    | Get model performance metrics      |
| `/api/ecg/images`        | GET    | Retrieve ECG images                |
| `/api/diagnosis`         | GET    | List all diagnoses                 |
| `/api/ecg/upload`        | POST   | Upload an ECG file                 |
| `/api/ecg/process`       | POST   | Process an uploaded ECG file       |
| `/api/users/register`    | POST   | Register a new user                |
| `/api/users/login`       | POST   | Authenticate a user                |
| `/api/users/profile`     | GET    | Retrieve user profile              |


