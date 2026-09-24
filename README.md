# Python Weather Lookup

Python Weather Lookup is a command-line application that retrieves current U.S. weather conditions from the OpenWeather API. Users can search by ZIP code or by city and state, choose temperature units, and view a formatted terminal report.

## Features

- Search current weather by U.S. ZIP code
- Search current weather by city and state
- Choose Fahrenheit, Celsius, or Kelvin
- Validates menu choices, ZIP codes, city names, and state abbreviations
- Handles API, timeout, connection, and response errors
- Uses environment variables so API keys are not stored in source code

## Technologies

- Python
- OpenWeather Geocoding API
- OpenWeather Current Weather API
- `requests`
- `python-dotenv`

## Setup

1. Install Python 3.
2. Install dependencies:

```bash
pip install requests python-dotenv
```

3. Create a `.env` file in the project folder:

```bash
OPENWEATHER_API_KEY=your_openweather_api_key
```

4. Run the app:

```bash
python weather_app.py
```

## Sample Output

```text
======================================================================
Weather for: Omaha, Nebraska, US
----------------------------------------------------------------------
Conditions : Clear Sky
Temperature: 72.5 °F
  High/Low : 75.2 °F / 69.8 °F
Humidity   : 45%
Pressure   : 1016 hPa
Clouds     : 0% coverage
Wind Speed : 8.1 mph
======================================================================
```

## Notes

This project is intended as a small API-focused Python application demonstrating input validation, REST API usage, environment-based configuration, exception handling, and readable command-line output.
