# Weather WebApp

This project is a simple weather web application built using Flask and the OpenWeatherMap API. The frontend is styled using Tailwind CSS, and the project was developed as part of an exercise on Resolve.ai.

## Features

- Search for the current weather in any city.
- Displays temperature, weather description, and an icon representing the weather.

## Technologies Used

- Flask
- OpenWeatherMap API
- Tailwind CSS

## Installation

1. Clone the repository:
   
 ```bash
git clone  https://github.com/SHIV000000/resolve.ai-project-1-weather-webapp.git
   ```
```bash
cd resolve.ai-project-1-weather-webapp
```
## Create a virtual environment and activate it:

```bash
python -m venv venv
```
## on macos\Unix `source venv/bin/activate`   On Windows, use `venv\Scripts\activate`

## Install the required packages:

```bash
pip install Flask requests
```
Set your OpenWeatherMap API key in the app.py file:

```python

API_KEY = 'your_openweather_api_key'
```
## Run the Flask application:

```bash
python app.py
```
## Open your web browser and go to http://127.0.0.1:5000/.
