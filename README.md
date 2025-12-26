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

---

## ⚙️ Setup & Run Locally

### Clone the repository
git clone https://github.com/your-username/realtime-tracking-app.git  ](https://github.com/Saurabh3652/RealTime-Tracking-app-PubSub.git
cd realtime-tracking-app

### Install dependencies
npm install

### Start the server
node app.js

### Open in browser
http://localhost:3000

---

## 📍 How It Works

1. User allows location access  
2. Browser captures live coordinates using the Geolocation API  
3. Location is sent to the server via Socket.IO  
4. Server broadcasts updates to all connected clients  
5. Leaflet updates or creates markers in real time  

---

## 🧪 Testing Multiple Users

- Open the app on different devices  
- Use Chrome DevTools → Sensors → Location override  
- Open in different browsers or incognito mode  

Multiple tabs on the same device may overlap markers due to identical GPS coordinates.

---

## 🔐 Privacy

- Location access is required for tracking  
- No user location data is stored permanently  

---

## 🧠 Future Enhancements

- User authentication  
- Marker clustering  
- Route / path tracking  
- User labels instead of socket IDs  
- Mobile-first UI  
- Cloud deployment  

---

## 🤝 Contributing

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Open a Pull Request  

---

## 📄 License

MIT License

---

## 👨‍💻 Author

**Saurabh Patel**  
Full-Stack Developer  

---

## ✅ Final steps

```bash
git add README.md
git commit -m "Add README"
git push
