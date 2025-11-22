peersafe-backend/
│
├── backend/
│   ├── peersafe/           # Django project root
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   │
│   ├── escrow/             # Core escrow app
│   │   ├── __init__.py
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── views.py
│   │   ├── urls.py
│   │   └── tasks.py        # scheduled fine/refund jobs
│   │
│   ├── payments/           # payment integrations
│   │   ├── __init__.py
│   │   ├── stripe_api.py
│   │   ├── paypal_api.py
│   │   └── webhook_handlers.py
│   │
│   ├── users/              # authentication
│   │   ├── __init__.py
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── views.py
│   │   └── urls.py
│   │
│   ├── notifications/      # push + email notifications
│   │   ├── __init__.py
│   │   ├── push.py
│   │   └── email.py
│
├── requirements.txt
├── Dockerfile
├── runtime.txt
├── Procfile
├── manage.py
└── README.md
