# FastAPI Assignment – Day 4 (CRUD APIs)

## Overview

This repository contains the solution for the **FastAPI Day-4 Assignment** from the February 2026 Internship program. The project demonstrates building REST APIs using **FastAPI** to manage a simple product inventory system. The APIs allow users to create, update, delete, and retrieve product data, along with generating an inventory audit summary.

## Features

* Add new products using **POST API**
* Update product details such as price and stock status using **PUT API**
* Delete products from inventory using **DELETE API**
* Retrieve product details using **GET API**
* Generate inventory summary using **/products/audit**
* API testing and documentation via **Swagger UI**

## Technologies Used

* Python
* FastAPI
* Uvicorn
* Pydantic
* Swagger UI

## API Endpoints

| Method | Endpoint               | Description             |
| ------ | ---------------------- | ----------------------- |
| GET    | /products              | Retrieve all products   |
| POST   | /products              | Add a new product       |
| PUT    | /products/{product_id} | Update product details  |
| DELETE | /products/{product_id} | Delete a product        |
| GET    | /products/audit        | Inventory audit summary |

## How to Run the Project

### 1. Create Virtual Environment

```
python -m venv venv
```

### 2. Activate Virtual Environment

```
venv\Scripts\activate
```

### 3. Install Dependencies

```
pip install fastapi uvicorn
```

### 4. Run the Application

```
uvicorn main:app --reload
```

### 5. Open API Documentation

Open the Swagger UI in your browser:

```
http://127.0.0.1:8000/docs
```

## Project Structure

```
IN226008602_FASTAPI_ASSIGNMENT_3
│
└── ASSIGNMENT 1
    ├── main.py
    ├── Q1_Output.png
    ├── Q2_Output.png
    ├── Q3_Output.png
    ├── Q4_Output.png
    └── Q5_Output.png
```

## Author

**Praveen Kumar**
FastAPI Internship – February 2026
