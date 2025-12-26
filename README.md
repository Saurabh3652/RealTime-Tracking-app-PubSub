# 📍 Realtime Location Tracking App

A real-time web application that tracks and displays live user locations on an interactive map using **Socket.IO** and **Leaflet.js**.

---

## 🚀 Features

- 🌍 Live location tracking
- 📡 Real-time communication with Socket.IO
- 🗺️ Interactive map using Leaflet & OpenStreetMap
- 👥 Supports multiple users simultaneously
- 🔄 Live marker updates as users move
- ❌ Removes marker when a user disconnects

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js  
- **Realtime**: Socket.IO  
- **Frontend**: EJS, HTML, CSS, JavaScript  
- **Maps**: Leaflet.js + OpenStreetMap  
- **Geolocation**: Browser Geolocation API  

---

## 📂 Project Structure

realtime-tracking-app/
├── app.js
├── package.json
├── views/
│ └── index.ejs
└── public/
├── css/
│ └── style.css
└── js/
└── script.js


---

## ⚙️ Setup & Run Locally

### 1️⃣ Clone the repository
bash
git clone https://github.com/your-username/realtime-tracking-app.git
cd realtime-tracking-app``

###📍 How It Works

User allows location access

Browser captures live coordinates using Geolocation API

Location is sent to the server via Socket.IO

Server broadcasts updates to all connected clients

Leaflet updates or creates markers in real time

##🧪 Testing Multiple Users

To see multiple markers:

Open the app on different devices

Use Chrome DevTools → Sensors → Location override

Open in different browsers or incognito mode

Multiple tabs on the same device may overlap markers due to identical GPS coordinates.

🔐 Privacy

Location access is required for tracking

No user location data is stored permanently

##🧠 Future Enhancements

User authentication

Marker clustering

Route / path tracking

User labels instead of socket IDs

Mobile-first UI

Cloud deployment

##🤝 Contributing

Contributions are welcome!

Fork the repository

Create a new branch

Commit your changes

Open a Pull Request
