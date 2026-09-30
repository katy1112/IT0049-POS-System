# POS System

A simple Point of Sale (POS) web application developed using **CodeIgniter 4** and **PHP**. The application demonstrates the basic use of the Model-View-Controller (MVC) architecture, routing, controllers, and views.

## Activity

**IT0049 – Web System Technologies**  
**Technical Formative Assessment 1**  
**POS System**

## Project Overview

This project is a basic Point of Sale web application created using CodeIgniter 4.

The application contains different pages for managing and displaying customer and user account information. For this activity, the application uses static PHP arrays to store sample customer and user records.

The project demonstrates how controllers pass data to views and how CodeIgniter routes connect different URLs to specific controller methods.

## Features

- POS system homepage
- About page
- Customer Accounts page
- User Accounts page
- Customer information display
- User information display
- CodeIgniter routing
- MVC architecture
- Static PHP array data
- Simple and organized web interface

## Pages

| Page | URL | Description |
|------|-----|-------------|
| Home | `/` | Displays the POS system homepage |
| About | `/about` | Displays information about the application |
| Customer Accounts | `/customers` | Displays customer account information |
| User Accounts | `/users` | Displays user account information |

## Technologies Used

- PHP
- CodeIgniter 4
- HTML5
- CSS3
- XAMPP

## Data Storage

For this activity, customer and user information is stored using **static PHP arrays**.

The sample data is passed from the Controllers to the Views and displayed on the corresponding pages.

Example:

```php
$customers = [
    [
        'id' => 1,
        'full_name' => 'Juan Dela Cruz',
        'email' => 'juan@example.com',
        'phone' => '09123456789'
    ],
];


MVC Structure

The application follows the CodeIgniter MVC architecture.

Model

The Model is responsible for handling application data.

View

The View is responsible for displaying the information to the user.

Controller

The Controller handles the application logic and passes data to the Views.

Project Structure
POS System/
├── app/
│   ├── Controllers/
│   │   ├── Customers.php
│   │   ├── Users.php
│   │   └── Pages.php
│   │
│   └── Views/
│       ├── customers/
│       ├── users/
│       └── pages/
│
├── public/
├── system/
├── vendor/
├── .env
├── composer.json
└── README.md
How to Run the Project Locally
1. Install XAMPP

Make sure Apache is running through XAMPP.

2. Place the Project

Place the project folder inside:

C:\xampp\htdocs\training
3. Start the Application

Open the project in your browser:

http://localhost/training/
Purpose of the Project

This project demonstrates the basic concepts of CodeIgniter 4, including:

Routing
Controllers
Views
MVC architecture
Passing data from Controllers to Views
Displaying data using PHP arrays
Basic web application structure

Developer:
Katrina Mangat

