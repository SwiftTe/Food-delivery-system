QuickBite/
│
├── quickbite/                  # Main Django project
│   ├── accounts/               # User authentication app
│   │   ├── migrations/
│   │   ├── templates/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   └── views.py
│   │
│   ├── core/                   # Home page / main UI
│   │   ├── migrations/
│   │   ├── templates/
│   │   │   └── home.html
│   │   ├── admin.py
│   │   ├── models.py
│   │   └── views.py
│   │
│   ├── orders/                # Order system
│   │   ├── migrations/
│   │   ├── admin.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   └── views.py
│   │
│   ├── restaurant/           # Restaurant + food items
│   │   ├── migrations/
│   │   ├── admin.py
│   │   ├── models.py
│   │   └── views.py
│   │
│   ├── quickbite/            # Project config
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   │
│   ├── db.sqlite3
│   └── manage.py
│
├── venv/                     # Virtual environment (ignored in git)
│
└── README.md