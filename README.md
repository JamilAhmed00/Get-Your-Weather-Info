Django Weather Update Project

Introduction:
---------------
This is a Django web application that provides real-time weather updates based on user input. The project utilizes the OpenWeatherMap API to fetch weather data for a given city.

Features:
---------------
- Weather Information: Users can enter a city and get information such as temperature, pressure, humidity, and weather description.
- Responsive Design: The web interface is designed using Bootstrap, making it accessible and visually appealing.

Requirements:
---------------
- Python (3.x recommended)
- Django
- Bootstrap (CDN included in the HTML)

Usage:
---------------
1. Installation: Install the required dependencies using the following commands:
    ```
    pip install django
    ```

2. Run the Application:
    ```
    python manage.py runserver
    ```
    Access the application at http://localhost:8000.

3. Usage: Enter the desired city in the search bar and submit the form to get the weather update.

Project Structure:
---------------
- weather_project/: Django project folder.
  - weather_app/: Django app folder.
    - views.py: Contains the logic to fetch weather data.
    - templates/index.html: HTML template for the user interface.

Configuration:
---------------
1. Obtain OpenWeatherMap API Key: OpenWeatherMap API
2. Update the API key in views.py: Replace 'ad6d91c541e7f84004e3201f55d89a05' with your API key.

Author:
---------------
[Jamil Ahmed]

Preview:


