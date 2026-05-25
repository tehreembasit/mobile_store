# Mobile Store Web Application

A Flask-based web application for browsing and purchasing mobile phones online. The system includes user authentication, product browsing, shopping cart functionality, and order management using SQLite database integration.

## Features
- User Signup and Login System
- Secure Password Hashing
- Mobile Brand and Model Browsing
- Product Details with Images and Pricing
- Shopping Cart System
- Order Summary and Checkout
- Session Management
- SQLite Database Integration

## Technologies Used
- Python
- Flask
- SQLite3
- HTML
- CSS
- Werkzeug Security

## Project Structure
```text
mobile_store/
│
├── app.py                 # Main Flask application
├── database.db            # SQLite database
├── templates/
│   ├── login.html
│   ├── signup.html
│   ├── companies.html
│   ├── models.html
│   ├── cart.html
│   └── summary.html
│
├── static/
│   └── style.css
│
└── README.md
