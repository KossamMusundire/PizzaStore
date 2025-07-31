# 🍕 PizzaStore API

A simple demonstration API for managing a list of pizzas, built with ASP.NET Core Minimal APIs. This project serves as a great starting point for learning the basics of building lightweight web APIs with .NET.

## ✨ Features

- **Modern .NET:** Built using the latest .NET and C# features.
- **Minimal APIs:** Leverages the new Minimal API framework in ASP.NET Core for a clean and concise setup.
- **Swagger/OpenAPI:** Comes with out-of-the-box support for Swagger UI, providing interactive API documentation.
- **In-Memory Database:** Uses a simple in-memory list to act as a database for demonstration purposes.

## 🚀 Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0) or later.

### Running the Application

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd PizzaStore
    ```

2.  **Run the project:**
    ```bash
    dotnet run
    ```

3.  **Access the API:**
    - The application will start and listen on a local port (e.g., `http://localhost:5150`).
    - You can access the interactive Swagger documentation by navigating to `/swagger` in your browser (e.g., `http://localhost:5150/swagger`).

## 📝 API Endpoints

The following endpoints are available. You can test them all from the Swagger UI.

### Health Check

- `GET /`
  - **Description:** A simple endpoint to check if the API is running.
  - **Success Response:** `200 OK` with the text `Hello World!`.

*(More endpoints for managing pizzas will be added soon!)*

