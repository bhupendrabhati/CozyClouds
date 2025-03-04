## 30 Days DevOps Challenge - Weather Dashboard

## Day 1: 
## Building a weather data collection system using AWS S3 and OpenWeather API

## Weather Data Collection System - DevOps Day 1 Challenge.

## Project Overview:
## This project is a Weather Data Collection System that demonstrates core DevOps principles by combining:
	External API Integration (OpenWeather API)
	Cloud Storage (AWS S3)
	Infrastructure as Code
	Version Control (Git)
	Python Development
	Error Handling
	Environment Management

## Features:
	Fetches real-time weather data for multiple cities,
	Displays temperature (°F), humidity, and weather conditions,
	Automatically stores weather data in AWS S3,
	Supports multiple cities tracking,
	Timestamps all data for historical tracking,
	Technical Architecture,
	Language: Python 3.x,
	Cloud Provider: AWS (S3)
	External API: OpenWeather API
	Dependencies:
	boto3 (AWS SDK)
	python-dotenv
	requests

## Project Structure:
        weather-dashboard
                src/        
                    __init__.py
                    weather_dashboard.py
                tests/
                data/
                .env  
                .gitignore
                requirements.txt

## Setup Instructions:
	1. Clone the repository:
	--bash
	git clone https://github.com/bhupendrabhati/30days-weather-dashboard.git

	2. Install dependencies:
	bashCopypip install -r requirements.txt

	3. Configure environment variables (.env):
	CopyOPENWEATHER_API_KEY=your_api_key
	AWS_BUCKET_NAME=your_bucket_name

	4. Configure AWS credentials:bashCopyaws configure

	5. Run the application:
	python src/weather_dashboard.py

## What I Learned:

        1. AWS S3 bucket creation and management
        2. Environment variable management for secure API keys
        3. Python best practices for API integration
        4. Git workflow for project development
        5. Error handling in distributed systems
        6. Cloud resource management

## Future Enhancements:
	1. Add weather forecasting
	2. Implement data visualization
	3. Add more cities
	4. Create automated testing
	5. Set up CI/CD pipeline
