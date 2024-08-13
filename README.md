# Weather Application

## Overview

A Flask-based weather application using Leaflet and OpenWeatherMap API. Fetch and display current weather data by city/state/country or by selecting a location on a map.

## Features

- Fetch weather by city, state, and country.
- Fetch weather by map location.
- Display weather icon, temperature, and description.
- Display latitude and longitude of selected location.

## Technologies

- Python
- Flask
- Leaflet
- OpenWeatherMap API
- Bootstrap
- dotenv

## Installation

### Prerequisites

- Python 3.x
- pip

### Steps

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/weather-app.git
    cd weather-app
    ```

2. **Set up virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Configure environment variables:**

    - Create a `.env` file in the root directory.
    - Add your OpenWeatherMap API key:

      ```
      API_KEY=your_openweathermap_api_key
      ```

5. **Run the application:**

    ```bash
    flask run
    ```

6. **Open in browser:**

    Visit `http://127.0.0.1:5000/`.

## Usage

### By City/State/Country

1. Enter city, state, and country.
2. Click "Find".
3. View weather data.

### By Map

1. Click on the map.
2. Latitude and longitude fields populate automatically.
3. Click "Find".
4. View weather data.

## Project Structure

weather-app/
<br>
├── templates/
<br>
│ └── index.html # HTML template
<br>
├── app.py # Flask application
<br>
├── weather.py # Weather data fetching
<br>
├── requirements.txt # Dependencies
<br>
├── .gitignore # Environment variables (not included)
<br>
└── README.md # Project README



## License

Licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/)
- [Leaflet](https://leafletjs.com/)
- [Bootstrap](https://getbootstrap.com/)
