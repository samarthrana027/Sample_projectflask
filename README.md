# Sample Flask Project

A simple Flask web application that demonstrates form handling and template rendering.

## 📋 Project Overview

This is a beginner-friendly Flask project that showcases:
- Flask routing and HTTP methods (GET, POST)
- Form handling with request data
- HTML template rendering
- Welcome message display based on user input

## 📁 Project Structure

```
Sample_projectflask/
├── Main.py                 # Flask application entry point
├── templates/
│   └── name.html          # HTML form template
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Flask framework

### Installation

1. Install Flask (if not already installed):
```bash
pip install flask
```

2. Clone or navigate to this repository:
```bash
cd Sample_projectflask
```

### Running the Application

Run the Flask application:
```bash
python Main.py
```

The application will start on `http://localhost:5000` with debug mode enabled.

## 📝 How It Works

1. **Main.py** - Flask Application
   - Defines a Flask app with a `/submission` route
   - Handles both GET and POST requests
   - Renders the `name.html` template on GET request
   - Processes form submission on POST request and displays a welcome message

2. **templates/name.html** - User Form
   - Simple HTML form with a text input field for username
   - Includes a submit button
   - Form method is POST, submitting to the same `/submission` endpoint

## 🔄 Application Flow

1. User navigates to `http://localhost:5000/submission`
2. The GET request renders the form (name.html)
3. User enters their name and clicks submit
4. POST request is processed, extracting the username from form data
5. Application displays: "Hello, {username}, welcome to Flask!"

## 📦 Dependencies

- **Flask** - Python web framework for building web applications

## 💡 Features

- ✅ Simple form-based user input
- ✅ Dynamic greeting message
- ✅ HTML template rendering
- ✅ GET/POST method handling
- ✅ Debug mode for development

## 🛠️ Technology Stack

| Technology | Purpose |
|-----------|---------|
| Python | Programming language |
| Flask | Web framework |
| HTML | Form UI |

## 📚 Learning Objectives

This project is great for learning:
- Flask route definition and decorators
- HTTP request methods (GET, POST)
- Template rendering with `render_template()`
- Form data handling with `request.form`
- Flask development server usage

## 🔧 Future Enhancements

- Add CSS styling to the form
- Implement form validation
- Add error handling
- Database integration for storing submissions
- Add more routes and pages

## 📄 License

This project is open source and available for educational purposes.

## 👤 Author

Created as a sample Flask learning project.

---

**Happy Learning! 🎓**
