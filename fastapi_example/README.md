# FastAPI Example

This is a simple "Hello World" FastAPI application.

## Prerequisites

*   Python 3.7+
*   pip (Python package installer)

## Setup and Run

1.  **Navigate to the `fastapi_example` directory:**
    ```bash
    cd fastapi_example
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application using Uvicorn:**
    ```bash
    uvicorn main:app --reload
    ```
    The `--reload` flag makes the server restart after code changes.

5.  **Open your browser and go to `http://127.0.0.1:8000`**. You should see the JSON response:
    ```json
    {"message": "Hello World"}
    ```

6.  **To access the interactive API documentation (Swagger UI), go to `http://127.0.0.1:8000/docs`**.

7.  **To access the alternative API documentation (ReDoc), go to `http://127.0.0.1:8000/redoc`**.

## Deactivate virtual environment

When you are done, you can deactivate the virtual environment:
```bash
deactivate
```
