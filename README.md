# Polls app

Django tutorial app

## Run the project locally

- Clone and cd into project directory
- Use virtual environment: `python -m venv .venv && source .venv/bin/activate`
- Install dependencies: `pip install -r requirements.txt`
- Apply database migrations: `python manage.py migrate`
- Run development server: `python manage.py runserver`
- Navigate to `localhost:8000/polls`

## Use admin dashboard

- Create admin user: `python manage.py createsuperuser`
- Run development server: `python manage.py runserver`
- Navigate to `localhost:8000/admin`
