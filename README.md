This repository contains API test cases for weather forecast and air pollution data using OpenWeatherMap API and Katalon Studio.

✅ Test Cases
WeatherForecast: Tests 5-day weather forecast data for South Jakarta

AirPollution: Tests current air pollution data for South Jakarta

Each test case includes:

Status code validation (200)

Key property checks (e.g., city.name, components.co, etc.)

⚠️ About JSON Schema Validation
Initially, I attempted to use JSON Schema validation with the JsonSchemaValidator library, but encountered unresolved import and plugin issues:

"unable to resolve class katalon.library.jsonschema.JsonSchemaValidator"

Due to this, I excluded JSON Schema validation from the test cases and focused on validating essential JSON properties manually using verifyElementPropertyValue.

🔧 Tools Used
Katalon Studio for test creation and execution

OpenWeatherMap API for real-time weather and air quality data








