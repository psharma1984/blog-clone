# blog-clone

A multi-user blog

## Installation

To run this project locally, please follow these steps:

1. Clone the repository:
   git clone https://github.com/psharma1984/blog-clone.git
2. Navigate to project directory
   cd project-directory
3. Setup the virtual environment
   python -m venv env
   source env/bin/activate # On Linux/Mac
   .\env\Scripts\activate # On Windows
4. Install project dependencies using the requirements.txt file:
   pip install -r requirements.txt
5. Run the migrations
   python manage.py migrate
   python manage.py makemigrations blog
6. Start the development server
   python manage.py runserver
7. Access the application in your web browser at http://localhost:8000.
