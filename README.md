# Weather Dashboard
This project is a Python-based weather dashboard that fetches real-time weather data from OpenWeather API and saves it to an Amazon S3 bucket. It is designed to provide weather information for specified cities and store this data securely in the cloud for later use or analysis.

# Features
* Fetches real-time weather data from OpenWeather API.
* Supports multiple cities.
* Saves weather data as JSON to an S3 bucket.
* Automatically creates an S3 bucket if it doesn't exist.
* Logs weather information including temperature, humidity, and conditions.

# Prerequisites
To run this project, you'll need:

* Python 3.7+
* AWS Account with S3 permissions
* OpenWeather API Key
* .env file to store API keys and credentials

# Setup
1. I created local folder 30days-devops-challenge and inside it i created another folder weather-dashboard-demo then cd into the weather-dashboard-demo folder.

2. I installed all the depencies 
```
pip install -r requirements.txt
```

3. Then i configured my .env with my AWS Credentials and Openweather API key
```
OPENWEATHER_API_KEY=my_openweather_api_key
AWS_BUCKET_NAME=my_s3_bucket_name
```

4. I run my dashboard using

```
pythoon3 src/waetherdashboard.py

```

