# Beauty Parlour Website

A web application developed for a beauty parlour client to showcase salon services, provide business information, and manage customer enquiries and appointments.

## Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Python, Django
- **Database:** SQLite (Development)
- **Version Control:** Git and GitHub

## Project Structure

```text

beauty-parlour-website/
│
├── .venv/                         # Virtual environment (ignored)
│
├── config/                        # Django project configuration
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── main/                          # Main Django application
│   ├── migrations/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── templates/                     # Project-level templates
│   │└── main/
│   │    ├── home.html
│   │    └── ...
│   └── base.html
│
├── static/                        # Project-level static files
│   ├── css/
│   ├── js/
│   └── images/
│
├── media/                         # Uploaded media
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md

```

## Local Development Setup

### 1. Clone the repository

```bash
git clone https://github.com/swethamanju2002/beauty-parlour-website.git
cd beauty-parlour-website
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply migrations

```bash
python manage.py migrate
```

### 6. Run the development server

```bash
python manage.py runserver
```

Open http://127.0.0.1:8000/ in your browser.

## Git Collaboration Guidelines

- `main` – Stable and reviewed code.
- `swetha` – Swetha's development branch.
- `shobana` – Shobana's development branch.
- All changes must be pushed through feature branches.
- Create a Pull Request before merging into `main`.
- Never commit virtual environments, secret keys, or local database files.

## Project Status

Under Development.