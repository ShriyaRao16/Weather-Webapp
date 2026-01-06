# Weather-Webapp
A simple web-based application that shows current weather using city name or live location and provides clothing recommendations based on temperature.
 # Tech Stack
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Weatherbit](https://img.shields.io/badge/Weatherbit-00AEEF?style=for-the-badge&logo=cloud&logoColor=white)
![Geolocation](https://img.shields.io/badge/Geolocation-4285F4?style=for-the-badge&logo=google-maps&logoColor=white)

## 🏗️ Project Architecture

```text
User
 │
 │  Enter City Name / Use Live Location
 ▼
Frontend (HTML + CSS + JavaScript)
 │
 │  UI Components
 │  ├─ City Input Field
 │  ├─ Live Location (Geolocation API)
 │  ├─ Weather Display Card
 │  ├─ Temperature Color Indicator
 │  ├─ Outfit Recommendation 
 │  └─ 7-Day Forecast Section
 │
 │  API Requests
```
# How to Run Locally
1.)Clone the Repository
```md
git clone https://github.com/ShriyaRao16/Weather-Webapp.git
```
2.)Open the Project Folder
```md
cd Weather-Webapp
```
3.)Add Your Weatherbit API Key

  a.)Open weather.html in a code editor<br>
  b.) Locate the following line in the JavaScript section:
```text
const apiKey = "YOUR_API_KEY";
```
 c.)Replace YOUR_API_KEY with your actual Weatherbit API key:
 ```
const apiKey = "your_real_api_key_here";
```
⚠️ Make sure there are no spaces before or after the key.
 
 d.)Run the App

## 👕 Outfit Recommendation Logic

| Temperature | Recommendation |
|------------|----------------|
| < 15°C     | Jacket / Hoodie 🧥 |
| 15–24°C    | Casual wear 👕 |
| 25–34°C    | Light cottons 👗 |
| ≥ 35°C     | Very light clothing 🩳 |


License<br>
This project is open-source and free to use for learning and educational purposes.
