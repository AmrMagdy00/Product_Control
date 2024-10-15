# Product Control Application

## Overview

**Product Control** is a web-based application designed to help you efficiently manage your products. It streamlines operations, helps in inventory control, and enables you to manage sales more effectively.

The application provides a user-friendly interface for CRUD (Create, Read, Update, Delete) operations, allowing for easy product management.

---

## Features

- **Product Management**: Add, edit, and delete products from the system.
- **Responsive Design**: Fully responsive layout using Bootstrap, ensuring compatibility with different devices.
- **Real-time Data**: Manage product prices, names, and details with real-time feedback.
- **Animations**: Smooth and engaging animations using Animate.css.
- **CRUD Operations**: Full functionality for managing products.

---

## Technologies

- **ASP.NET Core** - Backend framework for building web applications.
- **Entity Framework Core** - ORM for handling database interactions.
- **Bootstrap 4/5** - Frontend framework for responsive design.
- **Font Awesome** - Icon library used throughout the interface.
- **Animate.css** - Library for adding CSS animations.
- **SQL Server** - Database for persisting data.

---

## Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

Make sure you have the following installed on your system:

- **.NET SDK** (at least version 6.0 or higher)
- **SQL Server** or **SQL Express** for the database

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/Product_Control.git
    cd Product_Control
    ```

2. **Set up the database**:

    Ensure that your connection string in `appsettings.json` points to your local SQL Server.  
    Run the following commands to apply the migrations and set up the database:

    ```bash
    dotnet ef database update
    ```

3. **Run the application**:

    Use the following command to start the application:

    ```bash
    dotnet run
    ```

4. **Access the application**:

    Navigate to `http://localhost:5000` in your web browser.

---

## Usage

Once the application is running, you can:

- **Add Products**: Go to the **Add Product** page to create new products.
- **View Products**: View the entire list of products in the **Product List**.
- **Edit Products**: Click on **Edit** next to any product to modify its details.
- **Delete Products**: Remove products by clicking on the **Delete** button in the product list.



