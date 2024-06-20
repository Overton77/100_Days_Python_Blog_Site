# Blog Website

This is a simple blog website created with Flask and SQLite. The application allows users to create posts, add comments, and includes a text editor area with basic authentication.

## Features

- Create and manage blog posts
- Comment on posts
- Simple text editor for post creation
- User authentication

## Prerequisites

- Python 3.11.4 or higher

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/blog-website.git
   cd blog-website
   ```

2. Create a virtual environment:

   ```bash
   python -m venv blogAuthGit
   ```

3. Activate the virtual environment:

   - **Windows**:

     ```bash
     blogAuthGit\Scripts\activate
     ```

   - **macOS/Linux**:

     ```bash
     source blogAuthGit/bin/activate
     ```

4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:

   ```bash
   python main.py
   ```

2. Open your web browser and go to:

   ```
   http://localhost:5001
   ```

## Dependencies

The application relies on the following Python packages:

- Bootstrap-Flask==2.2.0
- Flask==2.2.5
- Flask-CKEditor==0.4.6
- Flask-Login==0.6.2
- Flask-Gravatar==0.5.0
- flask_sqlalchemy==3.0.5
- Flask-WTF==1.2.1
- Werkzeug==2.2.3
- WTForms==3.0.1
- SQLAlchemy==2.0.19
- gunicorn==21.2.0
- psycopg2-binary==2.9.6

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
