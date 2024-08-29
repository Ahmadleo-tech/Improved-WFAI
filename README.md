Here's a description you can use to upload this project to GitHub:

---

# Weather Forecast AI with Voice Interaction

This Python project is a voice-interactive AI that retrieves and reports current or future weather conditions for a specified city. The program leverages the OpenWeatherMap API to fetch weather data and uses text-to-speech and speech recognition technologies to interact with the user. It also includes customizable alarm conditions for temperature thresholds and rain alerts.

## Features

- **Voice Interaction**: The AI can listen to user commands, respond with voice alerts, and ask for input via voice or keyboard.
- **Weather Reports**: Get real-time weather updates or a 3-hour weather forecast for any city worldwide.
- **Temperature Alerts**: Set custom alarm conditions based on temperature thresholds in Celsius or Fahrenheit.
- **Rain Alerts**: The AI can notify you if rain is detected in the forecast.
- **Manual or Voice Input**: Choose to enter the city name manually or through voice commands.

## Requirements

- Python 3.x
- `pyowm`
- `pyttsx3`
- `speech_recognition`
- `certifi` (Optional: Ensure secure connections)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/weather-forecast-ai.git
   cd weather-forecast-ai
   ```

2. Install the required dependencies:
   ```bash
   pip install pyowm pyttsx3 speechrecognition certifi
   ```

3. Replace the placeholder API key with your own OpenWeatherMap API key in the `api_key` variable.

## Usage

1. Run the script:
   ```bash
   python weather_ai.py
   ```

2. Follow the voice prompts to either input the city name manually or speak it aloud.

3. Choose your preferred temperature scale (Celsius or Fahrenheit) and specify whether you want the current weather or a future forecast.

4. The AI will fetch the weather data, check for any alarm conditions, and provide a detailed weather report through both speech and text.

## Notes

- Ensure your microphone is working properly for voice commands.
- You can customize temperature thresholds and enable/disable rain alarms by modifying the `self.to_low`, `self.to_high`, and `self.rain_alarm` variables in the `AI` class.

---

Feel free to customize the description further based on your project's specifics!
