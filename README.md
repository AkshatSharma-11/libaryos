📚 LibraryOS

A modern, lightweight Library Management System built with Python, Flask, and SQLite for managing books, members, and library transactions efficiently.








✨ Overview

LibraryOS is a web-based library management application designed to simplify everyday library operations.

It provides a centralized interface for managing books and members, tracking book issue/return transactions, searching the library catalog, and viewing important library statistics.

The project is built with a simple and maintainable architecture using Flask for the backend and SQLite for data persistence.

🚀 Features
📖 Book Management

Add new books to the library

Edit existing book information

Delete books

Search books by:

Title

Author

ISBN

Track book availability

👥 Member Management

Register library members

Update member information

Remove members

Maintain member records

🔄 Transaction Management

Issue books to members

Return borrowed books

Track transaction records

Manage due dates

Monitor currently issued books

📊 Dashboard & Statistics

Library overview

Book statistics

Member statistics

Transaction information

Quick access to important library data

🔍 Search

Quickly find books using:

Book title

Author name

ISBN

🛠️ Tech Stack
Technology	Purpose
Python	Core programming language
Flask	Web application framework
SQLite	Database
HTML5	Application structure
CSS3	Styling and UI
JavaScript	Client-side functionality
Jinja2	Server-side templating
🏗️ Project Architecture
LibraryOS/
│
├── run.py
├── requirements.txt
├── library.db
│
├── app/
│   ├── __init__.py
│   ├── models.py
│   │
│   └── routes/
│       ├── main.py
│       ├── books.py
│       ├── members.py
│       └── transactions.py
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── statistics.html
│   ├── search_books.html
│   │
│   ├── books/
│   ├── members/
│   └── transactions/
│
└── static/
    ├── css/
    │   └── style.css
    │
    └── js/
        └── main.js

⚙️ Getting Started
Prerequisites

Make sure you have the following installed:

Python 3.x

pip

Git

1. Clone the repository
git clone https://github.com/AkshatSharma-11/libaryos.git


Navigate into the project:

cd libaryos/systemv2

2. Create a virtual environment

Windows:

python -m venv venv
venv\Scripts\activate


macOS / Linux:

python3 -m venv venv
source venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Run the application
python run.py

5. Open the application

Visit:

http://localhost:5000


The SQLite database is initialized automatically when the application is first started.

🖥️ Application Modules

LibraryOS is organized into several functional modules:

Dashboard

Provides an overview of the library and quick access to major functionality.

Books

Handles the complete lifecycle of library books, including creation, editing, deletion, searching, and availability.

Members

Provides functionality for registering and managing library members.

Transactions

Handles book issuing and returning while maintaining transaction records and due-date information.

Statistics

Provides a centralized view of important library metrics.

🔐 Data Management

LibraryOS uses SQLite for lightweight and reliable local data persistence.

The database stores information related to:

Books

Members

Transactions

Library statistics

The database file is created automatically when the application starts.

Note: For production deployments, consider using environment-specific configuration, backups, authentication, and a production-grade database such as PostgreSQL.

📈 Future Improvements

The project can be extended with additional capabilities such as:

🔐 User authentication and role-based access

📧 Email notifications for overdue books

📱 Responsive mobile-first UI

📅 Advanced due-date management

📊 Advanced analytics and reports

📥 CSV/Excel import and export

🖨️ Printable transaction reports

🌐 REST API

☁️ Cloud deployment

🗄️ PostgreSQL/MySQL support

🧪 Automated unit and integration tests

🐳 Docker support

🧪 Development

For development, it is recommended to use a virtual environment:

python -m venv venv


Activate it and install the project dependencies:

pip install -r requirements.txt


Then start the Flask application:

python run.py

🤝 Contributing

Contributions are welcome.

If you'd like to improve LibraryOS:

Fork the repository

Create a new branch

git checkout -b feature/your-feature


Make your changes

Commit your changes

git commit -m "feat: add your feature"


Push the branch

git push origin feature/your-feature


Open a Pull Request

Please keep contributions focused, documented, and consistent with the existing project structure.

🐛 Issues & Feedback

If you discover a bug or have an idea for improving LibraryOS, please open an issue in the GitHub repository.

When reporting a bug, include:

A clear description of the issue

Steps to reproduce it

Expected behavior

Actual behavior

Relevant error messages or screenshots

📄 License

This project is intended as an open-source library management application.

If a specific license has been added to the repository, refer to the LICENSE file for the applicable terms.

👨‍💻 Author

Akshat Sharma

Built with Python, Flask, and a focus on practical software engineering.

⭐ Support

If you find LibraryOS useful or interesting, consider giving the repository a ⭐ on GitHub.

It helps support the project and encourages further development.

Repository:
https://github.com/AkshatSharma-11/libaryos

<p align="center"> Made with ❤️ using Python & Flask </p>
