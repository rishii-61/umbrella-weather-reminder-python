#  Umbrella Weather Reminder (Python)

A Python-based weather assistant that checks live weather conditions, analyzes rain probability, and sends an email reminder if you need to carry an umbrella.  
This project uses the WeatherAPI service and Gmail SMTP to deliver timely updates, including a 3-day forecast, humidity, wind speed, sunrise/sunset time, and heat/cold alerts.

---

##  Features

###  Weather Intelligence
- Real-time weather check  
- Rain detection (Rain, Thunder, Drizzle, Showers, Snow)  
- Heat alert (> 35°C)  
- Cold alert (< 15°C)  
- Humidity detection  
- Wind speed summary  
- UV Index  
- Feels-like temperature  
- Sunrise and sunset times  
- 3-Day detailed forecast with rain probability  

###  Email Reminder System
- Sends reminder when umbrella is needed  
- Sends normal update when weather is clear  
- Fully automated email generation  
- Uses Gmail SMTP with secure login  

###  Additional Enhancements
- Error handling for API issues  
- Logs weather checks into `weather_logs.txt`  
- Clean, modular functions  
- Easy to expand for automation (cron, schedule, etc.)

---

## Project Flow

1. Fetch weather data for the selected city  
2. Check for rain indicators  
3. Generate a detailed weather report  
4. Send an email with the full report  
5. Save a log entry with timestamp and weather details  

---

##  Technologies Used

- **Python 3**  
- **WeatherAPI** (weather data)  
- **SMTP (Gmail)** (sending emails)  
- **Requests library**  
- **Email MIMEText**  
- **File logging**

---

##  File Structure

# umbrella-weather-reminder-python
A Python program that fetches weather data and sends umbrella reminders via email
