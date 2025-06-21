# Login System 🚀

![Login System](https://img.shields.io/badge/Login%20System-Python%20Flask%20and%20SQLite-brightgreen)

Welcome to the **Login System** repository! This project provides a simple web-based login and registration system built with Python Flask and SQLite. It allows users to register, log in, and access a protected home page. This project is perfect for beginners who want to learn about user authentication and database integration in Flask.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- User registration
- User login
- Protected home page
- SQLite database integration
- Simple and clean user interface
- Beginner-friendly code structure

## Technologies Used

This project utilizes the following technologies:

- **Python 3**: The programming language used to build the application.
- **Flask**: A lightweight web framework for Python that makes it easy to build web applications.
- **SQLite**: A simple database engine used for storing user data.
- **HTML/CSS**: For creating the user interface.

## Installation

To set up the Login System on your local machine, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/alid070/Login-System.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Login-System
   ```

3. **Create a virtual environment** (optional but recommended):

   ```bash
   python3 -m venv venv
   ```

4. **Activate the virtual environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

5. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```

6. **Run the application**:

   ```bash
   python app.py
   ```

Now, you can access the application at `http://127.0.0.1:5000`.

## Usage

After running the application, you can use the following features:

1. **Register**: Click on the registration link to create a new account. Fill in the required fields and submit the form.

2. **Login**: After registering, you can log in using your credentials. If the login is successful, you will be redirected to the protected home page.

3. **Home Page**: This page is accessible only to logged-in users. You can see a welcome message and log out from this page.

### Screenshots

![Login Page](https://via.placeholder.com/600x400.png?text=Login+Page)

![Registration Page](https://via.placeholder.com/600x400.png?text=Registration+Page)

![Home Page](https://via.placeholder.com/600x400.png?text=Home+Page)

## Project Structure

Here's a brief overview of the project structure:

```
Login-System/
│
├── app.py                  # Main application file
├── requirements.txt        # List of required packages
├── templates/              # HTML templates
│   ├── login.html          # Login page template
│   ├── register.html       # Registration page template
│   └── home.html           # Home page template
└── static/                 # Static files (CSS, JS, images)
    └── styles.css          # CSS file for styling
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Open a pull request.

Please ensure your code adheres to the project's coding standards and is well-documented.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Links

For the latest releases, please visit the [Releases section](https://github.com/alid070/Login-System/releases). You can download the latest version and execute it to get started with the application.

For more information, check the [Releases section](https://github.com/alid070/Login-System/releases) for updates and improvements.

---

Thank you for checking out the Login System project! We hope it helps you learn about user authentication and database management in Flask. If you have any questions or feedback, feel free to reach out. Happy coding!