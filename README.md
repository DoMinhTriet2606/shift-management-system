# Shift Management System

The Shift Management System is a web application designed to streamline shift scheduling and tracking for small to medium-sized food and beverage businesses. It offers features for both employees and managers to efficiently manage shifts, view assignments, and track worked hours.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourUsername/shift-management-system.git
   cd shift-management-system
2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
3. **Install Required Libraries: Make sure you have the requirements.txt file in your project directory, then run**:
   ```bash
   python -m pip install requirement.txt
4. **Create a .env File: Create a .env file in the root directory and add your environment variables as needed.**
5. **Run the Application**
   ```bash
   uvicorn app.main:app --reload
