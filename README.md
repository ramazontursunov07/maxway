# MaxWay

MaxWay is a food ordering web application built with Python and Django. Customers can browse the menu, add items to their cart, and place orders with delivery details and a payment method. All orders can be viewed and managed in the dashboard.

## Features

- Menu with products
- Shopping cart
- Order placement with delivery details
- Payment method selection
- Dashboard for viewing and managing orders
- Docker support (Dockerfile and docker-compose)

## Tech Stack

- Python
- Django (MVT architecture)
- SQL database
- HTML, CSS (templates and static files)
- Docker, Docker Compose
- Git

## Project Structure

```
maxway/
├── config/        # Django project settings and URLs
├── food/          # Menu, cart and orders
├── dashboard/     # Dashboard for managing orders
├── templates/     # HTML templates
├── static/        # CSS, JS and other static files
├── media/         # Uploaded product images
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
└── manage.py
```

## Getting Started

### Run locally

1. Clone the repository:

```bash
git clone https://github.com/ramazontursunov07/maxway.git
cd maxway
```

2. Create a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate        # on Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Apply migrations and create an admin user:

```bash
python manage.py migrate
python manage.py createsuperuser
```

4. Start the server:

```bash
python manage.py runserver
```

Open http://127.0.0.1:8000/ in your browser.

### Run with Docker

```bash
docker-compose up --build
```

## Author

Ramazon Tursunov, Backend Developer (Python, Django)

- GitHub: [ramazontursunov07](https://github.com/ramazontursunov07)

## License

This project is licensed under the MIT License.
