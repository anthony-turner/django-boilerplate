# README.md
# Django Project Boilerplate

A production-ready Django project template with best practices built-in.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Features
- PostgreSQL database configuration
- Environment variables using python-decouple
- REST framework integration
- CORS headers support
- Organized project structure
- Docker support (optional)

## Quick Start
1. Clone this repository
2. Create a virtual environment: `python -m venv venv`
3. Activate it: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows)
4. Install requirements: `pip install -r requirements.txt`
5. Create a `.env` file based on `.env.example`
6. Run migrations: `python manage.py migrate`
7. Create superuser: `python manage.py createsuperuser`
8. Run the server: `python manage.py runserver`