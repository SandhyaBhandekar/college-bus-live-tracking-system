# College Bus Live Tracking System

## 📌 Project Overview

The College Bus Live Tracking System is a web-based application that allows students to track the real-time location of their college bus. The system uses GPS coordinates from the driver's mobile device and displays the location on an interactive map.

This project uses **Leaflet.js** with **OpenStreetMap** to display the map, which is completely free and open-source. Unlike Google Maps, this system does not require any paid APIs.

The main purpose of this project is to help students know the current location of the bus and reduce waiting time at bus stops.

---

## 🎯 Objective

The objective of this project is to develop a simple and efficient bus tracking system that allows students to track the live location of the college bus using open-source technologies.

---

## 🚀 Features

- Real-time bus location tracking
- Interactive map using Leaflet.js
- Free map services using OpenStreetMap
- GPS location sharing from driver’s mobile device
- Web-based interface accessible from any browser
- Lightweight and easy to use system

---

## 🛠 Technologies Used

- HTML
- CSS
- JavaScript
- Leaflet.js
- OpenStreetMap
- GPS (Mobile Location)

---

## 🗂 Project Structure
college-bus-live-tracking-system/
│
├── index.html (Student Map Interface)
├── driver.html (Driver Location Sharing Page)
├── README.md


---

## ⚙️ How the System Works

1. The **driver opens driver.html** on their mobile phone.
2. The browser requests **GPS location permission**.
3. The driver's mobile device provides **latitude and longitude coordinates**.
4. These coordinates are used to update the bus position.
5. Students open the **student page (index.html)** to see the bus location on the map.

---

## 🌐 Live Demo

Student Page  
https://sandhyabhandekar.github.io/college-bus-live-tracking-system/

Driver Page  
https://sandhyabhandekar.github.io/college-bus-live-tracking-system/driver.html

---

## 🧭 System Architecture
Driver Mobile GPS
↓
Driver Web Page
↓
Location Coordinates
↓
Leaflet Map Update
↓
Student Web Interface



---

## 🔮 Future Improvements

- Develop a dedicated **Android mobile application for the driver**
- Integrate **Firebase Realtime Database for live tracking**
- Support **multiple buses tracking**
- Add **bus route information**
- Implement **driver authentication system**
- Improve **real-time update accuracy**

---

## 📚 Advantages

- Completely free and open-source
- No paid APIs required
- Easy to deploy using GitHub Pages
- Works on any device with internet access
- Simple and lightweight system

---

## 🎓 Conclusion

The College Bus Live Tracking System provides a simple and effective solution for tracking college buses in real-time. By using open-source technologies like Leaflet.js and OpenStreetMap, the system eliminates the need for paid map services while still providing accurate and interactive tracking.

This project demonstrates how GPS-based tracking systems can be implemented using modern web technologies.
