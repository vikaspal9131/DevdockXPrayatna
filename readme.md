
## Project Overview
This project is designed for diagnosing ECG signals using machine learning techniques. It includes backend services for handling model predictions, API endpoints for interaction, and unit tests for ensuring reliability.

## Features
- ECG signal diagnosis using ML models
- REST API endpoints for model interaction
- User authentication and profile management
- Image and report retrieval

## Installation
#### Prerequisites
Ensure you have Python installed (recommended: Python 3.8 or later).

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/vikaspal9131/DevdockXPrayatna.git
   cd skitech
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   from setup.py

## Running the Application
### Start the Application
```bash
python app.py
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
- app.py          # Application entry point
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


## Webpages 


![Alt text](Readmeimage/Screenshot%202025-03-05%20202537.png)
![Alt text](Readmeimage/Screenshot%202025-03-05%20202557.png)

![Alt text](Readmeimage/Screenshot%202025-03-05%20202632.png)
![Alt text](Readmeimage/Screenshot%202025-03-05%20202649.png)

![Alt text](Readmeimage/Screenshot%202025-03-05%20202707.png)
![Alt text](Readmeimage/Screenshot%202025-03-05%20202632.png)
![Alt text](Readmeimage/Screenshot%202025-03-05%20202724.png)



