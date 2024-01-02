# Quiz-App Using FastAPI

## About The Project
This project introduces an engaging Quiz App built with FastAPI and PostgreSQL, providing an interactive platform for users to create, answer, and receive feedback on quiz questions.

Feature:
* Creation of quiz questions and answers
* Immediate feedback on correct or incorrect answers

### Built With
* Python 
* FastAPI
* PostgreSQL
 
## Getting Started

### Prerequisites
Ensure the following prerequisites are met before getting started:

* Python is installed on your system
* An Integrated Development Environment (IDE) is set up
* FastAPI & Uvicorn are installed
* PostgreSQL - pgAdmin4


### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Erhesvara/Quiz-App.git
   ```
3. Navigate to the project directory.

## Usage

### Launching the App

1. **Start the FastAPI Server**

    Run the following command in the terminal to initiate the FastAPI server:
    ```sh
    uvicorn main:app --reload
    ```
    This command starts the FastAPI server, enabling access to the Quiz App through designated endpoints.

2. **Accessing the App**

    Open a web browser and navigate to `http://localhost:8000` or the specified port where the FastAPI server is running.

### Interacting with the Quiz App

- **Creating Quiz Questions:**

    Use the provided API endpoints to create new quiz questions and their corresponding answers.

- **Answering Quiz Questions:**

    Utilize the appropriate endpoint to submit answers to the quiz questions.

- **Receiving Feedback:**

    Upon answering questions, the app will promptly provide feedback, indicating whether the responses were correct or incorrect.

### Exploring Endpoints and API Documentation

Utilize the provided API documentation or navigate to the Swagger UI available at `http://localhost:8000/docs` to comprehend and interact with the diverse endpoints available for managing quiz-related functionalities.

### Stopping the App

To halt the FastAPI server, return to the terminal where the server is running and press `Ctrl + C` to shut it down.






