# 🏀 [The Court Connect](https://thecourtconnect.onrender.com) 🏀
[![License: MIT](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

## 📝 Description
The Court Connect is a full-stack Flask web application that connects basketball enthusiasts with basketball courts around the world. Users can register, log in, and search for basketball courts via the Google Maps API. They can then save their favorite courts to their profile and rate them. 

## 🗺️ APIs Used
Google Maps Javascript API: https://developers.google.com/maps/documentation/javascript

Google Maps Places API (New): https://developers.google.com/maps/documentation/places/web-service/text-search

Google Maps Geocoding API: https://developers.google.com/maps/documentation/javascript/geocoding

## 📊 Features
- User Authentication & Profile Management
- Basketball Court Search & Mapping
- Save, Manage, & Rate Favorite Courts

## 🛠 Tech Stack
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)
![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=2f9fe3)
![Jasmine](https://img.shields.io/badge/jasmine-%238A4182.svg?style=for-the-badge&logo=jasmine&logoColor=white)

## 🎬 Getting Started

### 📦 Installation

1. **Clone the Repository & Setup Virtual Environment**
```
git clone https://github.com/yourusername/the-court-connect.git
cd the-court-connect
```

2. **Create and Activate a Virtual Environment**
```
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. **Install Dependencies**
```
pip install -r requirements.txt
```

4. **Configure Environment Variables**

- Create a .env file in the project root with the following variables
```
SECRET_KEY=your_secret_key
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

5. **Set Up the Database**

- Ensure that you have PostgreSQL installed and create the development database
```
createdb basketball_court_finder_db
```

## 💪🏽 Usage
### 🏃🏽‍♂️ Running the Application
- Start the Flask development server
```
flask run
```
- Visit http://localhost:5000 to access the application.

### 🔬 Running Tests
 **Back-End Tests**
- Run the Pytest suite to verify back-end functionality
```
pytest
```
**Front-End Tests**
- Open the SpecRunner.html file in your browser to run the Jasmine tests for front-end JavaScript functions.

## 🌐 Deployment & Hosting
The Court Connect is deployed on **Render** using the free tier, which spins down after 15 minutes of inactivity. To keep the app responsive, **UptimeRobot** is set up to ping the site every 14 minutes to prevent cold starts.

### Hosting:
- 🌍 Render: [TheCourtConnect](https://thecourtconnect.onrender.com/)
- 🔄 Keep-Alive Service: [UptimeRobot](https://uptimerobot.com/) (pings every 14 min)