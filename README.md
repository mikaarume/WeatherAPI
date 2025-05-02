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

Here are the screenshots of the Object Repository
<img width="1147" alt="Screenshot 2025-05-02 at 17 18 11" src="https://github.com/user-attachments/assets/77df2338-655d-4c04-b56c-b6df463be093" />



<img width="1147" alt="Screenshot 2025-05-02 at 17 18 25" src="https://github.com/user-attachments/assets/088ef202-48da-4883-a377-dc0560766770" />


Here are the screenshot at testcase

<img width="1375" alt="Screenshot 2025-05-02 at 17 19 39" src="https://github.com/user-attachments/assets/489102b9-9b7c-48fa-8986-ba164a7524d0" />


<img width="1375" alt="Screenshot 2025-05-02 at 17 20 02" src="https://github.com/user-attachments/assets/0d36ece5-f015-4074-ad12-026c261e5318" />











