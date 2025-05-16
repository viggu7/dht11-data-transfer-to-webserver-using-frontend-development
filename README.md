🌡️ DHT11 IoT Dashboard – G. Pulla Reddy College
A dynamic, real-time web dashboard that displays live temperature and humidity readings from a DHT11 sensor connected via ESP8266 to ThingSpeak Cloud. The UI updates every 5 seconds and the background image changes depending on the temperature 🌞❄️.

🖼️ Live Preview
The dashboard looks modern and adapts the feel of summer or winter based on temperature.
Summer (≥ 25°C) → summer.png ☀️
Winter (< 25°C) → winter.png ❄️

🛠️ Tech Stack
✅ HTML5 + CSS3 — Dashboard UI
✅ JavaScript — Fetching live data from ThingSpeak every 5 seconds
✅ ThingSpeak API — Cloud for logging sensor data
✅ DHT11 + ESP8266 — Hardware to measure and send data
✅ Dynamic Background — Changes based on temperature (warm/cool)

🚀 How It Works – Step-by-Step
1️⃣ DHT11 sensor reads the temperature 🌡️ and humidity 💧
2️⃣ ESP8266 sends the data to ThingSpeak every few seconds 📡
3️⃣ Webpage fetches data from this URL:
https://api.thingspeak.com/channels/2965118/feeds/last.json?api_key=TJAWGGGWS732GCYY
4️⃣ JavaScript updates the DOM every 5s ⏱️ and shows:
  • Temperature 🌡️ in °C
  • Humidity 💧 in %
  • Current time 🕒
5️⃣ If temperature ≥ 25°C → summer.png as background ☀️
  If temperature < 25°C → winter.png as background ❄️

📁 Files Included
• index.html – Main dashboard code
• summer.png – Background image for summer 🌞
• winter.png – Background image for winter ❄️
• README.md – This full explanation

💻 How to Run Locally
1️⃣ Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/dht11-iot-dashboard.git  
2️⃣ Open index.html in your browser 🌐
3️⃣ Live data will auto-refresh every 5 seconds 🔄
4️⃣ Background will adapt based on temperature 🚀

📊 Live Sensor Data
• Channel ID: 2965118
• Read API Key: TJAWGGGWS732GCYY
• Hosted on: ThingSpeak Cloud 🌐

👨‍💻 Contributors
Project developed by final year team – G. Pulla Reddy College ❤️
• Mukesh
• Vignesh
• Charan
• Pavan
• Chandra
• Mahesh

🧠 Concepts Demonstrated
• Real-time IoT data visualization
• Cloud-to-Frontend communication
• Dynamic UI using JS based on sensor feedback
• Integration of HTML, CSS, JavaScript with hardware
• Responsive design and live updates without refresh

⭐ Support
If you liked this project, give it a ⭐ on GitHub!
Pull requests, suggestions, and contributions are always welcome 🙌
