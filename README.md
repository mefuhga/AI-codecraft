# AI CodeCraft Project

## Project Overview

The AI CodeCraft project is a Flask-based web application designed to showcase essential functionalities like user registration, login, and dashboard management, along with sustainability metrics visualization. The application emphasizes modern web development practices with potential integration of AI-driven coding tools and sustainability features.

## Features

### User Management
- **Register**: Allows new users to create accounts with secure password hashing.
- **Login**: Enables users to log in with secure credential verification.
- **Logout**: Provides an option for users to log out securely.

### Dashboard
- A personalized dashboard where users are welcomed by their username.

### Sustainability Metrics Visualization
- Interactive graphs to visualize sustainability metrics over time, such as:
  - Energy Consumption (kWh)
  - Waste Reduction (kg)
  - Carbon Footprint (kg CO2)

## File Structure
```
AI_CodeCraft_Project/
├── templates/
│   ├── dashboard.html       # User dashboard template
│   ├── login.html           # User login template
│   ├── register.html        # User registration template
│   ├── metrics.html         # Sustainability metrics visualization template
├── app.py                   # Flask application logic
├── requirements.txt         # Python dependencies (to be created)
├── README.md                # Project overview (this file)
```

## Setup Instructions

### Prerequisites
- Python 3.6+
- Pip (Python package manager)

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourUsername/AI_CodeCraft_Project.git
   cd AI_CodeCraft_Project
   ```

2. **Set up a virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   python app.py
   ```
   The application will be available at `http://127.0.0.1:5000`.

## Key Functionality

### Flask Application (`app.py`)
- **Routes**:
  - `/register`: Handles user registration with secure password storage.
  - `/login`: Verifies user credentials and manages user sessions.
  - `/dashboard`: Displays a personalized dashboard upon successful login.
  - `/logout`: Logs out the user and ends the session.
- **Security**:
  - Passwords are securely hashed using `werkzeug.security`.
  - Session management ensures protected user data.

### Templates
- Templates are written in HTML and integrate Flask's Jinja2 templating engine.
- Example templates include user forms (`login.html`, `register.html`) and visualizations (`metrics.html`).

## Future Enhancements
- Integration with AI-driven coding tools for real-time code suggestions and analysis.
- Improved sustainability metrics dashboard with more data points and insights.
- Advanced user roles and permissions.

## License
This project is currently not licensed. You can update this section as needed.

## Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## Contact
For questions or support, please reach out to [Your Name or Email].
