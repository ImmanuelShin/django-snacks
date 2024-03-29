# Lab - Class 26

## Project: Django Snacks

### Author: Immanuel Shin

### Setup

**How to initialize/run your application:**
  1. Clone the repository.
   ```bash
   git clone
   ```
  2. Navigate to the project directory.
   ```bash
   cd django-snacks
   ```
  3. Activate your virtual environment (if applicable).
   ```bash
   python3 -m venv .venv
   source .venv/Scripts/activate
   ```
  4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
  5. Apply migrations:
  ```bash
  python manage.py migrate
  ```
  6. Run server:
  ```bash
  python manage.py runserver
  ```
  7. Go to URL: Most likely http://127.0.0.1:8000/

### Tests

Run tests with:
```bash
python manage.py test
```
