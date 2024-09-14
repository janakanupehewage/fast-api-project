## Vehicle Type Prediction API
![FastAPI](README%20images/FastAPI_b.jpg)

This repository contains a FastAPI application that uses a pre-trained model to predict the type of vehicle (bus, car, motorcycle, or truck) based on an uploaded image.

## Features

- **FastAPI:** Provides a RESTful API for image uploads and vehicle type predictions.
- **TensorFlow:** Uses a Keras model for vehicle type classification.
- **Image Preprocessing:** Converts uploaded images to the correct format for the model.
- **PIL: Handles image** manipulation and conversion.

## Requirements

- Before running the application, make sure you have the following dependencies installed:

    ```bash
        pip install fastapi tensorflow pillow uvicorn
    ```

- You can install all the required dependencies at once using the following command:
    ```bash
        pip install -r requirements.txt
    ```
H
## How to Run the Application

1. **Clone this repository**:
    ```bash
    git clone https://github.com/janakanupehewage/fast-api-project.git
    cd fast-api-project
    ```

2. **Ensure the model file is in place:**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Ensure the model file is in place:**:
    Make sure your model file (vehicle_type_identifier_model.keras) is placed in the same directory as main.py.

4. **Run the FastAPI Application::**:
    ```bash
    uvicorn main:app --reload
    ```

5. **Access the API:**:
    ```bash
    http://127.0.0.1:8000
    ```

6. **Get Swager UI**

    ```bash
    http://127.0.0.1:8000/docs
    ```
