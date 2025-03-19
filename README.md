# Django React Project

This is a full-stack web application built with Django backend and React frontend.

## Project Structure

```
djangoreact/
├── reactfrontend/           # React application
├── mysite/            # Django project settings
├── manage.py          # Django management script
└── README.md          # This file
```

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.x
- Node.js and npm
- pip (Python package manager)

## Installation

### Backend Setup

1. Create and activate a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

2. Install Python dependencies:
```bash
python -m pip install django django-cors-headers djangorestframework
```

3. Apply database migrations:
```bash
python manage.py migrate
```

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd reactfrontend
```

2. Install Node dependencies:
```bash
npm install
```

3. Build the React application:
```bash
npm run build
```

## Development

### Running the Development Server

1. Start the Django development server:
```bash
python manage.py runserver
```

2. For frontend development, in a separate terminal:
```bash
cd reactfrontend
npm start
```

The application will be available at:
- Django Backend: http://localhost:8000
- React Frontend (development): http://localhost:3000

## Features

- Django REST framework for backend API
- React for frontend UI
- CORS headers configured for development
- Static file serving configured
- Database configuration (SQLite by default)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
