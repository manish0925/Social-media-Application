Social Media Feed Project

📝 Overview

This project is a Social Media Feed web application built with Python, Django, and a virtual environment. It allows users to view, create, and manage social media posts in a dynamic and interactive way.

🚀 Features

User authentication (Login/Signup)

Create, update, and delete posts

Like and comment functionality

Responsive design for mobile and desktop

Real-time updates using AJAX (optional)

🛠️ Technologies Used

Frontend: HTML, bootstrap5

Backend: Python, Django

Database: SQLite3 

Virtual Environment: Python venv

🏗️ Installation & Setup

Clone the repository:

git clone https://github.com/manish0925/social_media_feed.git
cd social_media_feed

Create a virtual environment:

python -m venv myenv

Activate the virtual environment:

For Windows (PowerShell):

Set-ExecutionPolicy Unrestricted -Scope CurrentUser
.\myenv\Scripts\activate

For Mac/Linux:

source myenv/bin/activate

Install dependencies:

pip install -r requirements.txt

Run database migrations:

python manage.py migrate

Start the server:

python manage.py runserver

Now, visit http://127.0.0.1:8000/ in your browser to see your app live! 🚀

📂 Project Structure

├── social_media_feed
│   ├── manage.py
│   ├── myenv/ (virtual environment)
│   ├── db.sqlite3 (database)
│   ├── requirements.txt (dependencies)
│   ├── app/ (Django app)
│   │   ├── models.py
│   │   ├── views.py
│   │   └── templates/

📚 Usage

Register a new account or log in.

Create a new post from the homepage.

Like or comment on other users' posts.

Edit or delete your own posts anytime.

🛠️ Troubleshooting

If you face the ExecutionPolicy error in PowerShell, run this command as admin:

Set-ExecutionPolicy Bypass -Scope Process

Then, try activating the environment again.

👥 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License — feel free to use and modify as needed.
