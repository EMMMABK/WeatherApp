# Weather App

Welcome to the **Weather App**! This is a simple and visually appealing web application built with Django that displays current weather information for any city entered by the user.

---

## 🌟 Features

- **City Weather Search**: Search for current weather details by entering the name of a city.
- **Image Integration**: Fetches and displays an image representing the searched city using Google's Custom Search API.
- **Dynamic UI**: Clean and responsive user interface styled with CSS.
- **Real-time Updates**: Fetches live weather data.
- **Error Handling**: Gracefully handles invalid or unavailable city searches.
- **Default City**: Displays weather information for New York by default.

---

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (with a responsive and modern design)
- **APIs**: 
  - OpenWeatherMap API for weather data
  - Google Custom Search JSON API for city images
- **Database**: SQLite (default Django database)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- pip (Python package manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up environment variables (e.g., `.env` file):
   ```env
   SECRET_KEY=your_secret_key
   DEBUG=True
   API_KEY=your_google_api_key
   SEARCH_ENGINE_ID=your_google_search_engine_id
   API=your_openweathermap_api_key
   ```
5. Run database migrations:
   ```bash
   python manage.py migrate
   ```
6. Start the development server:
   ```bash
   python manage.py runserver
   ```
7. Open your browser and go to `http://127.0.0.1:8000/`.

---

## 📂 Project Structure

```
weather/
├── weather/               # Project settings and configuration
│   ├── settings.py        # Main settings for the project
│   ├── urls.py            # URL routing for the project
│   └── wsgi.py            # WSGI entry point
├── weatherapp/            # Main app containing core logic
│   ├── templates/         # HTML templates for the app
│   │   └── index.html     # Main page for displaying weather
│   ├── static/            # Static files (CSS, JavaScript, images)
│   │   └── style.css      # Styling for the application
│   ├── views.py           # Logic for fetching and processing data
│   └── urls.py            # URL routing for the app
└── db.sqlite3             # SQLite database
```

---

## 🎨 Style

The application is styled with modern CSS for a clean and polished look. Here are some highlights of the design:

- **Background**: Full-screen responsive background.
- **Form Styling**: Intuitive input field and buttons.
- **Weather Display**: Elegant layout for displaying temperature, city name, weather condition, and city image.

---

## 🖼️ Screenshots

![Weather App Screenshot](/assets/weatherapp1.png)
![Weather App Screenshot](/assets/weatherapp2.png)
![Weather App Screenshot](/assets/weatherapp3.png)
![Weather App Screenshot](/assets/weatherapp4.png)


---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Commit your changes and open a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
