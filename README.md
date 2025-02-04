#  Flask Web App with MySQL

This is a **Flask-based web application** that connects to **MySQL**, 
renders **HTML pages**, and includes **CSS styling** for a modern UI. 
The app supports **user authentication, session management, and database interactions**.

---

## Features

✅ User registration with hashed passwords (using `bcrypt`)  
✅ User login with session-based authentication  
✅ Dashboard displaying user details  
✅ Secure MySQL database connection  
✅ Bootstrap-based responsive UI  
✅ Proper error handling and security measures  

---

## Tech Stack

| Component  | Technology |
|------------|-----------|
| **Backend** | Flask (Python) |
| **Frontend** | HTML, CSS (Bootstrap) |
| **Database** | MySQL |
| **Authentication** | Bcrypt (hashed passwords) |
| **Version Control** | Git & GitHub |

---

##  Folder Structure
/your_project/ │── app.py # Main Flask application │── config.py # Database & app configuration 
│── requirements.txt # Dependencies │── .gitignore # Ignored files │── README.md # Project documentation 
│── /static/ # CSS, JS, images │ ├── styles.css │── /templates/ # HTML pages │ ├── index.html │ 
├── login.html │ ├── dashboard.html │── /venv/ # Virtual environment (ignored)

### 1️⃣ Clone the Repository
### 2️⃣ Create a Virtual Environment & Install Dependencies
      python -m venv venv
      source venv/bin/activate  # On Windows: venv\Scripts\activate
      pip install -r requirements.txt

### 3️⃣ Set Up the MySQL Database
* Open MySQL and create a database:
    CREATE DATABASE my_flask_app;
* Update config.py with your MySQL credentials.

### 4️⃣ Run the Flask App
  * python app.py
  * Open http://127.0.0.1:5000/ in your browser.
