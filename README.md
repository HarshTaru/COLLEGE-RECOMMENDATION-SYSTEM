# College Recommendation System

The College Recommendation System is a web application developed using Flask for the backend, along with MySQL as the database management system. It provides functionalities for both administrators and users, allowing administrators to manage colleges and courses, while users can search for colleges and predict potential colleges based on their rank and scores.

## Features

### For Administrators:
- **Login System**: Administrators can log in using their credentials to access the admin dashboard.
- **College Management**: Add and manage colleges, including details such as institute code, name, status, and total intake.
- **Course Management**: Add and manage courses offered by colleges.

### For Users:
- **User Registration and Login**: Users can register and log in to access the user dashboard.
- **College Search**: Users can search for colleges based on various criteria.
- **College Predictor**: Users can predict potential colleges based on their rank and scores.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/college-recommendation-system.git
    ```

2. Navigate to the project directory:

    ```bash
    cd college-recommendation-system
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask application for normal users:

    ```bash
    python flaskapp.py
    ```

5. Run the Flask application for administrators:

    ```bash
    python flaskadmin.py
    ```

6. Access the application using a web browser:
   - For normal users: http://localhost:5000
   - For administrators: http://localhost:5000/adminDashboard.html

## Project Structure

- **`flaskapp.py`**: Main Flask application for normal users.
- **`flaskadmin.py`**: Flask application for administrators.
- **`templates/`**: Directory containing HTML templates for the frontend.
- **`static/`**: Directory containing static files such as CSS and JavaScript.
- **`database.sql`**: SQL script for creating the database schema.

## Database Configuration

- Ensure MySQL is installed and running on your system.
- Update the database configuration in the Flask application (`flaskapp.py` and `flaskadmin.py`) with your MySQL credentials.

## Contributing

Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to open an issue or submit a pull request.

